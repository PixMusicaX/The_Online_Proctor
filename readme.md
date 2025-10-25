# Online Exam Proctor

Welcome to the **Online Exam Proctor** project! This repository contains the source code and resources for an online proctoring system designed to ensure the integrity and security of remote exams.

## Features

- **Real-time Monitoring**: Uses AI to monitor candidates during the exam.
- **Face Detection**: Detects the candidate's face to ensure they are present.
- **Object Detection**: Identifies unauthorized objects or activities.
- **Activity Logs**: Generates logs of suspicious activities.
- **Scalable Design**: Easily integrates into existing online exam platforms.

## Installation

1. Clone the repository:
   ```bash
   git clone https://github.com/PixMusicaX/Online_Exam_Proctor.git
   cd Online_Exam_Proctor
   ```

2. Install the required dependencies:
   ```bash
   pip install -r requirements.txt
   ```

3. Set up the necessary configuration in `.env` file:
   ```
   DB_URL=<your_database_url>
   SECRET_KEY=<your_secret_key>
   ```

4. Run the application:
   ```bash
   python main.py
   ```

## Usage

1. Navigate to the application interface in your browser (default: `http://localhost:5000`).
2. Login as an administrator or candidate.
3. For administrators, set up an exam and monitor the live proctoring feed.
4. For candidates, participate in the exam while the proctoring system monitors your session.

## Technologies Used

- **Backend**: Python (Flask or FastAPI)
- **Frontend**: HTML, CSS, JavaScript
- **Database**: MongoDB (or other database systems)
- **AI Models**: OpenCV, TensorFlow/PyTorch for face and object detection

## Folder Structure

```
Online_Exam_Proctor/
│
├── main.py                # Entry point of the application
├── requirements.txt       # Python dependencies
├── templates/             # Frontend HTML templates
├── static/                # Static files (CSS, JS, Images)
├── models/                # AI/ML models for detection
├── utils/                 # Utility scripts
└── README.md              # Project documentation
```

## Contributing

We welcome contributions to improve this project! To contribute:

1. Fork the repository.
2. Create a new branch for your feature/bug fix.
3. Submit a pull request with a detailed explanation of your changes.

## License

This project is licensed under the [MIT License](LICENSE).

## Contact

If you have any questions or suggestions, feel free to reach out:

- **Repository Owner**: [PixMusicaX](https://github.com/PixMusicaX)
- **Email**: [support@example.com](mailto:pinakipps21@gmail.com)

---

Thank you for checking out the Online Exam Proctor project! Your contributions and feedback are greatly appreciated.
