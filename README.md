# Pizza vs. Steak Classification

This repository contains a project focused on classifying images of pizza 🍕 and steak 🥩 using a modified version of the Food101 dataset. The original dataset includes 101 different classes of food, but for simplicity and focused learning, we've reduced it to only two classes: pizza and steak.

## Dataset

- **Source:** The images are from the [Food101 dataset](https://www.kaggle.com/datasets/dansbecker/food-101).
- **Modification:** The dataset has been modified to include only two classes (pizza and steak) using the [Image Data Modification Notebook](https://github.com/mrdbourke/tensorflow-deep-learning/blob/main/extras/image_data_modification.ipynb).

## Project Structure

- `Pizza_vs_Steak_Classification.ipynb` - Jupyter Notebook for training and evaluating a deep learning model on the pizza vs. steak dataset.
- `README.md` - This file, providing an overview of the project.
- `data/` - Directory containing the modified dataset (not included in the repository).
- `models/` - Directory to save trained models.

## Features

- Image data preprocessing and augmentation.
- Implementation of a Convolutional Neural Network (CNN) to classify pizza and steak images.
- Visualization of model performance metrics including accuracy and loss curves.

## Installation

1. **Clone the repository:**
     ```bash
     git clone https://github.com/mazimum86/Convolutional-Neural-Network.git
  
2. Navigate to the project directory:
    ```bash
    cd Convolutional-Neural-Network
    
3. Install the required dependencies:
   ```bash
   pip install -r requirements.txt

## Usage

1. Run the notebook:
   ```bash
   jupyter notebook Pizza_vs_Steak_Classification.ipynb
   
2. Follow the steps in the notebook to preprocess data, train the model, and evaluate its performance.

3. Save or load pre-trained models from the models/ directory.

## Contributing
Contributions are welcome! If you have suggestions for improvements or new features, please open an issue or submit a pull request.

## License
This project is licensed under the MIT License. See the LICENSE file for details.
