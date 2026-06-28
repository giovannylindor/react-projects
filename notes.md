# React Notes

- React is a Front-End Library
    - A collection a pre-written code designed to make development easier

* With React:
    - Components are reusable
    - It's Well-supported
    - There's a Smaller learning curve

--- 

## Setting up React Environment

You can start React from `<script>` tags or toolchains and frameworks such as:
- Vite
- Gatsby
- NextJS
- Create React App (Depreciated)

* It's very difficult to start React w/o a Toolchain as the following would need to be configured:
    - Package Management
    - Module Bundling 
    - Compilation
    - React 

- Vite will be used in the terminal to start a react project 

**Creating a React App**

- Use the latest version of Node.js
- Enter the following command in the terminal:
`npm create vite@latest react-project-name -- --template react`
- The terminal will provide a `localhost` server to your React app

**What is `localhost`?**
- `localhost` is a hostname that refers to your own computer
- Data is sent and looped directly back to your local machine
- Your computer is essentially talking to itself

To exit out of you dev server hit `Ctrl + C`
To start your dev server type `npm run dev` in the terminal 