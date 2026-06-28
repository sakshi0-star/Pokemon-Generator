# 🎮 Pokémon Fetcher

A simple web app that fetches and displays Pokémon sprites using the [PokéAPI](https://pokeapi.co/).

## 📸 Demo

Enter any Pokémon name (e.g. `pikachu`, `charmander`, `bulbasaur`) and click **Fetch Pokémon** to see its sprite!

## 🚀 Features

- Search any Pokémon by name
- Displays the Pokémon's front sprite
- Error handling for invalid Pokémon names
- Lightweight — no frameworks, just HTML, CSS & JS

## 🛠️ Tech Stack

- HTML
- JavaScript (Async/Await)
- [PokéAPI](https://pokeapi.co/) — free, open Pokémon REST API

## 📁 Project Structure

```
├── index.html   # UI — input, button, and image
└── index.js     # Logic — fetch data from PokéAPI and display sprite
```

## ▶️ How to Run

1. Clone the repository:
   ```bash
   git clone https://github.com/your-username/pokemon-fetcher.git
   ```

2. Open `index.html` in your browser — no install needed!

   Or use **Live Server** in VS Code for a better experience.

## 💻 How It Works

1. User types a Pokémon name in the input box
2. On button click, `fetchData()` is called
3. It sends a request to `https://pokeapi.co/api/v2/pokemon/{name}`
4. The sprite URL is extracted from the response
5. The `<img>` tag is updated and made visible

## ⚠️ Error Handling

- If the Pokémon name is invalid, an error is caught and logged to the console
- The API returns a `404` for unknown Pokémon names

## 🙌 Acknowledgements

- [PokéAPI](https://pokeapi.co/) for the free Pokémon data
