
# Data ML — Chest X-Ray Multi-Condition Detection


## 1. Team Details

| Field | Details |
|---|---|
| Team Name | Coffee and Code |
| Team Members (4) | 1. Abhinav Pabbaraju 2. Narayana Kadali 3. Nithin Padmanabhuni  4. Yashwanth D. |
| Team Lead (contact) | K. Narayana |
| GitHub Repository Link | https://github.com/AbhinavPabbaraju/ML-Model-Varchas |

## 2. Repository Structure

```
├── code/           # Final notebook(s) or script(s) — must run end-to-end
├── predictions/    # predictions.csv on the held-out test set
├── README.md       # This write-up
└── pitch_deck/     # Slide deck for the Final Round (if selected)
```

## 3. Problem Understanding

We are predicting the probability of five conditions — Atelectasis, Effusion, Infiltration, Nodule, and Pneumothorax — for each chest X-ray in the test set. This is a multi-label problem, since a single scan can show multiple conditions or none at all. The core challenge is feature engineering: since deep learning and pretrained models are not permitted, we must hand-design an image representation that captures the visual patterns distinguishing these conditions before applying a classical ML model.

## 4. Exploratory Data Analysis (EDA)

## 5. Approach & Methodology

### 5.1 Feature Engineering


### 5.2 Model(s) Used

## 6. Results

| Metric | Score | Notes |
|---|---|---|
| | | |
| | | |

Predictions file: submitted as `predictions.csv` inside `/predictions`, with columns matching the test set's ID column plus one probability column per condition (Atelectasis, Effusion, Infiltration, Nodule, Pneumothorax), as specified in the problem brief.

## 7. Key Insight


## 8. Wildcard Challenges Attempted

| Challenge | Attempted? (Y/N) | Where to find it in the repo |
|---|---|---|
| Best Visualization | | |
| Most Interpretable Model | | |
| Fastest Inference Time | | |
| Best Handling of Messy/Incomplete Data | | |

## 9. Declaration

We confirm that this submission is original work completed by our team during the official event window (Days 1–28), built solely on the officially released dataset, and does not reuse pre-existing projects or another team's code.


---

### Constraints Reminder (Classical ML Only)

- **Allowed:** Logistic Regression, SVM, Random Forest, Gradient Boosting, k-NN, hand-designed features, NumPy/pandas/scikit-learn/OpenCV/scikit-image.
- **Not allowed:** CNNs, deep learning, pretrained models/feature extractors (ResNet, DenseNet, VGG, EfficientNet, etc.) at any pipeline stage. Violations are disqualified from scoring.
