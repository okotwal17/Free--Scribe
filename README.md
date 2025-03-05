# Free Scribe

Free Scribe is a web-based app that allows users to record and upload audio, which is then transcribed and translated into text. The app utilizes speech recognition and translation APIs to process the audio input and deliver accurate transcriptions and translations. This project was created to practice integrating external APIs and building interactive user interfaces with React.

## Features

### 1. **Audio Recording**
- Users can record audio directly within the app using the built-in microphone feature.
- Supports recording in multiple audio formats.

### 2. **Transcription**
- The app transcribes the recorded audio into text using a speech-to-text API.
- Provides an accurate transcription of spoken words with minimal latency.

### 3. **Translation**
- After transcribing the audio, the app translates the transcribed text into the desired language.
- Supports translation into multiple languages.

### 4. **Editable Transcripts**
- Once the audio is transcribed, users can edit and refine the text.
- Allows for better accuracy and customization in the output.

### 5. **Simple and User-Friendly Interface**
- Clean and intuitive UI that guides users through the process of recording, transcribing, and translating audio.
- Seamless experience with real-time feedback during recording.

## Tech Stack

- **Frontend**: React
- **APIs**: Speech-to-Text API (e.g., Google Cloud Speech), Translation API (e.g., Google Translate API)
- **State Management**: React `useState` and `useEffect` hooks
- **Styling**: CSS (for responsive and clean layout)
- **Audio Processing**: Web Audio API for recording audio

## Process and What I Learned

### 1. **Setting Up the Project**
- Started with `create-react-app` to initialize the project and set up the development environment.
- Organized the app into components: Audio recorder, Transcription display, Translation interface, and editable transcript section.

### 2. **Integrating Speech-to-Text API**
- Integrated the Speech-to-Text API to convert audio recordings into text. This required setting up API keys and handling asynchronous requests.
- Ensured that the app accurately transcribes the spoken words, even with various accents or speech patterns.

### 3. **Integrating Translation API**
- Implemented the Translation API to translate the transcribed text into different languages.
- Allowed users to select a target language for the translation and provided real-time feedback.

### 4. **Recording Audio**
- Used the Web Audio API and MediaRecorder API to record audio in the browser.
- Implemented functionality to handle different audio formats and quality levels for accurate transcription.

### 5. **Handling State and Feedback**
- Managed application state with React’s `useState` hook to store the audio input, transcription, and translation data.
- Provided real-time feedback to users during the recording process and displayed results once the transcription and translation were complete.

### 6. **User Interface**
- Focused on building a simple, accessible interface that guides users through the steps.
- Implemented a progress bar for audio recording, a text box for transcriptions, and a dropdown for selecting translation languages.

## Lessons Learned

- **API Integration**: Gained experience integrating external APIs for speech recognition and translation, which required handling asynchronous data and error management.
- **Audio Processing**: Learned how to handle audio recording and processing in the browser using the Web Audio API and MediaRecorder API.
- **React State Management**: Practiced managing complex state transitions in React, especially with asynchronous data and multiple components.
- **User Experience**: Focused on providing a smooth user experience with clear steps, real-time feedback, and a responsive design.
- **Debugging**: Developed skills in debugging complex issues related to audio recording, API responses, and real-time UI updates.

## Getting Started

1. **Clone the Repository**
   - Clone the repository to your local machine using `git clone`.

2. **Install Dependencies**
   - Run `npm install` to install all required dependencies.

3. **Run the App**
   - Run `npm start` to launch the app in your default browser.

4. **Record and Transcribe**
   - Click the “Record” button to start recording audio, then let the app transcribe and translate your audio to text.
