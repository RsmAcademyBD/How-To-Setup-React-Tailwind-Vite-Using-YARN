# Setup React & Tailwind & Vite Using YARN
Presenting brand new Article:  In this article you will learn how to Set Up Tailwind Css With create-react-app and yarn. Just follow the steps in the Article. More article about Android Application And Web Development will uploaded so get in touch with the channel. So you are no more far. You can be  developer. 

![image](https://github.com/user-attachments/assets/3da6d9b2-c133-4cee-ab9c-7b784c777035)

## 1. Create a new react project with yarn
```bash
yarn create vite my-project

And follow next commands ....
Select - React
-----------and press enter---------

Select - JavaScript + SWC
-----------and press enter---------

cd my-project
```
## 2. Install Tailwind CSS with postcss & autoprefixer
```bash
yarn add -D tailwindcss postcss autoprefixer
```
## 3. Generate tailwind.config.js and postcss.config.js
```bash
yarn tailwindcss init -p
```
## 4. Configure your template paths

- Add the paths to all of your template files in your tailwind.config.js file.
```jsx
/** @type {import('tailwindcss').Config} */
module.exports = {
  content: ["./index.html", "./src/**/*.{js,ts,jsx,tsx}"],
  theme: {
    extend: {},
  },
  plugins: [],
};
```
## 5. Add the Tailwind directives to your CSS

- Add the @tailwind directives for each of Tailwind’s layers to your ./src/index.css file.

```jsx
@tailwind base;
@tailwind components;
@tailwind utilities;
```

## 6. Start your build process

- Run your build process with npm run start.

```jsx
yarn dev
```
