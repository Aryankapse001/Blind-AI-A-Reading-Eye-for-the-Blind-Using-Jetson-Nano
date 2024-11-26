 Overview
 Blind-AI is an assistive device designed to empower visually impaired individuals by leveraging
 the computational power of the NVIDIA Jetson Nano. This innovative solution combines Optical
 Character Recognition (OCR) and Text-to-Speech (TTS) technologies to convert printed text into
 synthesized speech, enabling users to access and comprehend written information effortlessly.

 Features
 1. Optical Character Recognition (OCR):
 ○ Captures text from images or live video streams using Tesseract OCR.
 ○ Processes text efficiently for further analysis.
 2. Text-to-Speech Conversion (TTS):
 ○ Converts recognized text into synthesized speech using the Google
 Text-to-Speech (gTTS) library.
 ○ Supports both English and Hindi language outputs.
 3. Real-Time Translation:
 ○ Translates recognized English text into Hindi using the EngtoHindi library.
 ○ Provides Hindi speech output for localized accessibility.
 4. Generative AI Integration:
 ○ Utilizes Google's Gemini AI for advanced natural language interactions and
 contextual understanding.
 ○ Responds intelligently to user inputs, including OCR text and speech commands.
 5. Speech Recognition:
○ Converts spoken commands into text using Google's Speech Recognition API.
 ○ Enables hands-free operation and interaction with the system.
 6. User-Friendly Interface:
 ○ Compactand lightweight design for easy portability.
 ○ Interactive controls for performing OCR, translation, and generative AI
 interactions.

 Technical Details
 1. Hardware Components:
 ○ Processor: NVIDIA Jetson Nano.
 ○ Camera:USBcamera for real-time image capture.
 ○ Audio: Integrated speakers for speech output.
 ○ Microphone: For voice input and speech recognition.
 2. Libraries and Frameworks:
 ○ cv2(OpenCV): For image processing and video capture.
 ○ pytesseract: OCR for extracting text from images.
 ○ gTTS:Text-to-speech conversion.
 ○ englisttohindi: Translation of English text to Hindi.
 ○ speech_recognition: Speech-to-text conversion.
 ○ google.generativeai: Integration with Google's Gemini AI for advanced
 conversational capabilities.
 3. Functions:
 ○ OCRCapture: Captures and processes images from a live video feed.
 ○ TTSConversion: Converts processed text into speech for immediate playback.
 ○ Translation: Provides Hindi translation for localized accessibility.
 ○ Generative AI: Processes input text for contextual AI responses.
 ○ SpeechRecognition: Allows voice commands for interaction and input.
 4. Custom Features:
 ○ Multi-language support (English and Hindi).
 ○ Hotkey-based controls for intuitive use:
 ■ f:Perform OCR.
 ■ g:SendOCRtext to Gemini AI.
 ■ h:Translate OCR text to Hindi and speak.
 ■ j:Speech-to-text conversion and interaction with Gemini AI.
 ■ k:Speech-to-text in English, translate to Hindi, and speak.
 
 Key Functionalities in Code
1. OCRandSpeechOutput:
 ○ Captures frames from the camera.
 ○ Converts the frames to grayscale for better OCR accuracy.
 ○ Synthesizes speech from recognized text using gTTS.
 2. Translation and Speech:
 ○ Translates English text into Hindi.
 ○ Converts translated text into Hindi speech.
 3. Generative AI Integration:
 ○ SendsOCRorspeech-to-text inputs to Gemini AI.
 ○ Processes AI responses and generates synthesized speech output.
 4. Speech Recognition:
 ○ Captures voice input.
 ○ Converts speech to text for further processing or interaction.
 
 Achievements
 ● Developed a compact and user-friendly assistive device for the visually impaired.
 ● Successfully integrated OCR, TTS, and AI functionalities into a seamless user
 experience.
 ● Enhanced accessibility with bilingual (English and Hindi) support.
 ● Leveraged NVIDIA Jetson Nano's processing power for efficient visual data analysis and
 real-time operations.

 Applications
 ● Accessibility: Enables visually impaired individuals to read printed materials and
 interact with text-based information.
 ● Education: Assists in learning and comprehension for non-native English speakers.
 ● Real-Time AI Assistance: Provides context-aware AI responses for enhanced user
 experience.
 This project demonstrates the practical application of AI and embedded systems to create
 impactful solutions for the differently-abled community.
