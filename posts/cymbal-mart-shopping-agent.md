<div align="center">

# 🛍️ Building CymbalMart Shopping Agent: An AI-Powered Event & Budget Planner

An interactive walk-through of how I designed and built an intelligent, budget-conscious party planning assistant with React, TypeScript, and modern AI agent workflows.

[![React](https://img.shields.io/badge/React-TypeScript-blue.svg?style=for-the-badge&logo=react&logoColor=white)](https://react.dev/)
[![Tailwind CSS](https://img.shields.io/badge/Tailwind_CSS-Styling-cyan.svg?style=for-the-badge&logo=tailwindcss&logoColor=white)](https://tailwindcss.com/)
[![GitHub](https://img.shields.io/badge/GitHub-Repository-black.svg?style=for-the-badge&logo=github&logoColor=white)](https://github.com/Hizba-cloud/cymbal-mart-shopping-agent)

</div>

---

## 🎯 The Challenge: Simplifying Event Planning
Planning any event—whether it's a child's birthday party, a corporate team-building event, or an outdoor wedding—involves a massive juggling act. You have to coordinate themes, estimate guest counts, manage strict budgets, and ensure no critical item gets left off the shopping list. 

Manual planning is tedious and often leads to overspending or missed essentials. I wanted to build a solution that automates the friction out of event preparation.

---

## 💡 Introducing CymbalMart Shopping Agent
**CymbalMart Shopping Agent** is an intelligent web application designed to convert raw event requirements into curated, budget-conscious shopping lists with real-time adjustments and voice integration.

### Core Capabilities:
* **Smart Event Curation:** Instantly generates tailored shopping lists based on party type, theme, guest count, and specific budget constraints.
* **Interactive AI Assistant (`CymbalMart Assistant`):** A built-in conversational chat interface to help users seamlessly plan and modify their events on the fly.
* **Dynamic Budget Recalculation:** Automatically updates and recalculates total expenses and item quantities as changes are made.
* **Hands-Free Voice Control:** Integrated voice command capabilities allowing users to navigate and complete the planning process entirely hands-free.

---

## 📸 Application Showcase

### 1. Central Event Dashboard
The starting hub where users configure their event parameters, theme choices, and guest counts:
<br>
<img src="Cymbal_Shopping_Agent.png" alt="CymbalMart Shopping Agent Dashboard" width="100%"/>

---

### 2. Interactive Store Mart Views
Browse through curated store inventories and item selections tailored specifically to your event:
<br>
<img src="Cymbal_Shopping_Mart1.png" alt="Shopping Mart View 1" width="100%"/>
<br>
<img src="Cymbal_Shopping_Mart2.png" alt="Shopping Mart View 2" width="100%"/>

---

### 3. Dynamic Shopping Lists & Real-Time Budgets
As modifications occur, expenses and quantities update instantly:
<br>
<img src="Cymbal_Shopping_List.png" alt="Dynamic Shopping List" width="100%"/>

---

### 4. Aisle Resources & Batch Recipes
Organize your physical or online shopping trips by store aisles and batch recipe requirements:
<br>
<img src="Cymbal_Aisle_Resources.png" alt="Aisle Resources" width="100%"/>
<br>
<img src="Cymbal_Batch_Recipe.png" alt="Batch Recipes" width="100%"/>

---

### 5. Hands-Free Voice Control & Event Timelines
Navigate menus completely hands-free and track milestone tasks leading up to your event date:
<br>
<img src="Cymbal_Hands_Free.png" alt="Hands-Free Voice Control" width="100%"/>
<br>
<img src="Cymbal_Timline.png" alt="Event Timeline" width="100%"/>

---

## 🛠️ Tech Stack & Architecture
* **Frontend:** React, TypeScript, Tailwind CSS
* **AI Integration:** Advanced Large Language Model agent workflows and natural language prompting frameworks
* **UI Components:** Custom modular modals, dynamic list views, and responsive design systems

---

## 📂 Project Structure
```text
├── src/
│   ├── components/     # UI components (Modals, Chat Assistant, Lists)
│   ├── App.tsx         # Main application entry point & state logic
│   └── main.tsx        # React DOM render setup
├── public/             # Static assets
├── package.json        # Project dependencies and scripts
└── README.md           # Project documentation
