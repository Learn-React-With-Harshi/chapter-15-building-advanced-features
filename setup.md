# `Learn React With Harshi` Series 
   Documenting my learning journey of [Namaste React Live Course](https://learn.namastedev.com/) conducted by Akshay Saini
   
## Steps to be followed while coding : 

Note : Before start to code, get the requirements clarified with the interviewer and create a low-level design of the app in mind.

1. Create React App - Executing a package CRA to start a new react app with name namaste-youtube 
```
$ npx create-react-app youtube-clone
```

2. Add a remote to local repository 
```
$ git remote add origin https://github.com/{username}/{repo-name}.git
```
In our case, 

```
$ git remote add origin https://github.com/Learn-React-With-Harshi/youtube-clone.git
```

3. Install Tailwind CSS

```
npm install -D tailwindcss
npx tailwindcss init
```

4. Configure tailwind.config.js 

```
module.exports = {
  content: ["./src/**/*.{html,js}"],
  theme: {
    extend: {},
  },
  plugins: [],
}
```

5. Add the Tailwind directives to your CSS
@tailwind base;
@tailwind components;
@tailwind utilities;

6. Install react-icons
```
$ npm install react-icons --save
```

7. Install Reaact-Router-DOM
```
npm install react-router-dom
```

8. Create Components 
 - Create components in the hierarchy that we imagined during low level design 
 - Tip : Use emmet `rafce` to create a functional component code 
 - Import them into required components
 - Create router and provider 

9. Install Redux
```
npm install @reduxjs/toolkit
npm install react-redux
```

- Create store - configureStore with reducer 
- craete slice with name, initialState & reducers with action functions toogleMenu
- Provider 
- dispatch action toggleMenu in Header 

useSelector -> only subscribe to portion of the store  -> in Sidebar 

10. Create config.js file and place all the external API URL there.





