
# Data ML — Chest X-Ray Multi-Condition Detection

*Fill this out and submit it as README.md in your team's GitHub repository*

## 1. Team Details

| Field | Details |
|---|---|
| Team Name | ____________________ |
| Team Members (4) | 1. ______  2. ______  3. ______  4. ______ |
| Team Lead (contact) | Name — Email/Phone |
| GitHub Repository Link | https://github.com/____________________ |

## 2. Repository Structure

```
├── code/           # Final notebook(s) or script(s) — must run end-to-end
├── predictions/    # predictions.csv on the held-out test set
├── README.md       # This write-up
└── pitch_deck/     # Slide deck for the Final Round (if selected)
```

## 3. Problem Understanding

*Write 3–5 sentences here.*

We are predicting the probability of five conditions — Atelectasis, Effusion, Infiltration, Nodule, and Pneumothorax — for each chest X-ray in the test set. This is a multi-label problem, since a single scan can show multiple conditions or none at all. The core challenge is feature engineering: since deep learning and pretrained models are not permitted, we must hand-design an image representation that captures the visual patterns distinguishing these conditions before applying a classical ML model.

## 4. Exploratory Data Analysis (EDA)

*Write 1–2 short paragraphs here. Reference any charts included in your /code folder.*

## 5. Approach & Methodology

### 5.1 Feature Engineering

*List the key features you engineered and why.*

### 5.2 Model(s) Used

*Name the model(s), key hyperparameters, and why you chose them.*

## 6. Results

| Metric | Score | Notes |
|---|---|---|
| | | |
| | | |

Predictions file: submitted as `predictions.csv` inside `/predictions`, with columns matching the test set's ID column plus one probability column per condition (Atelectasis, Effusion, Infiltration, Nodule, Pneumothorax), as specified in the problem brief.

## 7. Key Insight

*Write 3–5 sentences here — the ONE most surprising or valuable insight, to present in the Final Round if selected.*

## 8. Wildcard Challenges Attempted

| Challenge | Attempted? (Y/N) | Where to find it in the repo |
|---|---|---|
| Best Visualization | | |
| Most Interpretable Model | | |
| Fastest Inference Time | | |
| Best Handling of Messy/Incomplete Data | | |

## 9. Declaration

We confirm that this submission is original work completed by our team during the official event window (Days 1–28), built solely on the officially released dataset, and does not reuse pre-existing projects or another team's code.

*Team Lead name & signature/date*

---

### Constraints Reminder (Classical ML Only)

- **Allowed:** Logistic Regression, SVM, Random Forest, Gradient Boosting, k-NN, hand-designed features, NumPy/pandas/scikit-learn/OpenCV/scikit-image.
- **Not allowed:** CNNs, deep learning, pretrained models/feature extractors (ResNet, DenseNet, VGG, EfficientNet, etc.) at any pipeline stage. Violations are disqualified from scoring.
