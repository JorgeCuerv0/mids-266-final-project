# MIDS 266 Final Project: Adaptive Language Learning Quiz

## Overview

This project is part of the MIDS 266 course and focuses on creating an **adaptive language learning quiz** tailored for newcomer 6th graders. The project aims to gamify the language learning experience while leveraging NLP techniques to enhance student engagement and learning outcomes.

The project includes:
- **Interactive learning tasks** such as fill-in-the-blank and synonym matching.
- **Adaptive difficulty** to provide personalized learning experiences.
- Integration of **natural language processing (NLP)** to process language data and generate quizzes dynamically.

## Features

1. **Fill-in-the-Blank Task**  
   - Students are presented with sentences missing specific words.
   - They must complete the sentence by filling in the correct word.
   - Data is stored in `fill_in_the_blank_task_data.csv` and `fill_in_the_blank_task_data.pkl`.

2. **Synonym Matching Task**  
   - Students match words with their correct synonyms.
   - Data is stored in `synonym_task_data.csv` and `synonym_task_data.pkl`.

3. **Reports and Analysis**  
   - A comprehensive final report analyzing the quiz's effectiveness and implementation is included:  
     `Jorge Sandoval Final Report - Adaptive Language Learning Quiz for Newcomer 6th Graders.pdf`.

4. **Interactive Notebook**  
   - The project is implemented in a Jupyter notebook for easy replication and visualization:  
     `266_Final_Project.ipynb`.

## Files and Structure

```
project/
├── Jorge-Sandoval-project/
│   ├── 266_Final_Project.ipynb                       # Jupyter Notebook with the full implementation
│   ├── Jorge Sandoval Final Report - Adaptive Language Learning Quiz for Newcomer 6th Graders.pdf
│   ├── fill_in_the_blank_task_data.csv               # CSV data for the fill-in-the-blank task
│   ├── fill_in_the_blank_task_data.pkl               # Pickled version of the fill-in-the-blank data
│   ├── synonym_task_data.csv                         # CSV data for the synonym matching task
│   ├── synonym_task_data.pkl                         # Pickled version of the synonym data
├── README.md                                         # Project documentation (this file)
```

## Prerequisites

Before running the project, ensure the following are installed:
- Python 3.8 or later
- Jupyter Notebook
- Required Python libraries (specified in the `requirements.txt` file or the notebook):
  - pandas
  - numpy
  - nltk
  - sklearn

## Setup

1. Clone the repository:
   ```bash
   git clone git@github.com:JorgeCuerv0/mids-266-final-project.git
   cd mids-266-final-project
   ```

2. (Optional) Create and activate a virtual environment:
   ```bash
   python -m venv env
   source env/bin/activate   # On Windows, use `env\Scripts\activate`
   ```

3. Install the required Python packages:
   ```bash
   pip install -r requirements.txt
   ```

4. Launch the Jupyter Notebook:
   ```bash
   jupyter notebook
   ```

5. Open `266_Final_Project.ipynb` in Jupyter and follow the instructions to run the code.

## How to Use

1. **Run the Notebook:** Open and run all cells in `266_Final_Project.ipynb`.
2. **Analyze the Data:** Review the provided `.csv` and `.pkl` files for the learning tasks.
3. **Explore the Report:** Read the final report for detailed insights into the project's implementation and results.

## Dataset

The dataset used in this project is the [CLEAR Corpus](https://github.com/scrosseye/CLEAR-Corpus).

## Results

This project demonstrates how gamified, adaptive learning experiences can benefit language acquisition for newcomers. Key outcomes include:
- An intuitive framework for generating language-learning tasks.
- Insights into the effectiveness of personalized, data-driven educational tools.

## Future Work

Possible extensions include:
1. Expanding the task types (e.g., grammar correction, sentence rearrangement).
2. Scaling to support other languages or more advanced learning levels.
3. Integrating into a web or mobile platform for broader accessibility.

## License

This project is released under the [MIT License](LICENSE). You are free to use, modify, and distribute this project as long as proper credit is given.

## Acknowledgments

- **UC Berkeley MIDS Program:** For providing the foundation and resources for this project.
- **Course Instructors and Peers:** For guidance and feedback throughout the development process.
```
