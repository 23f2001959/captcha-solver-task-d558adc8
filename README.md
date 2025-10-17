# Captcha Solver Task

This project is a robust captcha solver that can recognize and solve text-based captchas from images using basic OCR techniques. It accepts base64 encoded image inputs, accurately extracts the captcha text, and returns the decoded answer as plain text. The system implements error handling for unclear or noisy images and uses Python with commonly used OCR libraries like Tesseract.

## Setup

1. Clone the repository:
```bash
git clone https://github.com/your-username/captcha-solver-task.git
```

2. Install the required dependencies:
```bash
pip install -r requirements.txt
```

## Usage

1. Run the following command to start the captcha solver:
```bash
python solver.py
```

2. Upload a base64 encoded image and wait for the system to recognize and solve the captcha.

## Code Explanation

- `solver.py`: This script contains the main functionality of the captcha solver. It takes a base64 encoded image input, processes it using OCR techniques, and returns the decoded answer.

- `utils.py`: This file contains utility functions for handling base64 encoding and error handling for unclear or noisy images.

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.