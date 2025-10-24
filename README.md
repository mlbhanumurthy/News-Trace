# 🗞️ News Trace Mapper

> **An interactive AI-powered dashboard for visualizing and analyzing the flow of news, journalists, and media outlets across topics and time.**

![TypeScript](https://img.shields.io/badge/TypeScript-3178C6?logo=typescript&logoColor=white)
![React](https://img.shields.io/badge/React-20232A?logo=react&logoColor=61DAFB)
![Vite](https://img.shields.io/badge/Vite-646CFF?logo=vite&logoColor=white)
![TailwindCSS](https://img.shields.io/badge/TailwindCSS-38B2AC?logo=tailwindcss&logoColor=white)
![License](https://img.shields.io/badge/License-MIT-green)

---

## 📖 Overview

**News Trace Mapper** helps users explore the relationships between **news sources**, **journalists**, and **topics** in a visual and insightful way.  
It leverages structured data and AI-driven analysis to map the spread and interconnection of news stories, providing deep insights into media activity patterns.

---

### ✨ Key Features
- 🧠 **AI-based categorization** of news sources and topics  
- 🕸️ **Interactive network graphs** connecting outlets and journalists  
- 📊 **Activity and topic distribution charts**  
- 🔍 **Powerful search and filtering** across datasets  
- 🌗 **Light/Dark theme toggle** for accessibility  
- 📱 **Responsive design** built with modern UI components

---

## 🧩 Project Structure

NewsTraceMapper/
├── client/ # React + TypeScript frontend

│ ├── src/

│ │ ├── components/ # Reusable UI and visualization components

│ │ ├── main.tsx # Entry point

│ │ └── App.tsx # Root component

│ └── public/

│ └── favicon.png

├── drizzle.config.ts # Database or ORM configuration

├── tailwind.config.ts # Tailwind setup

├── vite.config.ts # Build and dev config

├── tsconfig.json # TypeScript configuration

├── components.json # Shadcn component registry

└── design_guidelines.md # UI/UX documentation

---

## ⚙️ Tech Stack

| Layer | Technology |
|-------|-------------|
| Frontend | React (Vite) + TypeScript |
| Styling | TailwindCSS + Shadcn UI |
| Visualization | Recharts / D3.js (for charts & graphs) |
| Configuration | Drizzle ORM + Vite |
| Design | Modular and theme-based system |

---

## 🚀 Getting Started

1️⃣ Clone the Repository
``bash
git clone https://github.com/your-username/news-trace-mapper.git
cd news-trace-mapper

2️⃣ Install Dependencies
npm install

3️⃣ Start the Development Server
npm run dev

4️⃣ Build for Production
npm run build

---

🧠 Core Components
Component	Description
NetworkGraph.tsx	Displays connections between journalists and outlets
ActivityChart.tsx	Visualizes news publishing trends
TopicDistribution.tsx	Shows topic-wise coverage distribution
SearchBar.tsx	Enables quick lookup of sources or topics
StatCard.tsx	Displays key metrics at a glance
ThemeToggle.tsx	Switches between light and dark mode

---

📚 Design Guidelines
Refer to design_guidelines.md for UI principles, color palette, and accessibility standards followed in the project.

---

🛡️ License
This project is licensed under the MIT License.

---

Future Enhancements

🔗 Integration with live news APIs

🧮 Sentiment analysis on articles

🕵️‍♂️ Fake news detection and source credibility scoring

🌐 Multi-language support

