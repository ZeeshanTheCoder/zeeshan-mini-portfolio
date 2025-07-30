# Zeeshan Mini Portfolio

A modern, responsive portfolio web app built with React and Vite, featuring:
- Animated header and section transitions
- Responsive sidebar navigation for mobile
- Project showcase with image carousel
- Contact form with thank you page
- GitHub Finder tool

## Features
- **React Router** for smooth page navigation
- **Responsive Design**: Sidebar menu appears on mobile
- **Project Gallery**: Carousel with project images and links
- **Contact Form**: Sends messages via FormSubmit and redirects to a thank you page
- **GitHub Finder**: Search and display any GitHub user's profile

## Folder Structure
```
public/
  images/           # All images used in the app
  resume/           # Your downloadable resume PDF
src/
  components/       # All React components (Home, Projects, Contact, etc.)
  App.jsx           # Main app and routing
  App.css           # Main styles
```

## Getting Started
1. **Install dependencies:**
   ```bash
   npm install
   ```
2. **Run the development server:**
   ```bash
   npm run dev
   ```
3. **Open in browser:**
   Visit [http://localhost:5173](http://localhost:5173) (or the port shown in your terminal)

## Customization
- **Resume:** Place your PDF in `public/resume/` and update the file name in `Home.jsx` if needed.
- **Images:** Place all images in `public/images/` and reference them with `/images/...` paths in your components.
- **Projects:** Edit `src/components/Projects.jsx` to add or update your projects.
- **Contact Form:** The form uses [FormSubmit](https://formsubmit.co/) for submissions. Update the action URL if you want to use your own email.

## License
This project is licensed under the [Apache License 2.0](LICENSE) © 2025 ZeeshanTheCoder.
# React + Vite

This template provides a minimal setup to get React working in Vite with HMR and some ESLint rules.

Currently, two official plugins are available:

- [@vitejs/plugin-react](https://github.com/vitejs/vite-plugin-react/blob/main/packages/plugin-react) uses [Babel](https://babeljs.io/) for Fast Refresh
- [@vitejs/plugin-react-swc](https://github.com/vitejs/vite-plugin-react/blob/main/packages/plugin-react-swc) uses [SWC](https://swc.rs/) for Fast Refresh

## Expanding the ESLint configuration

If you are developing a production application, we recommend using TypeScript with type-aware lint rules enabled. Check out the [TS template](https://github.com/vitejs/vite/tree/main/packages/create-vite/template-react-ts) for information on how to integrate TypeScript and [`typescript-eslint`](https://typescript-eslint.io) in your project.
