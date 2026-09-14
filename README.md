# Fruit & Vegetable Freshness Detection — EDA and Feature Engineering

TECH 405 assignment: dataset selection, exploratory data analysis, and feature engineering ahead of
a CNN implementation for classifying fruits and vegetables as fresh or rotten.

## Dataset

[Fruits and Vegetables dataset](https://www.kaggle.com/datasets/muhriddinmuxiddinov/fruits-and-vegetables-dataset)
by Muhriddin Mukhiddinov (Kaggle). Approximately 12,000 images across 20 classes: five fruits
(apple, banana, orange, mango, strawberry) and five vegetables (tomato, cucumber, carrot, potato,
bell pepper), each split into fresh and rotten.

## Contents

- `EDA_Fruit_Vegetable_Freshness.ipynb` — full exploratory data analysis and feature engineering
  notebook (class distribution, sample images, dimension analysis, color/brightness analysis,
  data quality checks, label encoding, train/val/test split, class weighting, augmentation
  preview).
- `requirements.txt` — Python dependencies.

## Setup

```bash
pip install -r requirements.txt

# Kaggle API download (requires kaggle.json in ~/.kaggle/)
kaggle datasets download -d muhriddinmuxiddinov/fruits-and-vegetables-dataset -p ./data --unzip
```

Then open `EDA_Fruit_Vegetable_Freshness.ipynb` and run all cells.

## Next steps

The CNN model implementation using the preprocessing pipeline established here is the subject of
the following assignment.


