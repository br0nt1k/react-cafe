# Sip Happens Café ☕️

## 🌍 **International Version**

### 📌 Project Description

👋 A modern, interactive widget designed to collect and analyze customer feedback for a local coffee shop. The application focuses on clean, predictable state management, computing operational metrics on the fly, and ensuring bulletproof type safety.

### 💻 Core Technologies & Skills:

- 🔧 **Core:** React & TypeScript for precise component architecture.
- ⚡ **Build Tool:** Vite for fast feedback loops and bundling efficiency.
- ⭐ **Styling:** CSS Modules & modern-normalize for maintaining isolated layout parameters.
- 🛠️ **Code Style:** Code formatting driven strictly via Prettier.

### 💡 Key Skills & Concepts Implemented:

- **State Management:** Tracking collective review dimensions in a unified object via `useState`. Enforcing immutable updates using the JavaScript spread operator (`...votes`) to guarantee predictable lifecycle recalculations.
- **Lifting State Up:** Establishing a Single Source of Truth inside the root `App` component and driving children behaviors smoothly by distributing handlers (`handleVote`, `resetVotes`) down the prop pipeline.
- **Computed Data Processing:** Dynamically calculating absolute values (`totalVotes`) and satisfaction tracking (`positiveRate`) runtime during rendering cycles, completely eliminating out-of-sync bugs and extra hook variables.
- **Conditional Interface Rendering:** Designing real-time visual responses—toggling viewports cleanly between interactive statistical outputs (`VoteStats`) and clean user notices (`Notification`) contingent upon current interaction counts.
- **Strict Type Ecosystem:** Securing application runtimes by establishing custom data constraints (`Votes`), union states (`VoteType`), and declaring structural prop boundaries (`interface`) across all individual components.

### 📂 Project Structure:

```text
src/
├── components/
│   ├── App/
│   │   ├── App.tsx
│   │   └── App.module.css
│   ├── CafeInfo/
│   ├── Notification/
│   ├── VoteOptions/
│   └── VoteStats/
└── types/
    └── votes.ts        # Project global types configuration

```

### 🔗 Live Site:

👉 [View Sip Happens Café on Vercel](https://react-cafe-beta.vercel.app/)

---

## 🇺🇦 **Ukrainian Version**

### 📌 Опис проєкту

👋 Сучасний, інтерактивний віджет для збору та миттєвого аналізу відгуків відвідувачів кав'ярні. Застосунок зосереджений на побудові передбачуваної структури даних, динамічному розрахунку бізнес-метрик під час рендеру та суворій типізації.

### 💻 Основні Технології та Навички:

* 🔧 **Core:** React та TypeScript для створення масштабованої структури інтерфейсу.
* ⚡ **Build Tool:** Vite для швидкої розробки та миттєвого оновлення модулів.
* ⭐ **Стилізація:** CSS Modules та modern-normalize для абсолютної ізоляції та кросбраузерності макетів.
* 🛠️ **Code Style:** Форматування та чистота коду забезпечені інструментом Prettier.

### 💡 Отримані навички та практичний досвід:

* **Управління комплексним станом:** Організація логів у вигляді єдиного об'єкта через `useState`. Забезпечення правильного імутабельного оновлення за допомогою спред-оператора (`...votes`), що гарантує стабільний життєвий цикл інтерфейсу.
* **Підйом стану (Lifting State Up):** Збереження єдиного джерела істини (Single Source of Truth) в батьківському компоненті `App` та передача методів управління через пропси в дочірні віджети.
* **Обчислювальний стан (Computed State):** Розрахунок загальної кількості голосів (`totalVotes`) та відсотка позитивних відгуків (`positiveRate`) "на льоту" під час рендеру без створення зайвих стейтів, що запобігає десинхронізації даних.
* **Умовний рендеринг:** Реалізація динамічного UX — автоматичне перемикання між блоком живої статистики `VoteStats` та заглушкою `Notification` залежно від наявності активності користувача.
* **Сувора типізація:** Створення надійного середовища виконання завдяки кастомним інтерфейсам (`Votes`), союзним типам (`VoteType`) та чіткій типізації пропсів (interface) для кожного компонента.

### 🔗 Живий сайт:

👉 [Переглянути застосунок на Vercel](https://react-cafe-beta.vercel.app/)
