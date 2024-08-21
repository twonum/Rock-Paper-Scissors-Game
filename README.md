### 🎮 Rock-Paper-Scissors Game with Leaderboard

#### Overview

This project is a **Rock-Paper-Scissors** game built using Python's **Tkinter** library for the GUI, **SQLite** for local data storage, and **SQL Server** for maintaining a leaderboard. The game offers an interactive user interface, where users can log in, play the classic Rock-Paper-Scissors game, and view a leaderboard to track wins and losses.

#### Key Features

- **User Authentication:** 
  - Users can sign up or log in to start playing.
  - User information is stored securely using SQLite.
  
- **Rock-Paper-Scissors Gameplay:**
  - Intuitive GUI for playing Rock-Paper-Scissors with the computer.
  - Real-time score tracking for the user and the computer.
  - The game ends after a predefined number of turns, announcing the winner, loser, or if it's a tie.

- **Leaderboard:** 
  - The leaderboard displays top players based on their win-loss records.
  - Data is stored and retrieved using SQL Server, ensuring persistence and reliability.

- **Custom Graphics:**
  - Custom images for rock, paper, scissors, and the results (win, lose, tie) enhance the user experience.
  - A playful confetti animation is displayed for the winning message.

#### Tech Stack

- **Programming Language:** Python
- **GUI Framework:** Tkinter
- **Database:** 
  - SQLite for local user authentication.
  - SQL Server for storing and managing leaderboard data.
- **Additional Libraries:**
  - `PIL (Pillow)` for image processing.
  - `pyodbc` for connecting to SQL Server.

#### How to Run the Project

1. **Clone the repository:**

   ```bash
   git clone https://github.com/yourusername/rock-paper-scissors-game.git
   cd rock-paper-scissors-game
   ```

2. **Install dependencies:**

   Make sure you have the necessary Python libraries installed:

   ```bash
   pip install pillow pyodbc
   ```

3. **Configure SQL Server:**

   - Update the `server` and `database` variables in the code with your SQL Server instance details.
   - Ensure that the SQL Server is running and accessible.

4. **Run the application:**

   ```bash
   python rock_paper_scissors.py
   ```

5. **Enjoy the game!**

#### Project Structure

- **rock_paper_scissors.py**: Main game logic, including user authentication, gameplay, and leaderboard functions.
- **Images/**: Directory containing all the images used for the game (rock, paper, scissors, results, etc.).

#### Future Enhancements

- **Multiplayer Support:** Allow multiple players to compete against each other in real-time.
- **Improved UI/UX:** Enhance the user interface with more animations and smoother transitions.
- **More Customization:** Allow users to select their avatars or themes for the game.

#### Contributing

Feel free to fork the repository and submit pull requests. Any contributions to enhance the gameplay, improve the UI, or optimize the code are welcome!

#### License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

---

Hope you enjoy the game! Let me know if you have any suggestions or encounter any issues. Happy gaming! 🎉

--- 

**GitHub Repository:** [Rock-Paper-Scissors Game](https://github.com/twonum/rock-paper-scissors-game)

--- 

