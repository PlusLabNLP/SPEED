# SPEED
Data for our NAACL-2024 paper "Event Detection from Social Media for Epidemic Prediction"
--

Owing to Twitter's data-sharing policy, we can't publicly share the data. But you can fill out this [Google Form](https://forms.gle/G8hUwZaLqa2EYg596), and we can reach out to you with steps to procure the data.

## Data Statistics

Here are some high level statistics of our data:

| **# Event Types**                    | 7     |
|--------------------------------------|-------|
| **# Sentences**                      | 2,561 |
| **# Event Mentions**                 | 2,889 |
| **Average Event Mentions per Event** | 413   |

We also present the statistics for the train-dev-test splits of our data below:

| **Split** | **Disease** | **# Sentences** | **# Event Mentions** |
|-----------|-------------|-----------------|----------------------|
| Train     | COVID       | 1,601           | 1,746                |
| Dev       | COVID       | 374             | 471                  |
| Test      | Mpox        | 286             | 398                  |
| Test      | Zika/Dengue | 300             | 274                  |

## Training/Evaluating Models

For all model training/evaluations, we utilize [TextEE](https://github.com/ej0cl6/TextEE). Majorly we export our data as a dataset in this repo, create specific configs, and train/evaluate the models using the TextEE scripts.
