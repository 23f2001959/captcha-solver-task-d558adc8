# Captha-Solver-Task

## Summary
Captha-Solver-Task is a Python-based project that aims to develop a robust captcha solver using basic OCR techniques. The system is designed to recognize and solve text-based captchas from images by accepting base64 encoded inputs and returning the decoded answers as plain text. The project incorporates error handling for unclear or noisy images to ensure accurate results using commonly used OCR libraries like Tesseract.

## Setup
1. Clone the repository:
```bash
git clone https://github.com/your-username/captcha-solver-task.git
```

2. Install the required dependencies:
```bash
pip install -r requirements.txt
```

3. Run the program:
```bash
python captcha_solver.py
```

## Usage
To use the captcha solver, follow these steps:
1. Encode your captcha image to base64.
2. Input the base64 encoded image into the program.
3. The program will extract and display the captcha text.

## Code Explanation
- `captcha_solver.py`: The main script that contains the implementation of the captcha solver using OCR techniques.
- `utils.py`: Contains utility functions for handling base64 encoding and error handling for noisy images.
- `requirements.txt`: Lists the required dependencies for the project.

## License
This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for more details.