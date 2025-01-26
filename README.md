2. **Dataset:** 
   - You'll need a CSV file containing movie data. The file should have the following columns:
     - Movie ID
     - Title
     - Genre
     - Release Year
     - Rating
     - Number of Votes
     - Duration
     - Director
   - Replace the placeholder file path (`/content/drive/MyDrive/Python _iict/7_Movie_Recommendation_System.csv`) in the code with the actual path to your dataset file.

3. **Running the System:**
   - Execute the Python script (`movie_recommendation.py`).
   - Follow the interactive menu prompts to explore the system's features.

## Usage

- **Viewing Movies by Filters:**
   - Choose option 1 from the main menu.
   - Enter the desired genre and/or director (leave blank for all).
   - The system will display the filtered movies.

- **Adding Ratings and Reviews:**
   - Choose option 2 from the main menu.
   - Enter the movie ID, rating (1-5), and review.
   - The dataset will be updated with your input.

- **Viewing Recommendations/Top-Rated Movies:**
   - Choose option 3 from the main menu.
   - Select the type of recommendation or list you want to view.
   - The system will display the results.

- **Exiting:**
   - Choose option 4 from the main menu to exit the program.

## Future Enhancements

- **Improved Personalized Recommendations:** Implement more advanced recommendation algorithms (e.g., collaborative filtering) for more accurate and relevant suggestions.
- **Enhanced Sentiment Analysis:** Use more sophisticated sentiment analysis libraries (e.g., NLTK, TextBlob) to provide more nuanced sentiment scores.
- **User Accounts:** Add user accounts to store individual ratings and preferences for personalized recommendations.
- **GUI:** Develop a graphical user interface (GUI) for a more user-friendly experience.


## Contributing

Contributions are welcome! If you find any bugs or have suggestions for improvements, please feel free to open an issue or submit a pull request.

## License

This project is licensed under the MIT License.
