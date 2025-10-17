# Captcha Solver Task

This project is a robust captcha solver that can recognize and solve text-based captchas from images using basic OCR techniques. The system accepts base64 encoded image inputs, accurately extracts the captcha text, and returns the decoded answer as plain text. Error handling is implemented for unclear or noisy images. The project is built using Python and utilizes commonly used OCR libraries like Tesseract.

## Setup
1. Clone the repository:
```
git clone https://github.com/yourusername/captcha-solver-task.git
```

2. Install the required dependencies:
```
pip install -r requirements.txt
```

3. Download and install Tesseract OCR:
```
sudo apt install tesseract-ocr
```

## Usage
1. Run the script:
```
python captcha_solver.py
```

2. Input a base64 encoded image containing a captcha.

3. The script will extract the captcha text and display the decoded answer.

## Code Explanation
- `captcha_solver.py` contains the main script for solving captchas.
- The script uses the base64 and pytesseract libraries to process the image and extract text.
- Error handling is implemented to handle unclear or noisy images.

## License
This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for more information.