# EuroSAT RGB Land Use Image Classification

This repository demonstrates land use/land cover classification using the EuroSAT RGB remote sensing dataset and a Convolutional Neural Network (CNN) built with TensorFlow/Keras.

## Project Structure

```
EuroSAT-Image-Classification/
├── EuroSAT_RGB/
│   ├── train/
│   └── test/
├── Image_Classification_EuroSAT.ipynb
├── README.md
├── LICENSE
├── .gitignore
├── requirements.txt
└── CREDITS.md
```

- `Image_Classification_EuroSAT.ipynb`: Main Jupyter notebook for data preparation, modeling, evaluation, and visualizations (including confusion matrix, Grad-CAM, etc).
- `EuroSAT_RGB/`: Folder containing the dataset. Place your images here, split into `train/` and `test/` folders by class.
- `requirements.txt`: All Python dependencies for easy setup.
- `CREDITS.md`: Acknowledgements for datasets, code, and inspiration.
- `LICENSE`: Project license.
- `.gitignore`: Files/folders to ignore in version control (e.g., checkpoints, model weights).

## Getting Started

1. **Clone this repo**
2. **Install dependencies**
    ```
    pip install -r requirements.txt
    ```
3. **Prepare the dataset**
    - Download EuroSAT RGB from [here](https://github.com/phelber/eurosat) or the [official page](https://github.com/phelber/EuroSAT).
    - Place the dataset in `EuroSAT_RGB/` as described above.
    - Run the notebook to split the data, train a model, and analyze results.

## Features

- End-to-end image classification pipeline
- Clean notebook with code and explanations
- Advanced visualizations: confusion matrix, Grad-CAM
- Easy to adapt for other remote sensing datasets

## Results

- Model accuracy and confusion matrix are displayed in the notebook.
- Grad-CAM visualizations help interpret model decisions.

## License

See [`LICENSE`](LICENSE) for details.

## Credits

See [`CREDITS.md`](CREDITS.md).