# OCR Image Text Extraction

This project demonstrates how to extract text from images using Optical Character Recognition (OCR) techniques. It includes a Python script that loads an image, preprocesses it, performs OCR using Tesseract, and outputs the text along with bounding boxes and confidence intervals.

## Installation

To run this project, you need to have Python installed on your system. You can install the required Python packages using pip:

```bash
pip install opencv-python pytesseract
```

You also need to have Tesseract OCR installed on your system. You can download and install it from the official [Tesseract GitHub repository](https://github.com/tesseract-ocr/tesseract).

## Usage

1. Clone this repository to your local machine:

```bash
git clone https://github.com/your-username/ocr-image-text-extraction.git
```

2. Navigate to the project directory:

```bash
cd ocr-image-text-extraction
```

3. Place your image file in the project directory and update the `image_path` variable in the script with the filename.

4. Run the Python script:

```bash
python ocr_extraction.py
```

This will process the image, perform OCR, and output the result with bounding boxes and confidence intervals.

## Contributing

Contributions are welcome! If you have any suggestions, bug reports, or feature requests, please open an issue or submit a pull request. Make sure to follow the contribution guidelines outlined in the `CONTRIBUTING.md` file.

## License

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.
