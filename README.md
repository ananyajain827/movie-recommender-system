# movie-recommender-system💻
This is a movie recommender system built using Python and Streamlit. The system recommends movies to users based on their preferences using a dataset of movies and their similarities.
![Screenshot 2025-01-17 061843](https://github.com/user-attachments/assets/08eb5660-1b9d-4f64-8670-fffa990a9d8c)
![Screenshot 2025-01-17 061857](https://github.com/user-attachments/assets/388b3f32-9952-432a-bd59-6662ed3d1a9e)
![image](https://github.com/user-attachments/assetsyy/7f228197-82da-4c77-b07b-51a3a5d72283)

# Table of Contents📜

Project Overview

Technologies Used

Installation

How to Run

Usage

Contributing

License


# Project Overview📜
The Movie Recommender System is designed to recommend movies to users based on a selected movie. Using pandas, numpy, and pickle for data handling and machine learning, the system finds the most similar movies based on a given movie title. It uses a cosine similarity model to calculate similarity scores between movies.
This project is built as a web app using Streamlit, allowing users to interact with the recommender system by selecting a movie and getting movie recommendations in return.

# Technologies Used🔧
Python: Programming language used for building the recommender system.
pandas: Data manipulation and analysis.
numpy: Mathematical operations for data manipulation.
pickle: Serializing and deserializing data (for saving model data).
Streamlit: For creating the interactive web application.
Git Large File Storage (LFS): For storing large files like the model and similarity matrices.


# Installation🛠️
Follow these steps to set up the project on your local machine:
1. Clone the Repository
git clone https://github.com/ananyajain827/movie-recommender-system.git

2. Install Dependencies 📦
Create a virtual environment :
python -m venv venv
Activate the virtual environment:
For Windows:
.\venv\Scripts\activate
For macOS/Linux:
source venv/bin/activate

Install the required Python libraries:
pip install -r requirements.txt
If the requirements.txt file is not present, you can manually install the necessary libraries:
pip install pandas numpy streamlit pickle-mixin


# How to Run🏃‍♀️
Start Streamlit App:
Once you've installed all dependencies and are in your virtual environment, you can start the Streamlit web application:
streamlit run app.py

Access the Application:
After running the above command, Streamlit will provide a local server URL (usually (http://localhost:8501)) where you can view and interact with the Movie Recommender System.


# Usage👨‍💻/👩‍💻
Select a Movie: From the dropdown, choose a movie you would like recommendations for.
Get Recommendations: Click the "Recommend" button to display a list of similar movies.
View Results: The recommended movies will be displayed below the button.


# Contributing🤝
Contributions are welcome! If you'd like to contribute to this project, please follow these steps:
Fork the repository.
Create a new branch for your feature or bugfix.
Commit your changes and push them to your fork.
Open a pull request to merge your changes into the main repository.


# License
This project is licensed under the MIT License - see the LICENSE file for details.

________________________________________________________________________________________________________________________________________________________________






