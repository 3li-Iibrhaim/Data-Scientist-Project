# CommonLit - Evaluate Student Summaries


https://www.kaggle.com/competitions/commonlit-evaluate-student-summaries/data

I participated in the CommonLit Kaggle competition and secured the 180th place out of 2,064 participants, earning a bronze medal. This repository contains the code and resources related to my submission.

## Overview

The goal of the CommonLit competition was to assess the quality of summaries written by students in grades 3-12. Participants were tasked with building a model that evaluates how well a student represents the main idea and details of a source text, as well as the clarity, precision, and fluency of the language used in the summary. The provided dataset comprises about 24,000 summaries written by students, with assigned scores for both content and wording. The competition requires predicting content and wording scores for summaries on unseen topics.

## Dataset

The dataset consists of the following files:

- `summaries_train.csv`: Summaries in the training set.
- `summaries_test.csv`: Summaries in the test set. Contains all fields except content and wording.
- `prompts_train.csv`: Training set prompts. Each prompt comprises the complete summarization assignment given to students.
- `prompts_test.csv`: Test set prompts. Contains the same fields as above. The prompts here are only an example. The full test set has a large number of prompts.
- `sample_submission.csv`: A submission file in the correct format. See the Evaluation page for details.

## File and Field Information

Submissions are scored using MCRMSE (mean columnwise root mean squared error).

## Results

In the CommonLit Kaggle competition, my model achieved the following scores:

- **Public Score:** 0.44086
- **Private Score:** 0.48308

The public score is based on a subset of the test data and is visible on the Kaggle leaderboard throughout the competition. The private score is computed on a separate, hidden subset of the test data and is revealed after the competition concludes. These scores, evaluated using the MCRMSE metric, provide insights into the model's performance on both seen and unseen data.



Feel free to elaborate further on the significance of these metrics or provide any additional insights into your model's performance.

## Project Structure

- `notebooks/`:
  - commonlite-test-model-inference.ipyb
  - commonlite-inference 2.ipynb
  - commonlite-inference.ipynb
    
- `data/`: Data used for the competition.
- `scripts/`: Any additional scripts or code snippets.
- `README.md`: The file you're currently reading.

## Usage

To reproduce the results, follow these steps:

```bash
# Example installation steps
pip install -r alishog.txt
