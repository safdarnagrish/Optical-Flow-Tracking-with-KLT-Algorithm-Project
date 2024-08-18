# Optical Flow Tracking with KLT Algorithm

## Semester Project

This project demonstrates the application of the Kanade-Lucas-Tomasi (KLT) feature tracking algorithm on a video file. The project tracks key points across frames and visualizes the motion by drawing lines and bounding boxes around the tracked points.

## Project Overview

In this project, we utilize the KLT algorithm combined with the Lucas-Kanade method for optical flow estimation to track the movement of features between video frames. This technique is commonly used in computer vision for object tracking, motion detection, and video analysis.

### Key Features

- **Video Processing**: Load and process each frame of a video.
- **Feature Detection**: Identify and track up to 100 prominent features in the video using the KLT algorithm.
- **Optical Flow Calculation**: Estimate the motion of features between consecutive frames.
- **Visualization**: Draw motion tracks and bounding boxes around moving objects, and save the processed frames as images.

## Installation

### Prerequisites

Ensure you have Python 3.x installed, along with the following libraries:

- OpenCV (`cv2`)
- NumPy
- Matplotlib
- IPython

Install the required packages using `pip`:

```bash
pip install opencv-python numpy matplotlib ipython
```

## Usage

1. **Clone the Repository**:

   ```bash
   git clone https://github.com/yourusername/optical-flow-klt.git
   cd optical-flow-klt
   ```

2. **Place the Video File**:

   Make sure your video file is placed in the `Video/` directory with the name `footage.mp4`. You can change the video file name or path in the script if needed.

3. **Run the Script**:

   Execute the script to process the video and save the frames:

   ```bash
   python optical_flow_klt.py
   ```

4. **Output**:

   The processed frames with the tracked features will be saved in the `Video/output/` directory. The frames will also be displayed as the script runs.

## Project Structure

- `optical_flow_klt.py`: The main script that performs video processing and feature tracking.
- `Video/`: Directory where the input video (`footage.mp4`) is placed.
- `Video/output/`: Directory where the processed frames are saved.

## Example Output

After running the script, you should see images like these:

- **Original Frame**: The unprocessed frame from the video.
- **Tracked Frame**: The frame with motion tracks and bounding boxes around the tracked features.

## License

This project is open-source and available under the MIT License. Feel free to modify, share, and use the code for your own projects.

## Acknowledgments

- This project was developed as part of a university course on Computer Vision and Image Processing.
- The KLT algorithm and Lucas-Kanade method are well-established techniques in the field of optical flow and feature tracking.

## Contact

For any questions or collaboration opportunities, you can reach me at:



### Instructions:
- **Replace placeholders**: Make sure to replace `yourusername` and `your-email@example.com` with your actual GitHub username and email.
- **Script Name**: Ensure the script filename (`optical_flow_klt.py`) matches the actual name in your project.
