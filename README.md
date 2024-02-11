# SRISHTI_assignment_1


# Coffee Shop People Count Maintenance

This project aims to maintain the count of people entering and exiting a coffee shop using YOLO object detection.

## Usage

- Clone the repository.
- Ensure you have the necessary dependencies installed (OpenCV, Pandas, NumPy, Ultralytics YOLO).
- Run the `main.py` script.
- Ensure the `peoplecount1.mp4` file is present in the directory.

## Features

- Counts the number of people entering and exiting the coffee shop.
- Displays the count on the video frame.
- Draws regions of interest (ROI) for entry and exit.
- Supports tracking of people using the Tracker class.
- Dataset is just one required video.
- for individual videos we assign the required "region of interest" manually.
  

## Contributing

Contributions are welcome! If you'd like to contribute to the project, please open an issue to discuss your ideas or submit a pull request.

## Credits

- The implementation of this project was inspired by the YouTube video (https://www.youtube.com/watch?v=tbscP_d11Zw) and (https://www.youtube.com/watch?v=m9fH9OWn8YM)
- Special thanks to "freedomwebtech" and "computer vision engineer" for providing valuable insights and guidance in the video.
- The YOLO model used in this project is from the Ultralytics YOLO repository: [Ultralytics YOLO](https://github.com/ultralytics/yolov5).
