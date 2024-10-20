# React + Vite

<!-- This template provides a minimal setup to get React working in Vite with HMR and some ESLint rules.

Currently, two official plugins are available:

- [@vitejs/plugin-react](https://github.com/vitejs/vite-plugin-react/blob/main/packages/plugin-react/README.md) uses [Babel](https://babeljs.io/) for Fast Refresh
- [@vitejs/plugin-react-swc](https://github.com/vitejs/vite-plugin-react-swc) uses [SWC](https://swc.rs/) for Fast Refresh -->

# Project Learnings
- read docs for setting up environment variable 
- do not import them directly in your project instead make a separate conf file and export them in key: value pair in conf object. and destructure the required variable in your project.
- Also make a separate .env.sample file and copy all env variables in that.

- APPWRITE AUTH SERVICE 

  - Read appwrite docs for auth service(created a class and required methods inside this class, using that class object is created- basically used both js OOPs and appwrite auth service)
  - "production grade code" , created a wrapper so that our project is not bothered about which service is used whether it is appwrite or firebase or any server.
