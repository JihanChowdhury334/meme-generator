# Meme Generator

Learning project: a **React meme generator** built with **Vite**.  
Created to practice **React hooks (`useState`, `useEffect`), controlled inputs, event handling, API fetch, and dynamic UI rendering**.

## 🚀 Features
- **Fetch meme templates** from the Imgflip API using `useEffect` + async fetch  
- **Random meme selection** with a button click  
- **Dynamic text overlay** (top & bottom captions) via controlled inputs  
- **React state updates** with `useState` for image and text handling  
- **Event handling** for form inputs and button clicks  
- **Responsive design** with CSS (flex + grid)  
- **Custom styling**: text shadows, uppercase impact font, gradient backgrounds  

## 🛠️ Tech Stack
- **React 19 (RC)** — functional components & hooks (`useState`, `useEffect`)  
- **Vite** — fast dev/build setup  
- **JavaScript (ES6+)** — async/await, modular imports  
- **CSS3** — responsive styling, flexbox, grid, text effects  

## 📂 Project Structure
```
meme-generator/
├── App.jsx              # Root component (renders Header + Main)
├── components/          
│   ├── Header.jsx       # App header with logo + title
│   └── Main.jsx         # Meme form, API fetch, state logic
├── images/              
│   └── troll-face.png   # Header logo
├── index.css            # Global styles
├── index.html           # Root HTML file
├── index.jsx            # Entry point, renders <App />
├── package.json         # Dependencies & scripts
├── vite.config.js       # Vite configuration
└── README.md            # Project documentation
```

## ⚙️ How It Works
1. On mount, `useEffect` fetches meme templates from the Imgflip API and stores them in `allMemes`.  
2. Clicking **“Get a new meme image”** randomly selects a template and updates `meme.imageUrl`.  
3. Controlled inputs let users type `topText` and `bottomText`, updating state with `useState`.  
4. React re-renders the meme with overlayed text whenever state changes.  
5. CSS ensures the meme and captions remain responsive across devices.  

## 📈 Learning Purpose
This project helped me practice:  
- Using **React hooks** (`useState`, `useEffect`)  
- Fetching and handling data from an external **REST API**  
- Managing form state with **controlled inputs**  
- **Event handling** in React  
- **Dynamic rendering**: updating the DOM when state changes  
- Organizing code with **components & modular structure**  
- Styling a **responsive layout** with CSS grid, flexbox, and text effects  

---

⚠️ **Note**: This was built purely as a **learning project** and is not intended for production use.
