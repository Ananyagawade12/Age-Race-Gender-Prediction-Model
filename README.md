# Age-Race-Gender-Prediction-Model
Model to predict age, gender, and race of humans from facial images.It leverages a convolutional neural network (CNN) architecture to process RGB images. Achieved multi-output predictions by training the model on the UTKFace dataset .Deployed the model via Gradio interface for real-time inference

## How to Use the UTKFace Dataset

1. Log in to [Kaggle](https://www.kaggle.com/).
2. Go to **Account Settings** and create a new API token.
3. Download the `kaggle.json` file.
4. Run the script and upload the `kaggle.json` file when prompted.
5. The dataset will be automatically downloaded and extracted.
6. The extracted dataset will be available in the `./UTKFace` directory.

- If you encounter issues with the Kaggle API, check your internet connection or verify the dataset's URL.
