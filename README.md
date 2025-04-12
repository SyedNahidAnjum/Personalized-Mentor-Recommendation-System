# Personalized-Mentor-Recommendation-System
This project implements a Personalized Mentor Recommendation System using a basic content-based filtering approach. The system suggests the most suitable mentors for aspirants based on their preferences, including subjects, target college, preparation level, and learning style.

Features:

Mentor Profile Matching- Matches aspirants with mentors who best match their preferred subjects, target college, prep level, and learning style.

Cosine Similarity- Utilizes cosine similarity to compute the similarity score between an aspirant’s profile and mentors' profiles.

Top Mentor Recommendation- Recommends the top 3 mentors based on the similarity scores.

Scalable- The system can be extended with more features, such as user feedback, NLP-based profiling, and more.

Technologies Used:

Pandas- For handling data and creating DataFrames.

Scikit learn- For feature extraction (using CountVectorizer) and calculating cosine similarity.

Python- Core programming language used in the implementation.

How the System Works:

Step 1- Import required libraries.

Step 2- Create a mock dataset containing mentor information.

Step 3- Create a sample aspirant profile.

Step 4- Combine relevant features (subject, target college, prep level, and learning style) from both mentors and the aspirant.

Step 5- Use CountVectorizer to convert the combined features into a vector format.

Step 6- Calculate cosine similarity between the aspirant’s profile and all the mentor profiles.

Step 7- Rank mentors based on similarity scores and recommend the top 3 mentors.

How to Use:

Open the Jupyter notebook or Python script and run the cells to see the system in action.

To see the recommendations for a new aspirant, modify the aspirant_profile dictionary with the new aspirant's details and re-run the notebook.

Possible Improvements:

User Feedback- Add a user_rating column to track feedback for mentor sessions, and recalculate the final recommendation score using weighted averages of content similarity and feedback.

NLP Profiling- Gradually introduce NLP-based profiling, such as leveraging pretrained models or GPT-based profiling, to enhance recommendation accuracy.

Scalability- Collect more data over time, such as success rates, session feedback, or mentor-mentee interactions, to further improve the recommendations.

Contributing:

Contributions to this project are welcome! If you have ideas for new features or improvements, feel free to fork the repository and submit a pull request.

📬 Author

Made with 💡 by Syed Nahid Anjum
