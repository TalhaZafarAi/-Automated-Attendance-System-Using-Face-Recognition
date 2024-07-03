# -Automated-Attendance-System-Using-Face-Recognition
The Automated Attendance System Using Face Recognition is a project that leverages FaceNet for face detection, MTCNN for face cropping, and a Convolutional Neural Network (CNN) for training and evaluation. The system facilitates real-time attendance tracking through the laptop's webcam.


## Features

- Face detection powered by FaceNet
- Face cropping using MTCNN
- CNN-based training and testing for accuracy
- Real-time attendance tracking via webcam

## Requirements

- Python 3
- OpenCV
- TensorFlow
- NumPy

## Installation

1. Clone the repository:

   ```bash
   git clone https://github.com/your_username/automated-attendance-system.git
   ```

2. Install the required dependencies:

   ```bash
   pip install -r requirements.txt
   ```

Ensure Jupyter Notebook is installed. If not, you can install it with pip:

   ```bash
   pip install jupyterlab
   ```

To start the Jupyter Notebook server, run the following command in your terminal:

   ```bash
   jupyter notebook
   ```

This will open a new tab in your web browser displaying the Jupyter Notebook dashboard. Navigate to your `Automated_Attendance_System.ipynb` file and click on it to open.

You can execute the code cells in the notebook by pressing Shift + Enter.

If you prefer running the code outside Jupyter Notebook, you can convert the notebook to a Python script using:

```bash
jupyter nbconvert --to script Automated_Attendance_System.ipynb
```

This will generate a `.py` file, which you can run with the `python` command. Note that some interactive features of Jupyter Notebook may not function in a standard Python script.

3. Run the application:

   ```bash
   python Automated_Attendance_System.py
   ```

## Usage

1. Ensure your webcam is connected and functional.
2. Execute the `main.py` file.
3. The application will detect faces in real-time and record attendance accordingly.

## Acknowledgements

This project was developed with support from the following resources:

- [FaceNet](https://github.com/davidsandberg/facenet)
- [MTCNN](https://github.com/ipazc/mtcnn)
- [TensorFlow](https://www.tensorflow.org/)
