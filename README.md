# 🎮 Pokemon Card App

A beautiful and interactive **Pokemon card application** built with **React** that fetches data from the **PokeAPI** and displays Pokemon information in an elegant card layout.

---
# SCREENSHOTS
<img width="1916" height="1028" alt="image" src="https://github.com/user-attachments/assets/82d5d626-8346-4db2-afa8-3011c0d6ebaf" />
<img width="1903" height="1025" alt="image" src="https://github.com/user-attachments/assets/27a301e9-9f74-4c70-8352-c8e4398109b2" />

# 📝 Short Description

Interactive Pokemon card app built with React.
Features **search functionality, detailed stats display, and smooth animations**.

Developed to learn and practice **React hooks (`useState`, `useEffect`)** while fetching data from an external API.

Responsive design with a clean and modern **UI/UX**.

🔗 **Live Demo:**
[https://pokemonwebsiteusingreact.netlify.app/](https://pokemonwebsiteusingreact.netlify.app/)

---

# 📸 Features

### 🟢 Pokemon Grid Display

Browse Pokemon in a responsive **card grid layout**.

### 🔎 Search Functionality

Search for your favorite Pokemon by name.

### 📊 Detailed Stats

View detailed Pokemon information including:

* Height & Weight
* Speed & Attack Stats
* Base Experience
* Abilities
* Types with color-coded badges

### ✨ Smooth Animations

* Hover effects
* Card transitions
* Interactive UI

### 📱 Responsive Design

Works smoothly on:

* Desktop
* Tablet
* Mobile devices

---

# 🚀 Technologies Used

* **React** – JavaScript library for building user interfaces
* **PokeAPI** – RESTful Pokemon API for fetching data
* **CSS3** – Modern styling and animations
* **Urbanist Font** – Clean and modern typography

---

# 📚 What I Learned

This project helped me understand important **React fundamentals**.

## useState Hook

* Managing Pokemon data
* Handling search input
* Controlling loading and error states
* Filtering Pokemon based on user input

## useEffect Hook

* Fetching data from APIs
* Running code when components load
* Understanding dependency arrays
* Handling side effects
* Cleanup techniques

---

# 🛠️ Installation & Setup

### 1️⃣ Clone the Repository

```bash
git clone https://github.com/yourusername/pokemon-card-app.git
cd pokemon-card-app
```

### 2️⃣ Install Dependencies

```bash
npm install
```

### 3️⃣ Start Development Server

```bash
npm start
```

### 4️⃣ Open in Browser

```
http://localhost:3000
```

---

# 📁 Project Structure

```
pokemon-card-app/
│
├── src/
│   ├── components/
│   │   └── Card.jsx        # Pokemon Card Component
│   │
│   ├── App.jsx             # Main Application
│   ├── styles.css          # Global Styles
│   └── index.js            # Entry Point
│
├── public/
├── package.json
└── README.md
```

---

# 💡 Key Concepts Demonstrated

## State Management

```javascript
const [pokemon, setPokemon] = useState([]);
const [search, setSearch] = useState("");
const [loading, setLoading] = useState(true);
```

---

## API Integration

```javascript
useEffect(() => {
  const fetchPokemon = async () => {
    const response = await fetch("https://pokeapi.co/api/v2/pokemon");
    const data = await response.json();
    setPokemon(data.results);
  };

  fetchPokemon();
}, []);
```

---

## Search Filtering

```javascript
const filteredPokemon = pokemon.filter(p =>
  p.name.toLowerCase().includes(search.toLowerCase())
);
```

---

# 🎨 Design Features

* **Blob Effect Background** – Morphing shapes on hover
* **Responsive Grid Layout** – Auto-fit layout system
* **Type Badges** – Color-coded Pokemon types
* **Smooth Transitions** – 0.3s animations
* **Card Elevation** – Shadows for depth

---

# 🔮 Future Enhancements

* Pokemon detail modal on card click
* Type filtering
* Generation filters
* Evolution chain display
* Favorite / Bookmark system
* Pagination for performance
* Loading skeletons
* Dark mode toggle 🌙

---

# 🤝 Contributing

Contributions are welcome!

1. Fork the repository
2. Create a feature branch

```bash
git checkout -b feature/AmazingFeature
```

3. Commit your changes

```bash
git commit -m "Add AmazingFeature"
```

4. Push to the branch

```bash
git push origin feature/AmazingFeature
```

5. Open a Pull Request

---

# 📝 License

This project is licensed under the **MIT License**.

---

# 🙏 Acknowledgments

* **PokeAPI** for the free Pokemon API
* **Pokemon Company** for creating the Pokemon universe
* **React Community** for amazing documentation

---

# 📧 Contact

**Muhammad Hassan**

GitHub Project:
[https://github.com/TechHassan06/PokemonWebsiteUsingReactHooks](https://github.com/TechHassan06/PokemonWebsiteUsingReactHooks)

⭐ If you found this project useful, consider giving it a **star**!

---

Made with ❤️ using **React**

---

Made with ❤️ and React
