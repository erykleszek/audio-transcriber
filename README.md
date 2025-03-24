# Audio Transcriber

## 📌 Project Description
Audio Transcriber is a web application that allows users to upload audio files and automatically transcribe their content. The project consists of a **Spring Boot** backend and a **React + Vite** frontend.

## 🚀 Technologies
### Backend:
- **Java 17**
- **Spring Boot 3.2.3**
- **Maven**
- **Spring Web** – API handling
- **Spring Boot DevTools** – development support
- **Spring AI**
### Frontend:
- **Vite** – fast build and development
- **React** – component-based UI
- **CSS** 
## ⚙ Installation and Running

### Backend
1. Ensure you have **Java 17** and **Maven** installed.
2. Clone the repository:
   ```bash
   git clone https://github.com/your-repo/audio-transcriber.git
   cd audio-transcriber
   ```
3. Start the backend:
   ```bash
   mvn spring-boot:run
   ```
   The backend should be available at `http://localhost:8080`.

### Frontend
1. Navigate to the `frontend` directory:
   ```bash
   cd frontend
   ```
2. Install dependencies:
   ```bash
   npm install
   ```
3. Start the frontend:
   ```bash
   npm run dev
   ```
   The application should be available at `http://localhost:5173`.

## 📄 API Endpoints
- `POST /upload` – Upload an audio file for transcription
- `GET /transcription/{id}` – Retrieve transcription results

## 🛠 Future Enhancements
- Support for multiple audio file formats (WAV, FLAC)
- User transcription history
- Integration with OpenAI Whisper for improved transcription quality

## 📜 License
This project is available under the MIT license.

---
Let me know if you need any changes or additions! 😊

