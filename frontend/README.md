# React + Vite

This template provides a minimal setup to get React working in Vite with HMR and some ESLint rules.

Currently, two official plugins are available:

- [@vitejs/plugin-react](https://github.com/vitejs/vite-plugin-react/blob/main/packages/plugin-react/README.md) uses [Babel](https://babeljs.io/) for Fast Refresh
- [@vitejs/plugin-react-swc](https://github.com/vitejs/vite-plugin-react-swc) uses [SWC](https://swc.rs/) for Fast Refresh

## Expanding the ESLint configuration

If you are developing a production application, we recommend using TypeScript and enable type-aware lint rules. Check out the [TS template](https://github.com/vitejs/vite/tree/main/packages/create-vite/template-react-ts) to integrate TypeScript and [`typescript-eslint`](https://typescript-eslint.io) in your project.

Start Command: 
    under frountend folder run: npm install
    Then run: npm run dev
    Now you can load the page at: http://localhost:5173/

Coding Sturcture info:
    1. Everything(tags/subpages) lists on the left side of dashboard is coded at listItems.jsx, feel free to add more tags.
        Format: <ListItemIcon> + <ListItemText> Icon tag can be found in @mui, to be sepecfic, go to https://mui.com/material-ui/material-icons/