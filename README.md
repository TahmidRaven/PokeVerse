# PokéVerse 🐾

**Discover your favorite Pokémon and their powers!**  

PokéVerse is an interactive Pokémon web application that lets users search, compare, and explore Pokémon with a visually appealing interface, complete with dark/light mode support, animations, and Pokémon stats visualization.

---

## About the Project
PokéVerse allows users to:
- Search for any Pokémon by name.
- Randomly explore Pokémon.
- Compare two Pokémon to see which one would likely win based on stats.
- View detailed stats, types, and official artwork.
- Enjoy dark/light theme toggling for better user experience.
- Interact with Pokémon cards, including shiny sprite previews on hover.

The app is styled with a glassmorphism effect and animations to enhance the user interface.

---

## Technologies & Tools Used
- **Languages:** HTML, CSS, JavaScript
- **Frameworks & Libraries:** Tailwind CSS
- **Design Patterns:** Glassmorphism, Dark/Light Theme Toggle
- **Animations:** Custom CSS keyframes (`spin`, `pulse`), hover effects
- **Audio:** Pokémon opening sound effects
- **Version Control:** Git/GitHub

---

## Features
1. **Pokémon Search:** Search Pokémon by name and view detailed stats.
2. **Random Pokémon Generator:** Discover 20 random Pokémon at a click.
3. **Pokémon Comparison:** Compare two Pokémon stats side-by-side to find the winner.
4. **Interactive Cards:** Hover effects to show shiny sprites.
5. **Dark/Light Mode:** Toggle themes for comfortable viewing.
6. **Responsive Design:** Works on mobile, tablet, and desktop.
7. **Audio Effects:** Play Pokémon sound on modal open.

---

## APIs Used
- **[PokéAPI](https://pokeapi.co/)**: Fetches Pokémon data, including stats, types, and artwork.  

Example usage in JavaScript:
```javascript
const res = await fetch(`https://pokeapi.co/api/v2/pokemon/${query}`);
const data = await res.json();
