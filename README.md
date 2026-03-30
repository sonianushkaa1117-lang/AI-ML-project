# AI-ML-project
Book Recommendation System
 Overview

This project is a simple Book Recommendation System built using Python and Pandas. It recommends books to users based on their preferred genre and minimum rating.

The system filters and displays the top-rated books from a predefined dataset, making it easier for users to discover relevant books.

Features
Recommends books based on genre
Filters books by minimum rating
Case-insensitive genre matching
Displays top 5 recommendations
Simple and fast command-line interface
Technologies Used
Python
Pandas
Dataset

The dataset is manually created and includes:

Book Name
Genre
Rating

Example:

Book	Genre	Rating
The Alchemist	Fiction	4.7
Harry Potter	Fantasy	4.9
Atomic Habits	Self-help	4.6
⚙️ How It Works
The dataset is stored in a Pandas DataFrame
Genres are converted to lowercase for consistency
User inputs a genre
The system:
Filters books by genre
Applies minimum rating filter
Sorts books by rating
Displays top 5 results
-How to Run the Project
Step 1: Install Pandas
pip install pandas
Step 2: Run the Script
python your_file_name.py
Step 3: Enter Genre

Example:

Enter genre: Fantasy
-Available Genres
Fiction
Fantasy
Self-help
Finance
Horror
Sci-Fi
Romance
Thriller
History
Biography
-Example Output
Top Recommendations:

Harry Potter (4.9)
The Hobbit (4.8)
-Limitations
Small dataset
No user personalization
Command-line based (no GUI)
-Future Improvements
Add larger dataset
Use machine learning for better recommendations
Build a web app interface
Add filters like author, year, popularity
-Learning Outcomes
Understanding Pandas DataFrame
Data filtering and sorting
Basic recommendation system logic
Handling user input in Python
-Author

Anushka Soni
