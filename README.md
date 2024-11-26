
# Blind-AI: Assistive Reading Device for the Visually Impaired

## Overview
Blind-AI is a revolutionary assistive device aimed at empowering visually impaired individuals by enabling them to read printed or handwritten text effortlessly. It combines advanced Optical Character Recognition (OCR), Text-to-Speech (TTS), and Artificial Intelligence (AI) technologies, running on the NVIDIA Jetson Nano platform, to deliver an intuitive and accessible user experience.

## Technical Details
- **Processor:** NVIDIA Jetson Nano
- **Input Devices:**
  - USB Camera (for real-time image capture)
  - Microphone (for speech recognition)
- **Output Devices:**
  - Integrated Speakers (for synthesized speech)
- **Libraries and Frameworks:**
  - `pytesseract` (Tesseract OCR)
  - `OpenCV` (`cv2` for image processing)
  - `gTTS` (Google Text-to-Speech)
  - `speech_recognition` (Google Speech Recognition API)
  - `englisttohindi` (English-to-Hindi translation)
  - `google.generativeai` (Google Gemini AI for contextual responses)

## Features

### Optical Character Recognition (OCR)
- Captures text from printed or handwritten materials using Tesseract OCR.
- Processes live video streams and images for real-time text recognition.

### Text-to-Speech (TTS) Conversion
- Converts recognized text into natural-sounding speech using the Google TTS library.
- Supports multilingual output in both English and Hindi.

### Real-Time Translation
- Translates recognized English text into Hindi using the `englisttohindi` library.
- Provides Hindi speech output for enhanced accessibility.

### Generative AI Integration
- Utilizes Google’s Gemini AI for contextual understanding and advanced natural language interactions.
- Responds intelligently to user inputs, enhancing user engagement.

### Speech Recognition
- Captures and processes voice commands using the Google Speech Recognition API.
- Enables hands-free operation and control of the device.

### User-Friendly Interface
- Hotkey-based controls for intuitive operation:
  - `f`: Perform OCR
  - `g`: Send OCR text to Gemini AI
  - `h`: Translate OCR text to Hindi and speak
  - `j`: Speech-to-text conversion and AI interaction
  - `k`: Speech-to-text translation to Hindi and speech output

## Code Summary
- **Initialization:** Configures OCR, TTS, and AI modules, ensuring seamless hardware-software communication.
- **Image Processing:** Captures and preprocesses images (grayscale conversion, noise reduction) for accurate OCR.
- **Speech Processing:**
  - Converts recognized text to speech in real-time.
  - Captures user voice commands and translates them into text for further processing.
- **AI Integration:** Sends OCR or speech inputs to Google Gemini AI for contextual responses.
- **Multilingual Support:** Translates English text into Hindi and provides synthesized speech output.

## Key Learnings and Experience
- Gained expertise in integrating OCR, TTS, and speech recognition systems.
- Hands-on experience with real-time processing on the NVIDIA Jetson Nano platform.
- Developed skills in Python programming, computer vision, and natural language processing.
- Improved proficiency in AI model integration and managing complex hardware-software interactions.
- Designed user-centered solutions to address accessibility challenges, contributing to social impact through technology.
