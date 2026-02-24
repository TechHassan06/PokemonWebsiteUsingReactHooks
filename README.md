**🎮 Pokemon Card App**
A beautiful and interactive Pokemon card application built with React that fetches data from the PokeAPI and displays Pokemon information in an elegant card layout.

***📝 Short Description***
Interactive Pokemon card app built with React. Features search functionality, detailed stats display, and smooth animations. Developed to learn and practice useState and useEffect hooks while fetching data from PokeAPI. Responsive design with beautiful UI/UX.
<img width="1916" height="1028" alt="image" src="https://github.com/user-attachments/assets/82d5d626-8346-4db2-afa8-3011c0d6ebaf" />
<img width="1903" height="1025" alt="image" src="https://github.com/user-attachments/assets/27a301e9-9f74-4c70-8352-c8e4398109b2" />

**LiveLink**
https://pokemonwebsiteusingreact.netlify.app/

***📸 Features***

Pokemon Grid Display - Browse through Pokemon in a responsive card grid layout
Search Functionality - Search for your favorite Pokemon by name
Detailed Stats - View comprehensive Pokemon information including:

Height & Weight
Speed & Attack stats
Base Experience
Abilities
Types with color-coded badges


Smooth Animations - Hover effects and card transitions for better UX
Responsive Design - Works seamlessly on desktop and mobile devices

***🚀 Technologies Used***

React - JavaScript library for building user interfaces
PokeAPI - RESTful Pokemon API for data fetching
CSS3 - Modern styling with custom properties and animations
Urbanist Font - Clean and modern typography

***📚 What I Learned***

This project helped me master essential React hooks:
useState Hook

Managing component state for Pokemon data
Handling search input state
Controlling loading and error states
Filtering Pokemon based on user input

useEffect Hook

Fetching data from external APIs on component mount
Understanding dependency arrays
Handling side effects in functional components
Cleanup and optimization techniques

***🛠️ Installation & Setup***

Clone the repository

bashgit clone https://github.com/yourusername/pokemon-card-app.git
cd pokemon-card-app

Install dependencies

bashnpm install

Start the development server

bashnpm start

Open your browser
Navigate to http://localhost:3000

***📁 Project Structure***
pokemon-card-app/
├── src/
│   ├── components/
│   │   └── Card.jsx          # Pokemon card component
│   ├── App.jsx                # Main application component
│   ├── styles.css             # Global styles
│   └── index.js               # Entry point
├── public/
├── package.json
└── README.md

***💡 Key Concepts Demonstrated***
State Management
javascriptconst [pokemon, setPokemon] = useState([]);
const [search, setSearch] = useState("");
const [loading, setLoading] = useState(true);
API Integration
javascriptuseEffect(() => {
  const fetchPokemon = async () => {
    // Fetch Pokemon data from PokeAPI
    const response = await fetch('https://pokeapi.co/api/v2/pokemon');
    const data = await response.json();
    setPokemon(data.results);
  };
  
  fetchPokemon();
}, []);
Search Filtering
javascriptconst filteredPokemon = pokemon.filter(p => 
  p.name.toLowerCase().includes(search.toLowerCase())
);
***🎨 Design Features***

Blob Effect Background - Organic, morphing shapes on card hover
Grid Layout - Responsive auto-fit grid system
Type Badges - Color-coded Pokemon type indicators
Smooth Transitions - 0.3s transform and shadow transitions
Card Elevation - Box shadows for depth and hierarchy

***🔮 Future Enhancements***

 Add Pokemon detail modal on card click
 Implement type filtering
 Add generation filters
 Include evolution chains
 Add favorite/bookmark functionality
 Implement pagination for better performance
 Add loading skeletons
 Dark mode toggle

***🤝 Contributing***
Contributions are welcome! Feel free to open an issue or submit a pull request.

Fork the project
Create your feature branch (git checkout -b feature/AmazingFeature)
Commit your changes (git commit -m 'Add some AmazingFeature')
Push to the branch (git push origin feature/AmazingFeature)
Open a Pull Request

***📝 License***
This project is open source and available under the MIT License.
***🙏 Acknowledgments***

PokeAPI - The amazing RESTful Pokemon API
Pokemon Company - For creating the Pokemon universe
React community for excellent documentation and resources

***📧 Contact***
Muhammad Hassan
Project Link: https://github.com/TechHassan06/PokemonWebsiteUsingReactHooks
⭐ If you found this project helpful, please give it a star!
Made with ❤️ and React
