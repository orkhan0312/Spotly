# SpotLy: Spotlight Your Story

## Overview

SpotLy is an innovative application that recommends the most suitable songs based on your mood or feelings. Using advanced Natural Language Processing (NLP) and Large Language Model (LLM) techniques, SpotLy interprets user prompts about emotions and provides tailored music suggestions to enhance your listening experience.

## Features

- **Emotion Detection**: Analyze user prompts to detect nuanced emotions and sentiments.

## Installation

1. **Clone the repository:**
    ```bash
    git clone https://github.com/orkhan0312/Spotly.git
    cd spotly
    ```

2. **Set up the virtual environment:**
    ```bash
    python3 -m venv env
    source env/bin/activate
    ```

3. **Install dependencies:**
    ```bash
    pip install -r requirements.txt
    ```

4. **Set up environment variables:**
    Create a `.env` file in the root directory and add the necessary environment variables (e.g., API keys).

5. **Install Jupyter Notebook:**
    ```bash
    pip install jupyter
    ```

6. **Start Jupyter Notebook:**
    ```bash
    jupyter notebook
    ```

## Dataset

You can find the dataset used [here](https://www.kaggle.com/datasets/carlosgdcj/genius-song-lyrics-with-language-information).

## Usage

1. **Open the application**: Launch Jupyter Notebook by running `jupyter notebook` and open the `SpotLy.ipynb` file.
2. **Run the notebook**: Execute the cells in the notebook to load the model and start analyzing user prompts.
3. **Enter a prompt**: Type in a description of your mood or feelings in the designated cell.
4. **Get recommendations**: Run the subsequent cells to receive and enjoy a curated list of songs tailored to your emotional state.

## Challenges

- **Insufficient Supervised Datasets**: Limited data can lead to less accurate and relevant song recommendations.
- **Song Lyrics Copyright Issues**: Legal constraints can limit lyric availability, affecting recommendation quality.
- **High Computational Requirements**: Limited hardware access can slow development and delay system deployment.

## Future Work

1. **Expand and Refine Datasets**: Collect more diverse data to improve model accuracy.
2. **Improve Emotion Detection**: Enhance NLP model's ability to detect nuanced emotions.
3. **Address Copyright Challenges**: Secure partnerships or licensing agreements with music publishers.
4. **Enhance Personalization**: Develop more sophisticated algorithms to tailor recommendations.
5. **Optimize Computational Efficiency**: Reduce computational requirements for better performance.
6. **User Experience Improvements**: Continuously refine the app’s design and functionality.
7. **Explore New Features**: Introduce innovative features such as playlist generation and mood tracking.

## Contact

For any questions or feedback, please contact me at orxan03121@gmail.com.
