# Hunt the Wumpus 🧟‍♂️🎯

![WUM](https://github.com/user-attachments/assets/81ba8027-c71e-4385-905b-14d4ff301ad0)

This project is an implementation of the classic game **Hunt the Wumpus** using Python in a Jupyter Notebook.

In this game, the player explores a cave consisting of connected rooms while trying to avoid hazards such as bottomless pits, super bats, and the Wumpus itself. The goal is to hunt and kill the Wumpus before it catches you!

## Features

- Text-based adventure gameplay
- Randomized cave structure each game
- Hazards like pits and bats
- Shooting arrows to kill the Wumpus
- Replayability with random events

## Installation
1. **Clone the repository**:

    ```bash
    https://github.com/SoubhLance/AI-Wumpus-Solver.git
    cd wumpus
    ```

2. **Install required dependencies** (if any):

    > *Note*: If no external libraries are used other than standard Python ones, you can skip this step.

    ```bash
    pip install pygame
    ```

3. **Launch Jupyter Notebook**:

    ```bash
    jupyter notebook
    ```

4. Open `wumpus.ipynb` and run the cells to start playing!

## How to Play

- You start in a random cave room.
- Each room may have connections to 1-3 other rooms.
- You receive clues about nearby hazards (bats, pits, Wumpus).
- You can:
  - **Move** to an adjacent room
  - **Shoot** an arrow into a room to try and kill the Wumpus
- If you fall into a pit or encounter the Wumpus without killing it, the game ends.


## Future Improvements

- Add a graphical interface using `tkinter` or `pygame`
- Implement difficulty settings
- Save/load game states
- Add more random events or hazards

## License

This project is licensed under the [MIT License](LICENSE).

---

Feel free to fork the project, suggest improvements, or open issues if you encounter any bugs!

---

> Created with ❤️ and ⚡️
