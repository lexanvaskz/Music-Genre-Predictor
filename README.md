# Music-Genre-Predictor
This predictor predicts 10 genres (Blues Classical Country Disco Hip-hop Jazz Metal Pop Reggae Rock) with Decision Tree as the training algorithm model and STFT for feature extraction

Utilizing the Short-Time Fourier Transform (STFT) and a Decision Tree model, the system classifies music genres to provide personalized playlist links. Audio signals are captured using a laptop microphone, and features are extracted using STFT implemented with Librosa in Python on Jupyter Notebook. The GTZAN dataset is used for training and testing the model, achieving an average training accuracy of 75% and testing accuracy of 54%.

![image](https://github.com/user-attachments/assets/41166375-770f-4c8f-887b-1a0c3f22260b)


The project involves several stages: audio signal acquisition, feature extraction with STFT, spectrogram display, and music genre classification. The trained model is then used to classify new audio recordings obtained via Sounddevice. The final output includes genre predictions and corresponding playlist links, displayed on a Streamlit website. This research demonstrates the feasibility of combining STFT and Decision Tree techniques for automatic music genre prediction.
