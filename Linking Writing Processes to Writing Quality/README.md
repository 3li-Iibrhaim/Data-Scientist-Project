## Linking Writing Processes to Writing Quality ✍️ 📝

https://www.kaggle.com/competitions/linking-writing-processes-to-writing-quality/


I participated in the "Linking Writing Processes to Writing Quality" Kaggle competition. The goal of this competition was to predict overall writing quality by exploring the relationship between learners’ writing behaviors and writing performance. The dataset includes keystroke logs capturing writing process features.

### Team Solution

For a detailed overview of our team's solution, you can visit our [Kaggle Discussion Page](https://www.kaggle.com/competitions/linking-writing-processes-to-writing-quality/discussion/466839#2594913).

### Writing Quality Prediction

In the "Writing Quality Prediction" Kaggle competition, I achieved exceptional results:

- **Public RMSE Score (3rd Place):** 0.570977
- **Private RMSE Score (38th Place):** 0.566772

These scores reflect the performance of my model on both seen and unseen data, and the improvement in the private phase highlights the robustness of the solution.

### Kaggle Competition Badge

[![Linking Writing Processes to Writing Quality Kaggle Competition Badge](https://www.kaggle.com/c/linking-writing-processes-to-writing-quality/badge)](https://www.kaggle.com/c/linking-writing-processes-to-writing-quality)

### Notebooks

#### Solution Notebooks

- `linking-38th-place-solution-3rd-public.ipynb`: Main notebook for the final solution, achieving 3rd place in the public leaderboard and 38th in the private leaderboard.
- `linking-train-nb-06228f.ipynb`: Notebook related to the training process.
- `linking-train-nb-a5cc87-1bbb7f.ipynb`: Another notebook related to the training process.
- `linking-preprocessing-papers-and-artical-features.ipynb`: Preprocessing notebook for papers and article features.
- `lofo-importance/`:
  - `20 Dec, Lofo Importanc LGBM.ipynb`: Notebook for feature importance using LGBM.
  - `20 Dec, Lofo Importanc Ridge - Copy.ipynb`: Notebook for feature importance using Ridge.
  - `20 Dec, Lofo Importanc SVR.ipynb`: Notebook for feature importance using SVR.

#### Other Notebooks

- `24 Dec RandomForect LOFO.ipynb`: Notebook related to Random Forest and LOFO (Leave-One-Feature-Out) analysis.
- `essay-contructor.ipynb`: Notebook for constructing essays.

### Data Collection Procedure

For more detailed information about the competition dataset, you can refer to the [Data Collection Procedure](<URL to the Data Collection Procedure page>) page.

### File and Field Information

#### Train Logs

- `train_logs.csv`: Input logs to be used as training data.
  - `id`: The unique ID of the essay
  - `event_id`: The index of the event, ordered chronologically
  - ...

#### Test Logs

- `test_logs.csv`: Input logs to be used as test data. Contains the same fields as `train_logs.csv`.

#### Train Scores

- `train_scores.csv`: Scores for the essays in the training set.
  - `id`: The unique ID of the essay
  - `score`: The score the essay received out of 6 (the prediction target for the competition)

#### Sample Submission

- `sample_submission.csv`: A submission file in the correct format. See the Evaluation page for details.

Please note that this is a Code Competition. When your submission is scored, the example test data in `test_logs.csv` will be replaced with the full test set. There are logs for about 2500 essays in the test set.
