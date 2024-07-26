# Sign Language Decoder

The Sign Language Decoder is an innovative tool that translates sign language gestures into readable text or speech. Using advanced machine learning algorithms, it facilitates real-time communication between individuals who use sign language and those who do not.

This project was developed for the KEC LITE 2024 Project Demonstration event, showcasing innovative solutions and advancements in technology. The Sign Language Decoder highlights how technology can be harnessed to create impactful social change, facilitating better communication and understanding between individuals.
## Features

- Real-time sign language gesture recognition
- Translation of gestures into text or speech
- Initially trained to detect "happy face", "sad face", and "Wakanda forever" signs

## Libraries Used

- MediaPipe
- OpenCV
- Pandas
- NumPy
- Scikit-Learn
- Pickle

## Algorithms Used

- Random Forest (RF) Classifier
- Gradient Boosting (GB) Classifier
- Logistic Regression
- Ridge Classifier

## Installation

To get started with the Sign Language Decoder, follow these steps:

1. **Clone the repository:**

    ```sh
    git clone https://github.com/yourusername/sign-language-decoder.git
    cd sign-language-decoder
    ```

2. **Install the required libraries:**

    ```sh
    pip install mediapipe opencv-python pandas numpy scikit-learn
    ```

3. **Download the pre-trained models:**

    Ensure you have the trained models saved in the appropriate directory. You can download the model, I've uploaded it.

## Usage

1. **Run the decoder:**

    ```sh
    python sign_language_decoder.ipynb
    ```

2. **Interact with the application to see real-time gesture recognition and translation.**
