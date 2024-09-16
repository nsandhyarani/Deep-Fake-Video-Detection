# Deep-Fake-Video-Detection
Deepfake video detection using a combination of Convolutional Neural Networks (CNN) and Long Short-Term Memory (LSTM) networks involves a two-stage model designed for both spatial and temporal feature extraction. The CNN, typically pre-trained on ImageNet (e.g., ResNet50), processes each video frame to capture spatial information, such as facial features and patterns. These features are then passed into the LSTM, which is adept at learning temporal dependencies between frames, enabling it to detect subtle changes in facial movements or inconsistencies in frame sequences. This architecture excels in identifying deepfake videos by leveraging both visual content and temporal dynamics.
