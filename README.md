# Number Plate Detection and Recognition

## 📋 Project Overview

This project focuses on developing a system that detects and recognizes number plates from images using advanced deep learning techniques. We use the YOLOv8 model for detecting number plates and PaddleOCR for extracting the text from these plates. This system can be useful for various applications, including automated toll systems, parking management, and law enforcement.

## ✨ Features

- **Real-Time Number Plate Detection**: Utilizes YOLOv8 for fast and accurate detection of license plates in images.
- **Text Recognition**: Extracts and recognizes text from detected license plates using PaddleOCR.
- **Batch Image Processing**: Capable of processing multiple images at once, making it scalable for larger datasets.
- **Customizable**: The system can be fine-tuned for different types of license plates and regions.
- **Performance Tracking**: Outputs results in a structured format, allowing for easy analysis and further processing.

## 🛠️ Tools and Technologies

- **YOLOv8**: State-of-the-art object detection model used for identifying number plates in images.
- **PaddleOCR**: A powerful OCR tool used to extract text from detected number plates.
- **Python**: The core programming language used to integrate the detection and recognition systems.
- **OpenCV**: A computer vision library used for image processing and manipulation.
- **Pandas**: A data analysis library used to store and manage the extracted text data.
- **Google Colab**: A cloud-based platform used to run the project, with GPU support for faster computations.

## 🚀 Installation

To set up this project locally, follow these steps:

1. **Clone the Repository:**
    ```bash
    git clone https://github.com/AbdulRehman-git/license-plate-detection-YOLOv8-PaddleOCR.git
    ```

2. **Move to cloned folder:**
    ```bash
    cd license-plate-detection-YOLOv8-PaddleOCR
    ```

3. **Install Dependencies:**
    Make sure you have Python 3.9 installed, then install the required libraries:
    ```bash
    pip install ultralytics opencv-python matplotlib pandas paddlepaddle paddleocr
    ```

## 🏗️ Usage

1. Open the notebook `Number Plate Detection.ipynb` in Google Colab or a local Jupyter environment.
2. Run the cells to install the required packages and configure the YOLOv8 model.
3. Execute the cells to start detecting number plates and extracting text in real-time or from a batch of images.

## 📝 Notes

- Ensure that the images are of good quality for better detection and recognition accuracy.
- You can fine-tune the YOLOv8 model if you plan to use it for a different region or plate design.
- The project is optimized for use in Google Colab but can be adapted for local environments.
- If you are training the model, ensure that you update the data paths in the data.yaml file to reflect the correct locations of your datasets.

## 📜 License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## 🙏 Acknowledgments

- [YOLOv8](https://github.com/ultralytics/yolov8) for the object detection model.
- [PaddleOCR](https://github.com/PaddlePaddle/PaddleOCR) for the text recognition tool.
- [OpenCV](https://opencv.org/) for the image processing library.
- [Google Colab](https://colab.research.google.com/) for providing a cloud-based environment.

## 📧 Contact

For questions or suggestions, please contact 
- [![Email](https://img.shields.io/badge/Gmail-Contact-red)](mailto:inboxx.abdulrehman@gamil.com)
  - Feel free to reach out via email at inboxx.abdulrehman@gamil.com.
- [![LinkedIn](https://img.shields.io/badge/LinkedIn-Connect-blue)](http://www.linkedin.com/in/abdul-rehman-052292271)
  - Connect with me on LinkedIn for professional updates and discussions.
- [![Twitter](https://img.shields.io/badge/Twitter-Follow-blue)](https://twitter.com/AbdulRehman_twt)
  - Follow me on Twitter for the latest in data science trends and insights.

