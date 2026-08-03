# Smart Face Recognition-Based Attendance System

This project is a Smart Face Recognition-Based Attendance System designed to automate and simplify the process of taking attendance using facial recognition technology. It leverages machine learning and computer vision to identify and verify individuals in real-time.

## Features

- Fast and accurate face recognition for attendance marking
- Easy registration of new students/employees
- Secure and automated attendance records
- User-friendly interface for attendance management

## Prerequisites

- Python 3.7 or higher installed

## Setup Instructions

### 1. Clone the Repository

```bash
git clone https://github.com/Sumantradas01/Smart-Attendance-System.git
cd Smart-Attendance-System
```

### 2. Create a Virtual Environment

It’s recommended to use a virtual environment to manage dependencies and avoid conflicts.

**On Windows:**
```bash
python -m venv venv
```

**On macOS/Linux:**
```bash
python3 -m venv venv
```

### 3. Activate the Virtual Environment

**On Windows:**
```bash
venv\Scripts\activate
```

**On macOS/Linux:**
```bash
source venv/bin/activate
```

You should see `(venv)` at the beginning of your terminal prompt.

### 4. Install Project Dependencies

Make sure you are in the project directory and your virtual environment is activated. Then run:

```bash
pip install -r requirements.txt
```

This will install all necessary libraries, including:
- OpenCV
- face_recognition
- numpy
- pandas
- ...and other dependencies specified in `requirements.txt`

### 5. Run the Attendance System

After installing dependencies, you can start the attendance system:

```bash
python main.py
```
_(Replace `main.py` with your actual entry point if different.)_

## How It Works

1. **Register Faces**: Capture and store the faces of individuals in the system.
2. **Start Attendance**: The camera scans faces in real-time and compares them with the database.
3. **Mark Present**: Recognized individuals are marked as present in the attendance records.
4. **Export Records**: Generate attendance reports as needed.

## Project Structure

```
Smart-Attendance-System/
├── attendance/          # Attendance logic and records
├── dataset/             # Stored face images
├── requirements.txt     # Python dependencies
├── main.py              # Main script to run the system
└── README.md
```

## Project Link

You can view the live demo / deployed app here:

https://snapclass.streamlit.app/

## License

This project is for educational purposes.

---

For any issues, please open an [issue](https://github.com/Sumantradas01/Smart-Attendance-System/issues) or submit a pull request.
