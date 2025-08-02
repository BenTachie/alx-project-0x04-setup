
# 🧠 StateCraft: Mastering State Management with Redux & Context API

An interactive React-based counter application demonstrating progressive approaches to state management—from `useState`, to Context API, and finally Redux Toolkit. This project aims to educate developers on choosing the right tool for the right complexity in real-world React applications.

---

## 🚀 Project Overview

**StateCraft** is designed to showcase and compare different strategies for managing state in React applications. By implementing the same counter application across three distinct state management patterns, this project helps reinforce the concepts of local vs global state, scalability, and maintainability.

Each variant is implemented in its own version:
- `0x04`: `useState` – Component-local state
- `0x05`: `Context API` – Global state via React context
- `0x06`: `Redux Toolkit` – Scalable and production-grade state management

---

## 🎯 Learning Objectives

- Understand and apply the `useState` hook for local component state
- Implement global state with Context API and custom hooks
- Master Redux Toolkit for scalable and complex application state
- Compare and contrast different state management strategies
- Apply best practices such as separation of concerns and immutability
- Ensure type safety and structure using TypeScript
- Achieve state persistence across components

---

## 🧰 Tech Stack

| Tech             | Version     |
|------------------|-------------|
| React            | 18.x        |
| Next.js          | Latest      |
| TypeScript       | ^4.x        |
| Redux Toolkit    | ^1.x        |
| React-Redux      | ^8.x        |
| Node.js          | >=14        |
| npm or yarn      | Latest      |

---

## 📁 Project Structure
```
├── pages/
│ ├── counter-app.tsx # Main counter page
│
├── components/
│ ├── CounterDisplay.tsx # Displays current count
│ ├── CounterControls.tsx # Buttons for interaction
│ └── Header.tsx # Shared layout header
│
├── layouts/
│ └── DefaultLayout.tsx # App layout wrapper
│
├── context/ (for Context API version)
│ └── CountContext.tsx # Context provider and hooks
│
├── store/ (for Redux version)
│ └── store.ts # Redux store config
│
├── public/
├── styles/
├── tsconfig.json
└── package.json

```
---

## 🧪 Variants

### ✅ 0x04 – `useState`
- Pure local state using React's `useState`
- Simplicity-first approach within one component
- Good for small, isolated logic

### 🌐 0x05 – `Context API`
- Introduces shared state across components
- Uses a custom context with TypeScript interfaces
- Wrapped in `_app.tsx` to provide global access

### 🏛️ 0x06 – `Redux Toolkit`
- Scalable state via Redux slices and global store
- Strong typing with selectors and dispatch
- Ideal for large-scale applications with middleware needs

---

## 💡 Best Practices Followed

- ✅ **Component Isolation**: UI separated from state logic
- ✅ **Immutability**: State updates are immutable
- ✅ **Custom Hooks**: Abstracted context logic
- ✅ **Typed State**: Full TypeScript support
- ✅ **Redux Toolkit Slices**: Modular store design
- ✅ **Single Responsibility Principle**: One job per file/component

---

## 🧪 Running the Project

```
# Install dependencies
npm install

# Run the development server
npm run dev
Each version can be run by toggling/commenting the relevant implementation in pages/counter-app.tsx or setting up separate routes.
```

## 🧭 Manual QA & Review

- This project is subject to manual QA review. Ensure:
- State updates work as expected
- Buttons trigger correct actions
- Redux DevTools integration is functioning (for 0x06)
- Components are responsive and accessible

## 📚 Further Learning

- React Docs
- Redux Toolkit Docs
- React Context API
- TypeScript in React

## 🧠 Quote to Code By
>“Simplicity is the ultimate sophistication.” – Leonardo da Vinci

🙌 Feedback & Contributions
PRs and issues are welcome. Let’s improve state together!
