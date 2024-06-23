# Person Identification Using EEG Data

In a world increasingly driven by digital interactions, the need for robust and unique identification methods is more crucial than ever. Traditional biometric systems like fingerprint and facial recognition have their limitations and vulnerabilities. Imagine a world where your unique brain activity could serve as your password—impossible to forge and unique to you. This project explores this cutting-edge approach by leveraging EEG (electroencephalogram) data to identify individuals based on their brainwave patterns. Welcome to the future of biometric identification!

## Dataset Overview

- **Name:** EEG Motor Imagery (BCIC IV 2a)
- **Source:** BCI Competition IV
- **Description:** The dataset includes EEG recordings from subjects who were asked to imagine left-hand and right-hand movements.
- **Recording Method:** EEG signals were recorded using a 22-channel EEG system.
- **Session Structure:** Each recording session consisted of several trials, with each trial including a cue indicating the movement type (left or right hand) followed by a motor imagery period.
- **Objective:** While the dataset is typically used for EEG-based motor imagery classification tasks, this project aims to use it for person identification.
- **Dataset Link:** [EEG Motor Imagery (BCIC IV 2a) Dataset](https://www.kaggle.com/datasets/aymanmostafa11/eeg-motor-imagery-bciciv-2a)

## Project Structure

The notebook is organized as follows:

1. **Introduction**
   - Overview of the dataset and project objectives.

2. **Data Loading and Preprocessing**
   - Loading the dataset.
   - Preprocessing steps including filtering and artifact removal.

3. **Feature Extraction**
   - Extracting relevant features from the EEG signals for person identification.

4. **Model Training and Evaluation**
   - Training machine learning models on the extracted features.
   - Evaluating the performance of the models.

5. **Results**
   - Analysis of the results and discussion of the model's performance.

## License

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for more details.

## Acknowledgements

- The dataset used in this project is provided by the BCI Competition IV.
- Special thanks to the creators and contributors of the original dataset.
