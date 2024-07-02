# Movie Recommendation System

Welcome to the Movie Recommendation System project! This repository contains code to build a movie recommendation system using machine learning techniques. The project leverages Python 3.7 and is built with libraries such as NumPy, pandas, scikit-learn, nltk, and streamlit.

## Table of Contents
- [Installation](#installation)
- [Usage](#usage)
- [Dataset](#dataset)
- [Concepts](#concepts)
- [Images](#images)
- [License](#license)
- [Acknowledgment](#acknowledgment)

## Installation

To get started, you need to set up a Python 3.7 environment and install the required libraries. Follow these steps:

1. **Clone the repository:**
    ```bash
    git clone https://github.com/zeeza18/Movie-Recommendation-System.git
    cd Movie-Recommendation-System
    ```

2. **Create a virtual environment:**
    ```bash
    python3.7 -m venv env
    ```

3. **Activate the virtual environment:**
    - On Windows:
        ```bash
        .\env\Scripts\activate
        ```
    - On macOS and Linux:
        ```bash
        source env/bin/activate
        ```

4. **Install the required libraries:**
    ```bash
    pip install -r requirements.txt
    ```

## Usage

Once the environment is set up and libraries are installed, you can run the application using Streamlit:

```bash
streamlit run app.py
 ```

## Dataset
The dataset used for this project is the TMDB movie metadata. You can download it from the following link:

[TMDB Movie Metadata](https://www.kaggle.com/tmdb/tmdb-movie-metadata?select=tmdb_5000_movies.csv)

## Concepts
### Cosine Similarity
Cosine similarity is a measure of similarity between two non-zero vectors of an inner product space. It is defined as the cosine of the angle between the vectors. In the context of a recommendation system, it helps in measuring how similar two movies are based on their features.

### Vectorization
Vectorization is the process of converting text data into numerical vectors. This is crucial for performing mathematical operations on text data, which is common in recommendation systems.

## Images

![egone](uploads/one.png)

![egtwo](uploads/two.png)

![egthree](uploads/three.png)

## License
This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for more details.

## Acknowledgment
Special thanks to Campus X for providing guidance and resources throughout the development of this project.

