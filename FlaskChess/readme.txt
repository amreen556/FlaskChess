This is a simple chess engine/interface created using flask.
It uses chessboard.js and chess.js for the logic of the frontend chessboard, and python chess for the
logic of the backend chessboard. All calculation is done on the backend using python.

In order to run this application on your own machine, please install flask and python chess.

Install flask by running:
    pip install flask

Install python chess by running:
    pip install python-chess[uci,gaviota]

Project Structure
app/: Contains the main Flask application and its modules.
static/: Static files (CSS, JS, images).
templates/: HTML templates for rendering web pages.
routes.py: Defines the routes/endpoints of the application.
models.py: Database models for users, games, etc.
game_logic.py: Contains the chess game rules and move validation logic.
migrations/: Database migration files.
config.py: Configuration settings for the Flask application.
requirements.txt: List of dependencies needed to run the project.

##Usage
Start a Game: Register or log in to start a new game.
Make Moves: Click on a piece and then click on the destination square to make a move.
Game History: View past games from your profile.

##Contributing
Contributions are welcome! To contribute:

##Fork the repository.
Create a new branch: git checkout -b feature-branch.
Commit your changes: git commit -m 'Add new feature'.
Push to the branch: git push origin feature-branch.
Open a pull request.
