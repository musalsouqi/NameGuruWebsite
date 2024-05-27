# Sewer Text Adventure Game

Welcome to the Sewer Text Adventure Game! This is a simple text-based adventure game where you navigate through different rooms in a sewer, collecting items to face the final challenge: defeating the Rat King. You need to collect all the items scattered throughout the sewer before encountering the Rat King to win the game.

## How to Play

- **Objective**: Collect 6 items before you face off with the Rat King.
- **Commands**:
  - **Move**: `go [direction]` (e.g., `go north`, `go east`)
  - **Pick up an item**: `get [item name]` (e.g., `get map`, `get flashlight`)

## Rooms and Items

- **Water Treatment Plant**: Starting room, no items.
- **Sewer Control Room**: Contains a map. Connects to Maintenance Closet (north), Septic Tank (east), Water Treatment Plant (west), and Pump Room (south).
- **Storage Chamber**: Contains a hazmat suit. Connects to Maintenance Closet (east).
- **Maintenance Closet**: Contains a flashlight. Connects to Storage Chamber (west) and Sewer Control Room (south).
- **Pump Room**: Contains a stick. Connects to Sewer Control Room (north) and Ventilation Shaft (east).
- **Ventilation Shaft**: Contains a mask. Connects to Pump Room (west).
- **Septic Tank**: Contains cheese. Connects to Rat King's Hideout (north) and Sewer Control Room (west).
- **Rat King's Hideout**: Final room, where you face the Rat King.

## Game Logic

- **Starting Room**: Water Treatment Plant
- **Inventory**: Starts empty
- **Victory Condition**: Collect all 6 items and reach the Rat King's Hideout.
- **Defeat Condition**: Reach the Rat King's Hideout without collecting all 6 items.

## Instructions

1. Clone the repository:
    ```bash
    git clone https://github.com/musalsouqi/NameGuruWebsite
    ```

2. Open the `index.html` file in your browser to start the game.

3. Use the input field to enter your commands and navigate through the game.

## Example Commands

- Move to another room:
  ``` 
  go east
  ```
- Pick up an item:
  ```
  get map
  ```

## Development

Feel free to contribute to the development of this game by forking the repository and creating pull requests. Here are some areas that could be improved or expanded:
- Adding more rooms and items.
- Implementing additional game mechanics.
- Enhancing the user interface.

## License

This project is licensed under the MIT License. See the LICENSE file for more details.

## Contact

For any questions or suggestions, feel free to open an issue or contact me directly at [musalsouqi](https://github.com/musalsouqi).

---

Enjoy playing the Sewer Text Adventure Game!
```

