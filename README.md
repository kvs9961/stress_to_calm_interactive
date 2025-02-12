# Stress to Calm Animation

This project generates a soothing animation that transitions from a stressed state to a calm state. The animation features a changing background, dynamic elements like clouds and stars, and the transformation of a face from a stressed expression to a relaxed smile. It also includes a visual progress bar that shows the current status of the animation.

## Features

- **Background Transition**: Smooth blending between a stressed (gray) and calm (light blue) background.
- **Animated Clouds**: Moving clouds with a fading effect as the animation progresses.
- **Face Animation**: The face transitions from a stressed expression (frown) to a calm expression (smile).
- **Progress Bar**: A visual progress bar indicating the current state of the animation.
- **Particles**: Moving stars/particles for added interactivity and dynamism.

## Prerequisites

To run this project, you need to have the following dependencies installed:

- Python 3.x
- OpenCV
- Pillow
- NumPy

You can install the required libraries using `pip`:

```bash
pip install opencv-python pillow numpy
```

## How to Run

1. Clone the repository to your local machine:

    ```bash
    git clone https://github.com/kvs9961/stress-to-calm-animation.git
    ```

2. Navigate to the project directory:

    ```bash
    cd stress-to-calm-animation
    ```

3. Run the Python script to generate the animation:

    ```bash
    python stress_to_calm_animation.py
    ```

4. The script will generate a video file named `stress_to_calm_interactive.mp4` in the project directory.

## Code Overview

- **Helper Functions**:
  - `draw_cloud`: Draws cloud shapes on the canvas.
  - `draw_glow`: Adds a glowing effect around certain objects (like text and the face).
  - `create_frame`: Creates each frame of the animation based on the current progress.
  
- **Animation Logic**:
  - The animation progresses from 0 to 50 frames. At the start, the background is gray and the face shows a stressed expression (frown). As the frames progress, the background gradually changes to light blue, and the face transforms into a calm smile.
  - A progress bar at the bottom of the screen shows the current state.

## Project Output

- **Video**: The script generates a video file (`stress_to_calm_interactive.mp4`) which showcases the transition from stress to calm.
- The video can be opened with any media player that supports MP4 format.

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## Acknowledgments

- Thanks to the [Pillow](https://pillow.readthedocs.io/) and [OpenCV](https://opencv.org/) libraries for providing the tools to handle image processing and video creation.
- Inspiration from relaxation animations and the need to convey mental state transitions visually.

## Contributing

If you'd like to contribute to this project, feel free to fork the repository and create a pull request with your improvements or suggestions!
