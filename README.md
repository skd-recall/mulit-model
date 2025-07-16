# 🏡 Housing Price Prediction (Images + Tabular Data)

This project predicts housing prices using both house images and tabular data (beds, baths, sqft, city).

## 📂 Dataset

- Images folder: `dataset1/`
- Tabular data CSV: `dataset2.csv`  
  Columns: `image_id, street, citi, n_citi, bed, bath, sqft, price`

## ⚙️ How It Works

- Uses a pre-trained ResNet18 CNN to extract image features.
- Combines image features with tabular data.
- Trains a PyTorch model to predict house prices.
- Evaluates with MAE and RMSE.

## 🚀 Steps

1. Download dataset from Kaggle using `kaggle.json` and Kaggle CLI.
2. Use Google Colab with GPU for training.(due limited physical reasoures available)
3. Start with a small sample of data for testing.
4. Use `tqdm` to see training progress.
5. Save the trained model to Google Drive.

## 📈 Output

- Shows training loss per epoch.
- Prints final MAE and RMSE on validation data.

---

**Made with PyTorch & Google Colab.**
