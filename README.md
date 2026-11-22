# Snap-In – Smart Attendance System

Snap-In is a face recognition-based smart attendance system designed to automate student identification and attendance management using computer vision. It provides a web-based interface for managing the attendance process efficiently.

## Features

- Face recognition-based student identification.
- Automated attendance recording.
- Computer vision-based face detection and recognition.
- Web-based user interface.
- Frontend and backend communication through REST APIs.
- Organized attendance management.

## Tech Stack

### Frontend
- React.js
- TypeScript
- Tailwind CSS
- Axios
- React Router
- Lucide React Icons

### Backend
- Python
- FastAPI
- Uvicorn
- REST API Architecture

### AI & Face Recognition
- Face Recognition Library
- OpenCV
- NumPy

## Project Structure

```text
Snap_In/
├── src/
│   ├── components/
│   ├── pages/
│   ├── assets/
│   └── ...
├── public/
├── package.json
├── index.html
└── vite.config.ts
```

## Installation and Setup

### Frontend

1. Clone the repository:

```bash
git clone https://github.com/kiruthika569/Snap_In.git
```

2. Navigate to the project folder:

```bash
cd Snap_In
```

3. Install dependencies:

```bash
npm install
```

4. Start the development server:

```bash
npm run dev
```

### Backend

1. Navigate to your backend folder.
2. Install the required Python packages:

```bash
pip install fastapi uvicorn opencv-python numpy face-recognition
```

3. Start the FastAPI server using:

```bash
uvicorn main:app --reload
```

## Purpose

The main objective of Snap-In is to reduce manual attendance work by using face recognition technology to identify students and automate attendance recording.

## Author

**Kiruthika Loganathan**

GitHub: [kiruthika569](https://github.com/kiruthika569)

