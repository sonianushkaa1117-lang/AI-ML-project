# Movie Recommendation System using Neural Networks

This project is a simple movie recommendation system built using a neural network. It takes basic movie features like genre, rating, votes, and year, and uses them to learn patterns and suggest movies accordingly.

The focus of this project is not just recommendation, but understanding how a model learns from data over time.

---

## What this project does

A small dataset of movies is created manually, containing information like title, genre, rating, number of votes, and release year. This data is then prepared and fed into a neural network.

The model is trained over 40 epochs. During training, it tries to reduce error and improve predictions. Once trained, it can suggest movies from a chosen genre based on learned patterns.

---

## How it works

The genre values are converted into numerical form so the model can understand them. Other features like rating, votes, and year are scaled to keep everything balanced.

A neural network is built using TensorFlow and trained using the Adam optimizer. The model learns to predict normalized ratings based on the given inputs.

After training, graphs are plotted to show how the model improved over time. Both loss and error are tracked so it’s easy to see how well the model is learning.

---

## Recommendation logic

When a user enters a genre, the system filters movies from that category and runs them through the trained model. Each movie gets a score, and the top results are displayed as recommendations.

The system also handles incorrect inputs by showing available genres.

---

## Technologies used

Python is used for the entire implementation.  
Pandas and NumPy are used for handling and processing data.  
Matplotlib is used to visualize training performance.  
TensorFlow and Keras are used to build and train the neural network.

---

## Running the project

You can run this project directly in Google Colab or any Python environment.

Once you run the code:
- the model starts training
- training graphs are displayed
- you are prompted to enter a genre
- the system returns recommended movies

---

## Output

The model trains over 40 epochs and gradually reduces loss.  
Graphs are generated to show training and validation performance.  
Finally, a list of recommended movies is printed based on the selected genre.

---

## Final note

This is a simple project meant to understand the basics of machine learning and recommendation systems. It keeps things straightforward while still showing how real models are built and used.
