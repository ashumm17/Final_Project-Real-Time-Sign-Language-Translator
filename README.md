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

