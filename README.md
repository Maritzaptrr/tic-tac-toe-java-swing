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
<img width="1026" height="639" alt="login-window" src="https://github.com/user-attachments/assets/0f235a40-3e8a-446f-a44d-f0346285a358" />
<img width="1026" height="639" alt="login-window" src="https://github.com/user-attachments/assets/c7d15536-dca2-481e-9662-02416a265c1e" />
<img width="1026" height="639" alt="login-window" src="https://github.com/user-attachments/assets/f493a3a0-1d50-4731-ae40-26d9cc7dbe2d" />

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
Main: Entry point, starts the program and opens LoginFrame. 
DatabaseManager: Handles JDBC database connection using DriverManage.
Player: Model class. Stores player data: id, username, wins, losses, draws, score.
PlayerService: Service class. Handles login query, updateStatistics, getPlayerById, and getTopFiveScorers.
GameLogic: Handles game rules: makeMove, checkWinner, isDraw, and computerMove (random).
LoginFrame: Swing window for username and password input with login button handler.
MainMenuFrame: Swing window showing main menu buttons after successful login.
GameFrame: Swing window for the 3x3 Tic-Tac-Toe board. Handles player and computer moves.
StatisticsFrame: Swing window showing personal statistics retrieved from the database. 
TopScorersFrame: Swing window showing Top 5 players using JTable. Data is retrieved from the database.

## Screenshots

### Login Window


### Game Window


### Top 5 Scorers Window



## Links
YouTube: [URL VIDEO KAMU — isi setelah upload video]
