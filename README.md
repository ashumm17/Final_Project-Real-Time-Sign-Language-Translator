# Final_Project-Real-Time-Sign-Language-Translator

Real-Time Sign Language Translator is a deep learning-based application designed to bridge the communication gap for the hearing and speech-impaired. The system converts text or speech input into real-time sign language gestures using TensorFlow, MediaPipe, and OpenCV. It also includes Text-to-Speech functionality to translate recognized sign language gestures back into spoken words.

Features :

Text-to-Sign Language Translation: Converts text into sign language gestures using a deep learning model.

Speech-to-Sign Language Translation: Converts speech into sign language gestures in real-time.

Sign Language to Text/Speech: Converts recognized sign language gestures into text or speech.

Real-time Processing: The system works in real-time using a webcam for hand gesture recognition and translation.

Text-to-Speech: Integrated pyttsx3 library to convert the output text into spoken language.

Technologies Used:

TensorFlow: Used for building and training the machine learning models for hand gesture recognition and translation.

MediaPipe: Utilized for hand tracking and gesture recognition in real-time.

OpenCV: Used for handling image input, video streams, and pre-processing for model inference.

TensorFlow Lite: Optimized for mobile deployment to ensure lightweight, efficient operation.

pyttsx3: Text-to-Speech library to read out the generated text.

Flask (Optional): For creating a web interface if required.

Installation :
To set up and run this project locally, follow the steps below:

1. Clone the repository
bash
Copy
Edit
git clone https://github.com/yourusername/real-time-sign-language-translator.git
cd real-time-sign-language-translator
2. Set up a virtual environment (optional but recommended)
bash
Copy
Edit
python -m venv venv
source venv/bin/activate  # On Windows, use venv\Scripts\activate
3. Install the required dependencies
bash
Copy
Edit
pip install -r requirements.txt
You may need to install additional dependencies, such as TensorFlow and OpenCV, based on your system.

Usage
Text-to-Sign Language:

Input text directly into the command line or through a GUI (if implemented) to convert it to sign language gestures.

Speech-to-Sign Language:

Speak into the microphone, and the system will recognize and convert the spoken words into sign language gestures.

Sign Language to Text/Speech:

Use the webcam to perform sign language gestures, and the system will output either text or speech.

To run the project, use the following command:

bash
Copy
Edit
python main.py
Dataset
The project is trained on a variety of public datasets for hand gestures and sign language. If you plan to train the model further, you can use the following datasets:

Sign Language MNIST: A dataset of American Sign Language (ASL) digits.

ASL Alphabet Dataset: A dataset containing images of ASL letters.

You may need to adapt the dataset according to your project needs.

License :
This project is licensed under the MIT License - see the LICENSE file for details.

Contributing :
We welcome contributions to the project. If you'd like to contribute, please fork the repository and create a pull request. When contributing, please ensure that you:

Follow the coding standards used in the project.

Ensure all tests pass (if applicable).

Provide a detailed description of the changes you're making.

Acknowledgements : 
TensorFlow for machine learning model building.

MediaPipe for real-time hand gesture tracking.

OpenCV for handling image input and video streams.

pyttsx3 for text-to-speech conversion.
