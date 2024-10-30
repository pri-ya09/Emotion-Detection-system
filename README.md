# Emotion-Detection-system
This Emotion Detection System is a real-time application designed to identify human emotions from facial expressions and provide immediate auditory feedback
The project primarily aims to aid visually impaired individuals by interpreting emotional cues and announcing them through speech synthesis. Built with DeepFace for emotion recognition, age, and gender estimation, and Google Text-to-Speech (gTTS) for audio output, the system runs on a straightforward graphical user interface (GUI) created with Tkinter.
Project Objectives
Emotion Detection: Identify emotions (happy, sad, angry, surprised, etc.) in real-time using webcam input.
Auditory Feedback: Convert detected emotions to speech via gTTS, allowing users to hear the emotion detected in their interaction.
Age and Gender Estimation: Extend the emotional insight by detecting age and gender, enhancing user experience with more comprehensive feedback.
How It Works
Webcam Capture: The system uses OpenCV to capture video frames from the webcam.
Emotion Analysis: Each frame is processed by DeepFace to detect the dominant emotion, age, and gender.
Speech Output: Detected emotions are converted to speech using gTTS, providing audio feedback for users.
GUI Interface: A user-friendly interface built with Tkinter allows users to initiate or stop webcam input, view detected emotions, and receive auditory announcements.
Future Enhancements
Mobile Compatibility: Develop a mobile version for increased accessibility.
Audio Emotion Detection: Integrate emotion recognition from voice input.
Improved Accuracy: Optimize the model’s real-time performance and accuracy across different lighting and environmental conditions.
This project demonstrates the practical use of deep learning for social good, offering a tool to enhance communication and accessibility for visually impaired individuals.
