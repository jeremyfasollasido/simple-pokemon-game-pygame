# ⚡️ Simple Pokemon Battle Game ⚡️

A nostalgic, turn-based Pokemon battle game built with Pygame and leveraging the PokeAPI! Relive your favorite moments from the classic Red/Blue era with a straightforward yet engaging battle system.

## ✨ Features

* **Choose Your Starter Pokemon:** Select from the iconic trio: Bulbasaur, Charmander, or Squirtle.
* **Dynamic Battles:** Experience turn-based combat against a rival, complete with attack animations and HP tracking.
* **Authentic Moves:** Pokemon moves are fetched directly from the [PokeAPI](https://pokeapi.co/), ensuring accurate power and type information (specifically from the Red-Blue version for a classic feel).
* **Potion Usage:** Strategically heal your Pokemon with a limited supply of potions.
* **API Integration:** Demonstrates fetching and utilizing data from a public API to populate game elements like Pokemon stats, types, and moves.
* **Pygame Fundamentals:** A great example of using Pygame for:
    * Sprite handling and scaling
    * Event detection (keyboard and mouse)
    * Drawing shapes and text
    * Basic game state management

## 🎮 How to Play

1.  **Select Your Pokemon:** At the start, click on your desired starter Pokemon (Bulbasaur, Charmander, or Squirtle).
2.  **Battle Begins!** Your chosen Pokemon will face off against a rival Pokemon.
3.  **Player's Turn:**
    * **Fight:** Click the "Fight" button to choose an attack move.
    * **Use Potion:** Click "Use Potion" to restore some HP (you have a limited supply!).
4.  **Rival's Turn:** The rival will automatically select a random move to attack your Pokemon.
5.  **Fainting:** The battle continues until one Pokemon's HP drops to zero.
6.  **Play Again?** After a battle, you'll be prompted to play again. Press 'Y' to restart or 'N' to quit.

## 🛠️ Installation

To run this game, you'll need Python and the Pygame library.

1.  **Clone the repository:**

    ```bash
    git clone [https://github.com/YOUR_USERNAME/Simple-Pokemon-Game-Using-Pygame.git](https://github.com/YOUR_USERNAME/Simple-Pokemon-Game-Using-Pygame.git)
    cd Simple-Pokemon-Game-Using-Pygame
    ```

2.  **Install Pygame and Requests:**

    ```bash
    pip install pygame requests
    ```

    (If you have multiple Python versions, you might need `pip3 install pygame requests`)

3.  **Run the game:**

    ```bash
    python "Simple Pokemon Game Using Pygame.ipynb"
    ```

    (Or `python main.py` if you have extracted the code to a `.py` file)

## 📁 Project Structure

* `Simple Pokemon Game Using Pygame.ipynb`: The main Jupyter Notebook file containing all the game code.

## 🤝 Contributing

Feel free to fork this repository, open issues, or submit pull requests! Ideas for improvement could include:

* Adding more Pokemon
* Implementing different battle scenarios (e.g., wild encounters)
* Improving attack animations
* Adding sound effects and background music
* Implementing type effectiveness

## 📜 License

This project is open-source and available under the [MIT License](https://opensource.org/licenses/MIT).
