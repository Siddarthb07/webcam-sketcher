# webcam-sketcher

Minimal OpenCV project that converts live webcam frames into a sketch-like edge mask.

## Pipeline

For each frame:

1. Convert to grayscale
2. Apply Gaussian blur
3. Run Canny edge detection
4. Apply binary inverse threshold
5. Display resulting sketch mask in real time

## Run

```bash
python "webcame capture.py"
```

Press `Enter` (key code `13`) to exit.

## Dependencies

```bash
pip install opencv-python numpy
```

## Notes

- Script name is currently `webcame capture.py` (spelling kept as in repo).
- This is a quick prototype and does not include camera error handling.

