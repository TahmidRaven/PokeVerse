# PokéVerse 🐾

**Discover your favorite Pokémon and their powers!**  

PokéVerse is an interactive Pokémon web application that lets users search, compare, and explore Pokémon with a visually appealing interface, complete with dark/light mode support, animations, and Pokémon stats visualization.

## Live Demo
Check out the live project hosted on GitHub Pages:  **[PokéVerse Live](https://tahmidraven.github.io/PokeVerse/)**  
---
<img width="1847" height="986" alt="Screenshot 2025-11-08 041406" src="https://github.com/user-attachments/assets/011774a1-1142-4d12-aa52-3f5926fb086c" />
<img width="1846" height="996" alt="Screenshot 2025-11-08 041352" src="https://github.com/user-attachments/assets/b4de2830-6f55-47ec-b702-ae39be630461" />

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

## Example usage in JavaScript
```javascript
const query = "pikachu"; // Replace with any Pokémon name or ID
const res = await fetch(`https://pokeapi.co/api/v2/pokemon/${query}`);
if (!res.ok) {
  throw new Error("Pokémon not found");
}
const data = await res.json();
console.log(data);

// Example: Extract types and stats
const types = data.types.map(t => t.type.name);
const stats = data.stats.map(s => ({ name: s.stat.name, value: s.base_stat }));

console.log("Types:", types);
console.log("Stats:", stats);
```

## Repository
GitHub Repository:  
📁 **[PokéVerse on GitHub](https://github.com/TahmidRaven/PokeVerse)**  

## Website / Portfolio
Visit my personal website:  
🌐 **[Raven Death Portfolio](https://ravendeath.github.io/)**  

## Screenshots
![PokéVerse Screenshot](screenshot.png)  

## Author
**Raven Death**  
GitHub: [https://github.com/TahmidRaven](https://github.com/TahmidRaven)  
Portfolio: [https://ravendeath.github.io/](https://ravendeath.github.io/)
