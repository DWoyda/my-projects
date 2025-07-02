# Football Transfermarkt Analysis

Analysis of football data from the public dataset [Football Data from Transfermarkt](https://www.kaggle.com/datasets/davidcariboo/player-scores/data).

## 📥 How to download the data

The data **is not included in the repository**. You need to download it manually. Follow these steps:

1️⃣ **Generate your Kaggle API Token**  
Go to your [Kaggle Account Settings](https://www.kaggle.com/settings/account), click **Create New API Token**, and download the `kaggle.json` file.

2️⃣ **Configure your API token**  
- Create a folder called `.kaggle` in your home directory:
  - Windows: `C:\Users\YourUsername\.kaggle\`
  - Linux/macOS: `/home/yourusername/.kaggle/`
- Move the downloaded `kaggle.json` file into that folder.

3️⃣ **Download the dataset directly in your notebook**  
Use the following Python code to download the dataset (this will download the **latest version**, which as of **02.07.2025** is version **602**):

```python
import kagglehub

# Download latest version
path = kagglehub.dataset_download("davidcariboo/player-scores")

print("Path to dataset files:", path)

# if not 

