# GherisNetQuiz



*An interactive quiz to learn network fundamentals in an engaging way.*

---

## Table of Contents
- [Description](#description)
- [Features](#features)
- [Requirements](#requirements)
- [Installation](#installation)
- [Usage](#usage)
- [Contributing](#contributing)
- [License](#license)
- [Credits](#credits)
- [Contact](#contact)

---

## Description
**NetFundamentals** is an interactive quiz to learn network fundamentals, featuring 40 questions in English and Italian on protocols, OSI model, IP addresses, and more. With a modern interface, animations, real-time stats, and result saving, it’s ideal for students and professionals. Created by Gheris, it’s distributed as a Windows executable (NetFundamentals.exe`) for a seamless, engaging experience.

---

## Features
- **Bilingual Support**: Questions, options, and explanations in English and Italian.
- **40 Network Fundamentals Questions**: Covers protocols, OSI layers, IP addresses, devices, and more.
- **Modern Graphical Interface**: Custom theme with fade-in animations, progress bar, and sidebar for real-time statistics.
- **Error Tracking**: Counts incorrect answers and provides detailed explanations.
- **Dynamic Question Replacement**: Incorrectly answered questions are replaced with new ones, avoiding repetition.
- **Flexible Navigation**: "Previous" and "Next" buttons to review questions.
- **Result Saving**: Scores are saved in `quiz_results.json` in the executable’s directory.
- **Restart Option**: Restart the quiz with a new random question order.
- **Personal Credit**: "Created by Gheris" label displayed at the bottom of the interface.

---

## Requirements
- **Operating System**: Windows 7 or later.
- **Disk Space**: Approximately 20 MB for the executable.
- **No Additional Software Required**: The executable includes all necessary dependencies.

---

## Installation
To use the quiz, follow these steps:

1. **Download the Executable**:
   - Go to the [Releases](https://github.com/Gheris/GherisNetQuiz/releases) section of the repository.
   - Download the latest version of `GherisNetQuiz.exe`.

2. **Run the Application**:
   - Move `NetFundamentals.exe` to a folder of your choice.
   - Double-click `NetFundamentals.exe` to launch the quiz.

*Note*: Windows may display a security warning for downloaded files. Click "Run anyway" to proceed.

---

## Usage
1. Run `NetFundamentals.exe` by double-clicking.
2. Select the language (English or Italian) from the dropdown menu.
3. Click "Start Quiz" to begin.
4. Answer questions by selecting an option and clicking "Submit Answer."
5. Use the "Previous" and "Next" buttons to navigate between questions.
6. View statistics (score, errors, percentage) in the sidebar.
7. Upon completion, results are saved in `quiz_results.json` in the executable’s folder.
8. Click "Restart" to retake the quiz.

**Example output in `quiz_results.json`**:
```json
[
  {
    "timestamp": "2025-07-19 18:57:45",
    "language": "en",
    "score": 38,
    "total_questions": 40,
    "errors": 2,
    "percentage": 95.0,
    "feedback": "Good job! You know the concepts well."
  }
]
```

**Sample Screenshot**:  

<img width="1255" height="859" alt="Screenshot 2025-07-19 185103" src="https://github.com/user-attachments/assets/50f7fcd2-8c5a-45d0-a414-0f111a14ce00" />


<img width="1008" height="766" alt="Screenshot 2025-07-19 185131" src="https://github.com/user-attachments/assets/ca9fe747-dd13-4a8d-8da1-d6d00c5d42bd" />


---


## License
This project is licensed under the [MIT License](LICENSE.md). You may use, modify, and distribute the code freely, subject to the license terms.

---

## Credits
- **Author**: Gheris ([GitHub](https://github.com/Gheris))
- **Resources Used**:
  - [Python Documentation](https://docs.python.org/3/) for `tkinter` and JSON.
  - [PyInstaller](https://pyinstaller.org/) for creating the executable.
  - [Shields.io](https://shields.io/) for custom badges.
- **Contributors**: Thanks to everyone who has contributed to the project!

---

## Contact
Have questions or suggestions? Reach out:
- **Email**: gheris@example.com
- **GitHub**: [Gheris](https://github.com/Gheris)

---

*Last updated: July 19, 2025*
