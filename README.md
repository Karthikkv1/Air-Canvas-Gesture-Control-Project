

# Real-Time Drawing and Color Detection using OpenCV

This Python project utilizes OpenCV and NumPy to create a real-time drawing application with color detection capabilities. It allows users to draw on a canvas using different colors and clear the canvas as needed.

## Features

- **Real-Time Drawing**: Allows users to draw lines on a canvas using different colors.
- **Color Detection**: Utilizes color detection to change the drawing color based on the detected color from the webcam feed.
- **Clear Functionality**: Provides an option to clear the canvas and start over.
- **Adjustable Color Parameters**: Users can adjust the upper and lower HSV values for color detection using trackbars.

## Installation

1. Ensure you have Python installed on your system.
2. Install the required dependencies:
   ```
   pip install opencv-python numpy
   ```
3. Clone the repository to your local machine:
   ```
   git clone <repository_url>
   ```

## Usage

1. Run the main program using Python:
   ```
   python drawing_and_color_detection.py
   ```
2. Adjust the trackbars to set the upper and lower HSV values for color detection.
3. Use the webcam feed to select colors by moving objects of those colors in front of the camera.
4. Draw on the canvas by moving objects of the selected color in front of the camera.
5. Press the 'q' key to exit the application.



## Contributing

Contributions are welcome! If you find any bugs or have suggestions for improvements, please open an issue or submit a pull request.

