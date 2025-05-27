# Basketball Game Simulator

A simple basketball game simulator built with Python and the Tkinter library, offering a user-friendly graphical interface to manage a game series. This program allows users to draft players, input game scores, and determine the series winner in a best-of-seven format.

## Table of Contents
- [Project Description](#project-description)
- [Features](#features)
- [Technologies Used](#technologies-used)
- [How to Run](#how-to-run)
- [Contributing](#contributing)
- [Credits](#credits)

## Project Description

This project is a basketball game simulator created as a final project for CSC-121. It provides a graphical user interface (GUI) that allows users to simulate a basketball playoff series between two teams. The program manages player drafting, records game scores, and identifies the series winner, with the first team to win four games being declared the champion.

## Features

* **Interactive GUI:** Built using the Tkinter library for a user-friendly experience.
* **Player Drafting:** Randomly assigns players from a predefined pool to the home and away teams.
* **Customizable Team Names:** Users can input custom names for the home and away teams.
* **Game Score Input:** Allows users to input points for each team after each game.
* **Series Tracking:** Automatically tracks the playoff wins and losses for each team.
* **Winner Determination:** Declares the series winner once a team achieves four wins.
* **Game Reset Functionality:** A "Reset" button allows users to reset all game variables and clear team rosters to start a new series.
* **Application Termination:** A "Terminate" button provides a clean way to close the application.
* **Object-Oriented Design:** Utilizes a `Team` class to manage team data like name, wins, losses, and points.

## Technologies Used

* **Python:** The core programming language for the simulator.
* **Tkinter:** Python's standard GUI (Graphical User Interface) library, used for building the application's interface.
* **`random` module:** Used for randomizing player selection during the drafting process.

## How to Run

1.  **Prerequisites:**
    * Ensure you have Python installed on your system (Python 3.x is recommended).
    * Tkinter is usually included with standard Python installations.

2.  **Clone the repository:**
    ```bash
    git clone [https://github.com/YourGitHubUsername/BasketballGameSimulator.git](https://github.com/YourGitHubUsername/BasketballGameSimulator.git)
    cd BasketballGameSimulator
    ```
    (Replace `YourGitHubUsername` with your actual GitHub username and `BasketballGameSimulator` with your repository name).

3.  **Run the application:**
    ```bash
    python "Basketball Game Simulator.py"
    ```

## Contributing

This project was developed as a final project for an academic course. While not actively seeking external contributions for this specific version, feedback and suggestions are welcome.

## Credits

* Sarmad Safdar
