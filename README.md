# Pokédex Application

A web-based Pokédex application that displays Pokémon data fetched from the PokeAPI. Users can search and filter through Pokémon by name or type using an intuitive interface.

![Pokédex](https://img.shields.io/badge/Pokemon-API-blue)
![HTML5](https://img.shields.io/badge/HTML5-E34F26?logo=html5&logoColor=white)
![CSS3](https://img.shields.io/badge/CSS3-1572B6?logo=css3&logoColor=white)
![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?logo=javascript&logoColor=black)

## Features

- 📱 **Responsive Design** - Works seamlessly on desktop and mobile devices
- 🔍 **Real-time Search** - Filter Pokémon by name or type as you type
- 🎨 **Card-Based Layout** - Clean and organized display of Pokémon information
- ⚡ **Fast Loading** - Efficiently fetches data from PokeAPI
- 🎴 **Detailed Information** - Displays Pokémon ID, name, image, and type(s)

## What's Included

- **Pokédex Display** - View the first 150 Pokémon from Generation 1
- **Search Functionality** - Search by Pokémon name or type with instant filtering
- **Pokemon Details** - Each card shows:
  - Pokemon ID
  - Pokemon Image (official artwork)
  - Pokemon Name
  - Pokemon Type(s)

## Technologies Used

- **HTML5** - Structure and semantic markup
- **CSS3** - Styling and responsive design
- **JavaScript (Vanilla)** - DOM manipulation and API integration
- **PokeAPI** - Free Pokémon data API

## Project Structure

```
poke/
├── index.html      # Main HTML file with page structure
├── index.js        # Main JavaScript file for fetching and displaying Pokémon
├── search.js       # Search/filter functionality
├── style.css       # CSS styling
└── README.md       # Project documentation
```

## Installation

1. **Clone the repository:**
   ```bash
   git clone https://github.com/yourusername/poke.git
   cd poke
   ```

2. **Open in browser:**
   - Simply open `index.html` in your web browser
   - No build process or dependencies required
   - Works offline (after initial data load)

## Usage

1. **View Pokémon** - The page automatically loads and displays 150 Pokémon when opened
2. **Search Pokémon** - Type in the search box to filter by:
   - Pokémon name (e.g., "pikachu", "charizard")
   - Pokémon type (e.g., "fire", "water", "electric")
3. **Real-time Filtering** - Results update as you type

## API Reference

This project uses the **[PokéAPI](https://pokeapi.co/)** - a free, open-source Pokémon API.

- **Endpoint**: `https://pokeapi.co/api/v2/pokemon/{id}`
- **Data Fetched**: First 150 Pokémon (Generation 1)
- **Rate Limiting**: Fair use policy applies

## How It Works

1. **Initialization** - When the page loads, `fetchPokemon()` is called
2. **API Calls** - Makes requests for Pokémon 1-150 from PokeAPI
3. **Data Processing** - Extracts name, image, type, and ID for each Pokémon
4. **Rendering** - Displays Pokémon as interactive cards
5. **Search** - `search_pokemon()` filters cards based on search input

## Features in Detail

### Search Functionality
- Case-insensitive search
- Searches through Pokémon names and types
- Dynamically hides/shows cards as you filter

### Display Features
- Pokémon official artwork/sprite
- Pokémon ID number
- Pokémon name
- Pokémon type(s) - multiple types supported

## Browser Compatibility

- Chrome (Latest)
- Firefox (Latest)
- Safari (Latest)
- Edge (Latest)
- Mobile browsers (iOS Safari, Chrome Mobile)

## Future Enhancements

- [ ] Add more Pokémon (beyond Generation 1)
- [ ] Filter by type/generation
- [ ] Show additional details (moves, abilities, stats)
- [ ] Add sorting options (by ID, name, type)
- [ ] Add favorites/bookmarking feature
- [ ] Display evolution chains
- [ ] Add Pokémon move information

## Contributing

Contributions are welcome! Here's how you can help:

1. **Fork the repository**
2. **Create a new branch** (`git checkout -b feature/AmazingFeature`)
3. **Make your changes** and test thoroughly
4. **Commit your changes** (`git commit -m 'Add some AmazingFeature'`)
5. **Push to the branch** (`git push origin feature/AmazingFeature`)
6. **Open a Pull Request**

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## Acknowledgments

- **[PokéAPI](https://pokeapi.co/)** - For providing the free Pokémon data
- **Pokemon Company** - Original Pokémon data and artwork
- **The Open-Source Community** - For continuous inspiration and support

## Contact & Support

- **Issues & Bugs** - Please open an issue on [GitHub Issues](https://github.com/yourusername/poke/issues)
- **Feature Requests** - Suggestions welcome in [GitHub Discussions](https://github.com/yourusername/poke/discussions)
- **Questions** - Feel free to reach out or open a discussion

## Deployment

This application can be deployed to:

- **GitHub Pages** - Free hosting directly from your repository
- **Netlify** - Connect your repository for automatic deployments
- **Vercel** - Simple deployment with CI/CD
- **Any static hosting service** - No server required

### Deploy to GitHub Pages:
1. Push your code to GitHub
2. Go to repository Settings → Pages
3. Select `main` branch as source
4. Your site will be live at `https://yourusername.github.io/poke/`

---

**Happy Pokédex Hunting!** ✨🔴
