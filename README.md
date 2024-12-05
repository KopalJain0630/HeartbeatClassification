Heartbeat Classification
This project aims at assembling an at-home heart screening tool to detect abnormalities in the heartbeats, facilitating prompt consultation.
The heartbeat audio signals collected from clinical trials were converted into vectors using wav2vec and exploratory data analysis was performed on it, using the Librosa library.

The dataset had a very small size, and hence was not approproate to develop a suitable model.
Hence, we generated a dataset of 10,000 audio vectors from an initial dataset of 200 vectors by employing Generative Adversarial Networks for data generation.
We attained an accuracy of 92% in the initial, 91% in the intermediate, and 90% in the final classification step, by building a CNN-LSTM hybrid algorithm

Classification Tasks:
1. Task 1: Classification of heartbeat into normal and murmur
2. Task 2: Classification of murmur into systolic and diastolic
3. Task 3: Classification of systolic murmur into ESM and PSM
