# Captcha Solver Task

## Summary
This project aims to develop a robust captcha solver that can recognize and solve text-based captchas from images using basic Optical Character Recognition (OCR) techniques. The system should accept base64 encoded image inputs, accurately extract the captcha text, and return the decoded answer as plain text. Error handling is implemented for unclear or noisy images. Python is used along with commonly used OCR libraries like Tesseract.

## Setup
1. Install Python if not already installed.
2. Install the required libraries by running `pip install -r requirements.txt`.
3. Clone the repository using `git clone https://github.com/yourusername/captcha-solver-task.git`.

## Usage
1. Encode the captcha image to base64 format.
2. Use the `captcha_solver.py` script with the base64 encoded image as input.
3. The script will output the decoded captcha text.

Example:
```
python captcha_solver.py --image base64_encoded_image.txt
```

## Code Explanation
The `captcha_solver.py` script uses the Tesseract OCR library to extract text from the input image. It preprocesses the image by applying filters and transformations to improve OCR accuracy. Error handling is implemented to handle cases where the image is unclear or noisy. The decoded text is then outputted as plain text.

## License
This project is licensed under the [MIT License](https://opensource.org/licenses/MIT). See the `LICENSE` file for more details.

Feel free to contribute to the project by submitting pull requests or reporting issues. Thank you for using the Captcha Solver Task!