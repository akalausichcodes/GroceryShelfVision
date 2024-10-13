# GroceryShelfVision
A computer vision project for detecting and analyzing grocery shelf images, with enhanced capabilities for item detection, dimension estimation, and color analysis. Ideal for retail analytics, specifically for understanding shelf space allocation and product packaging details in grocery store environments.

Project Overview
GroceryShelfVision is a Python-based computer vision application for detecting and analyzing sections of grocery shelves. The tool identifies individual items, estimates dimensions in inches, extracts text, and analyzes dominant colors. This project is useful for retail analysts focusing on product placement, competitor analysis, and category management insights.

Key Features
Enhanced Detection: Uses multiple thresholds in edge detection for improved item detection accuracy, capable of detecting both small and large items.
Pixel-to-Inch Conversion: Provides dimensions in both pixels and inches by assuming a standard package width, useful for size estimation.
Color and Text Analysis: Utilizes K-Means clustering to find dominant colors and OCR for text extraction, aiding in brand and product identification.
Price Estimation: Attempts to estimate prices from detected text, offering insights into product pricing directly from the shelf.
Technologies Used

OpenCV: For image processing, edge detection, and visualization.
scikit-learn: For K-Means clustering to analyze color distributions.
Tesseract OCR: For text recognition from section images.
Python: The core language for developing the entire application.

Installation
Clone the repository:
bash
Copy code
git clone https://github.com/your-username/GroceryShelfVision.git
Install the required libraries:
bash
Copy code
pip install -r requirements.txt
Set up Tesseract OCR. Installation Guide
Usage
Upload an image of a grocery shelf or meat case.
Run the script to detect packages, estimate dimensions, analyze colors, and extract text.
View the results, including a visual output with numbered packages and console output with detailed package analysis.
Contributing
Contributions are welcome! If you have ideas for improvement or additional features, please fork the repository and submit a pull request. Make sure to follow the contribution guidelines.

License
2021 code
