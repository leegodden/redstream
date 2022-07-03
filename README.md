## Sanity, NextJs project

Run Sanity: sanity start:
http://localhost:3333/desk

[Setup]

1. install next
2. add sanity project (already installed globally)
3. In sanity backend add user, postedBY,comment & post schema files
4. import all the above schemas into scheam.js
5. In terminal run 'sanity start' and add first video post
6. Add dependencies in package.json and run 'npm install --legacy-peer-deps'
7. In another terminal run 'npm dev' to compile next
8. Clean up boilerplate in pages/api/index.tsx
9. remove Home.module.css and add remove globals.css and replace with tailwind stlyes
10. install tailwind: https://tailwindcss.com/docs/guides/nextjs
11. Add code to tailwind.config.js and style to <h1> in index.tsx. (install PostCSS Language Support, extension) to remove warnings
12. test in browser that tailwind styles are being applied
13. in \_app.tsx setup initial state and useEffect to test app is configured - (see comments)
14. add further code along with tailwind in \_app.tsx to import our future Navbar, Sidebar components

UP 30.22 in video
https://www.youtube.com/watch?v=CcBHZ0t2Qwc&ab_channel=JavaScriptMastery
