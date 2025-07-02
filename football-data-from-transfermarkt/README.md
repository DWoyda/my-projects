# Football Transfermarkt Analysis

Analysis of football data from the public dataset [Football Data from Transfermarkt](https://www.kaggle.com/datasets/davidcariboo/football-data-from-transfermarkt).

## 📥 Downloading the data

The data **is not included in the repository**. Please download it manually:

1. Install the [Kaggle API](https://github.com/Kaggle/kaggle-api).
2. Configure your Kaggle API key ([setup instructions](https://github.com/Kaggle/kaggle-api#api-credentials)).
3. Download and extract the dataset into the repository directory:
    ```bash
    kaggle datasets download -d davidcariboo/football-data-from-transfermarkt
    unzip football-data-from-transfermarkt.zip -d football-data-from-transfermarkt
    ```
4. The folder `football-data-from-transfermarkt/` should be located in the repository directory, next to the analysis notebook.

Alternatively, you can download a specific dataset version directly in your notebook using [kagglehub](https://github.com/Kaggle/kagglehub):
```python
import kagglehub

# Download a specific dataset version (e.g., version 602)
path = kagglehub.dataset_download("davidcariboo/player-scores", dataset_version_number=602)

print("Path to dataset files:", path)
