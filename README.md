# Deep-Learning---Instance-Segmentation

# Reproducibility

- Clone repository
- Create a Python virtual environment with your preferred package manager
- Activate virtual environment
- Run `pip install -r requirements.txt`
- Run code blocks in yolo.ipynb in data-models folder
    - Add preferred hyperparameters to model.train method 
- Dataset is already provided in converted format
- Pre-trained models are present in the pretrained-weights folder
- Our final run is present in runs/segment
    - The best model of this run is included in weights/best.pt such that you can inference on this model without training it

Dataset was downloaded from https://www.kaggle.com/datasets/ihelon/football-player-segmentation.

If you wish to run data-conversion and data-exploration notebooks you will have to download the dataset.
