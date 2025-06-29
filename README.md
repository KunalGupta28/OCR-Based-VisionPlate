# OCR-Based-VisionPlate
A real-time number plate detection and recognition system using OpenCV and EasyOCR. This project processes vehicle images, locates license plates, and extracts text using Optical Character Recognition.
🚀 Features
Detects number plates from car images using contour-based detection.

Extracts plate text using EasyOCR with support for multiple languages.

Applies preprocessing (grayscale, filtering, edge detection) for accurate results.

Displays the entire pipeline: original image → detection → OCR output.

🛠️ Tech Stack
Python

OpenCV – image processing & contour detection

EasyOCR – text recognition from images

NumPy – array and matrix operations

Matplotlib – visualizing results

imutils – additional image utilities

📸 Sample Workflow
Load vehicle image

Convert to grayscale, apply bilateral filtering

Detect edges (Canny), find contours

Approximate bounding box around the plate

Apply OCR to extract text

Display results

⚙️ How to Run
Clone the repo:

bash
Copy
Edit
git clone https://github.com/KunalGupta28/OCR-Based-VisionPlate.git
cd OCR-Based-VisionPlate
Install dependencies:

bash
Copy
Edit
pip install opencv-python easyocr imutils matplotlib numpy
Run the script:

bash
Copy
Edit
python anpr.py
🧪 Example Output

📌 Notes
Ensure the image is clear and well-lit for better OCR results.

Can be extended to work with video streams and real-time camera input.

🙋‍♂️ Author
Kunal Gupta
