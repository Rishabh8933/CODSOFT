# CODSOFT

TASK 1
I define a dictionary `pairs` where the keys are regular expressions representing different user queries, and the values are the corresponding responses. I then define a function `chat` that takes the user input as an argument and checks if it matches any of the patterns. If a match is found, the corresponding response is returned. 

TASK 2
The `minimax` function implements the Minimax algorithm to determine the best move for the AI. The `make_ai_move` function uses the `minimax` function to make the AI's move. The `make_player_move` function allows the player to make a move by inputting the row and column. The `play_game` function is the main game loop that handles the game logic, including checking for wins or ties and printing the board.

TASK 4
I start by loading the TMDB 5000 dataset using `pd.read_csv()` function from the pandas library. I then select the relevant features (such as title, overview, keywords, and genres) and fill any missing values with an empty string. Next, I combine the selected features into a single string using the `combine_features()` function and then use the `CountVectorizer()` from scikit-learn to create a count matrix, and then compute the cosine similarity matrix using `cosine_similarity()`. Finally, I define the `get_recommendations()` function to retrieve the most similar movies based on a given movie title. The AI sorts the movies based on their similarity scores and returns the top 10 recommendations.
