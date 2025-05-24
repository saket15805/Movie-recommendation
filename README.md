🎬 Movie Recommender System
A Movie Recommender System built using Streamlit, Pickle, and TMDb API to provide personalized movie recommendations and display movie posters.
📌 Features
- Select a movie from the dropdown menu
- Get five similar movie recommendations
- Fetch and display movie posters using the TMDb API
- Interactive Streamlit UI for seamless experience

🛠 Dependencies
- Streamlit - for web-based UI
- Pickle - to load pre-saved movie dataset
- Requests - to fetch movie posters from TMDb API
- Pandas - for data manipulation

🔗 API Configuration
This project uses TMDb API to fetch movie posters. Replace the placeholder API key in fetch_poster() function with your own TMDb API key.
Create an account at TMDb and generate an API key.
📜 How it Works
- User selects a movie from the dropdown.
- The system finds similar movies based on precomputed similarity scores.
- The corresponding movie posters are fetched using TMDb API.
- Recommended movies and posters are displayed in a grid format.
📷 Preview
Here's a preview of the application:
Movie Recommender System Screenshot

👨‍💻 Contributing
Want to improve this project? Feel free to submit a pull request or report issues.
⭐ Acknowledgments
- TMDb API for movie poster data
- Streamlit for building a simple UI
- Pandas & Pickle for data handling

