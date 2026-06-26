# tic-tac-toe-java-swing
tic-tac-toe game with java swing GUI, login, and statistics

## Student Information
Name: Maritza Putri Evita
Student ID: 5026251061
Class: A

## Project Description
This project is a simple Tic-Tac-Toe game built using Java Swing GUI. The player competes against a computer. The application includes login using a database, game statistics, personal statistics display, and Top 5 scorers feature.

## Features
- Login using username and password stored in database
- Play Tic-Tac-Toe against computer using Java Swing GUI
- Record wins, losses, draws, and total score
- Display personal statistics
- Display Top 5 scorers using JTable

## Database
Database used: PostgreSQL

## How to Run the Program
1. Create the database.
2. Import schema.sql.
3. Open the Java project.
4. Add JDBC driver.
5. Configure DatabaseManager.java.
6. Run Main.java

## Class Explanation
- Main: Entry point, starts the program and opens LoginFrame. 
- DatabaseManager: Handles JDBC database connection using DriverManage.
- Player: Model class. Stores player data: id, username, wins, losses, draws, score.
- PlayerService: Service class. Handles login query, updateStatistics, getPlayerById, and getTopFiveScorers.
- GameLogic: Handles game rules: makeMove, checkWinner, isDraw, and computerMove (random).
- LoginFrame: Swing window for username and password input with login button handler.
- MainMenuFrame: Swing window showing main menu buttons after successful login.
- GameFrame: Swing window for the 3x3 Tic-Tac-Toe board. Handles player and computer moves.
- StatisticsFrame: Swing window showing personal statistics retrieved from the database. 
- TopScorersFrame: Swing window showing Top 5 players using JTable. Data is retrieved from the database.

## Screenshots
- Login window
<img width="1026" height="639" alt="login-window" src="https://github.com/user-attachments/assets/0f235a40-3e8a-446f-a44d-f0346285a358" />

- Top scorers windows
<img width="1458" height="747" alt="top-5-window" src="https://github.com/user-attachments/assets/abf69eee-d778-4ee6-a7af-b9ef9408be30" />

- Exit Window
<img width="990" height="855" alt="exit-window" src="https://github.com/user-attachments/assets/7ef3a6b8-4356-4f33-9143-ce74692faa4e" />

- Main menu window
<img width="1005" height="864" alt="main-menu-window" src="https://github.com/user-attachments/assets/4eaf15ea-38f6-4b1f-919a-d4e936f52ce4" />

- Statistics window
<img width="897" height="807" alt="statistics-window" src="https://github.com/user-attachments/assets/02af7800-672f-4896-ab49-fc798b9e1362" />

- Game window
<img width="1152" height="1413" alt="game-window" src="https://github.com/user-attachments/assets/4e01b5dc-97a3-4225-a410-d76c269c2d00" />

## Video Link
YouTube: 
