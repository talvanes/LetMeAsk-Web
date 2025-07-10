# LetMeAsk-Web

A modern Q&A web application inspired by the latest [NLW #20 RocketSeat Event](https://www.rocketseat.com.br/nlw), built with a focus on real-time interactivity, clean architecture, and developer experience. This project was created during the NLW #20 event (July 2025), leveraging the best practices and technologies showcased by RocketSeat.

## 🚀 Tech Stack

- **Frontend Framework:** [React 18+](https://react.dev/) (with functional components & hooks)
- **Type System:** [TypeScript](https://www.typescriptlang.org/)
- **Build Tool:** [Vite](https://vitejs.dev/) (for lightning-fast development)
- **Styling:** CSS Modules, with a focus on modular and reusable styles
- **Component Library:** Custom UI components (see `src/components/ui/`)
- **State Management:** React Context API & hooks
- **Routing:** [React Router](https://reactrouter.com/) (if applicable)
- **Utilities:** Custom utility functions in `src/lib/utils.ts`
- **Linting & Formatting:** ESLint (with type-aware rules), Prettier, Biome
- **Testing:** (Add your testing stack here if applicable)

## 🏗️ Project Structure

```
LetMeAsk-Web/
├── public/                # Static assets
├── src/
│   ├── app.tsx            # Main App component
│   ├── main.tsx           # Entry point
│   ├── index.css          # Global styles
│   ├── components/
│   │   └── ui/            # Reusable UI components (e.g., Button)
│   ├── lib/
│   │   └── utils.ts       # Utility functions
│   └── pages/             # Page components (e.g., CreateRoom, Room)
├── package.json           # Project metadata & scripts
├── tsconfig*.json         # TypeScript configuration
├── vite.config.ts         # Vite configuration
├── biome.jsonc            # Biome configuration
└── README.md              # Project documentation
```

## ✨ Features

- **Create & Join Rooms:** Users can create new Q&A rooms or join existing ones.
- **Real-Time Interactions:** (If using a backend or Firebase, mention here)
- **Modern UI:** Clean, accessible, and responsive design.
- **Reusable Components:** Modular UI elements for rapid development.
- **Type Safety:** End-to-end TypeScript for reliability.
- **Developer Experience:** Fast HMR, strict linting, and easy-to-read codebase.

## 🧑‍💻 Design Patterns & Best Practices

- **Atomic Design:** UI components are organized by reusability and specificity.
- **Separation of Concerns:** Pages, components, and utilities are clearly separated.
- **Hooks & Context:** State and logic are managed with React hooks and Context API.
- **Type-First Development:** TypeScript is used throughout for type safety.
- **ESLint & Biome:** Enforced code quality and consistent style.

## 🛠️ Getting Started

1. **Install dependencies:**
   ```sh
   npm install
   ```
2. **Start the development server:**
   ```sh
   npm run dev
   ```
3. **Build for production:**
   ```sh
   npm run build
   ```
4. **Preview production build:**
   ```sh
   npm run preview
   ```

## 📝 Linting & Formatting

- **ESLint:** Type-aware linting with recommended and strict rules. See `eslint.config.js` for customizations.
- **Biome:** Used for code formatting and additional linting. See `biome.jsonc`.
- **Prettier:** (If used, mention here)

## 🌟 About NLW #20 RocketSeat

This project was built as part of the [NLW #20](https://www.rocketseat.com.br/nlw) (Next Level Week) event by RocketSeat, July 2025. NLW is a hands-on coding event where thousands of developers build real-world projects together, learning the latest in web technologies, design patterns, and best practices. LetMeAsk-Web reflects the spirit and technical stack of NLW #20, focusing on modern React, TypeScript, and rapid development with Vite.

## 🤝 Contributing

Pull requests are welcome! For major changes, please open an issue first to discuss what you would like to change.

## 📄 License

[WTFPL](LICENSE) (Do What The F*ck You Want To Public License)
