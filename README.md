# Summer_Internship_2025
Project Title: Speech-to-Phoneme Normalization with CMU Dictionary and TTS
Student Name: Vyom Mukeshkumar Patel
College ID: 22IT121

This project aims to build an interactive web-based application that converts speech into phonemes using the CMU Pronouncing Dictionary and provides audio feedback using a Text-to-Speech (TTS) engine. The project was developed using Python, Flask for the web framework, and libraries such as SpeechRecognition, pyttsx3, NLTK, and sounddevice.

Initially, the system was created to accept voice input, convert it into text using the Google Speech API, extract phonemes using NLTK’s interface with the CMU dictionary, and synthesize speech using pyttsx3. Once the core functionalities were tested in a command-line environment, the focus shifted to building a user-friendly Flask-based web interface. This included audio recording through the browser, phoneme extraction display, and playback features. Basic HTML and CSS were used for UI development, while JavaScript and WebRTC enabled direct microphone access across different browsers.

In the third and fourth weeks, major improvements were made, such as expanding phoneme extraction to entire sentences, logging all transcriptions and their phoneme outputs in a CSV/database, and adding a pronunciation scoring system. The score compares the spoken phonemes to the expected sequence from the CMU dictionary, providing visual feedback with color-coded matching and mismatched sounds.

A dedicated API (/api/score) was introduced to enable future integration or mobile app expansion. A history page was also added to allow users to review their previous recordings, phoneme outputs, and scores. Final testing was conducted across various devices and browsers, ensuring cross-platform compatibility.

In the final week, a project demonstration video, slide presentation, and complete documentation were prepared. The application was successfully deployed on PythonAnywhere, and feedback was gathered from professors and peers, which guided minor refinements in the UI and error handling.

Overall, the project effectively integrates speech processing, phoneme analysis, and TTS synthesis into a cohesive and interactive educational tool, with potential future applications in language learning, speech therapy, and AI-driven pronunciation training.
