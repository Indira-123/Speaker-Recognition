# Audio Classification with cosine similarity and KNN

This project demonstrates audio classification using cosine similarity and a K-Nearest Neighbors (KNN) model. The audio files are preprocessed by extracting MFCC (Mel-frequency Cepstral Coefficients) features, applying PCA (Principal Component Analysis) for dimensionality reduction, and then using KNN for classification.

## Libraries Used
- `torchaudio` for audio processing
- `sklearn` for machine learning algorithms (KNN, PCA)
- `matplotlib`, `seaborn` for data visualization

## Dataset
- 9 Training and 9 test audios are used for classifying audio samples.
- The dataset contains `.m4a` audio files for training and testing.

## Process
1. **Waveform Visualization**: Visualizes the waveform of audio files.
2. **MFCC Extraction**: Extracts MFCC features from audio signals.
3. **PCA**: Reduces the dimensionality of the features using PCA for better visualization.
4. **Cosine Similarity**: Calculates similarity between test and train audio files.
5. **KNN Classification**: Trains a KNN model on the PCA-reduced features and predicts the class of test samples.

## Results
- The KNN model achieved **100% accuracy** on the test set.

## Visualization
- PCA visualization of the feature space.
- Heatmap of cosine similarity between test and train audio files.
