# React + Vite

This template provides a minimal setup to get React working in Vite with HMR and some ESLint rules.

Currently, two official plugins are available:

- [@vitejs/plugin-react](https://github.com/vitejs/vite-plugin-react/blob/main/packages/plugin-react/README.md) uses [Babel](https://babeljs.io/) for Fast Refresh
- [@vitejs/plugin-react-swc](https://github.com/vitejs/vite-plugin-react-swc) uses [SWC](https://swc.rs/) for Fast Refresh

Problem Statement:
The user name field should only accept an email format. The validation should happen through Javascript.
The password field must be a masked field i.e. should not reveal what's being entered. 
The password field should not accept any special character other than @ and must contain an uppercase letter and a number.
Entering the password as - SmartServTest@123 should redirect the user to a dashboard page which must look like below. (file : dashboard2.png). Any other password should throw an error.

