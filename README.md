# OpenCV Color Picker

A desktop color picker built with **Python, NumPy, and OpenCV**. Adjust red, green, and blue trackbars to preview a color on a canvas.

## Run

Use Python with access to a desktop display:

```sh
python3 -m venv .venv
source .venv/bin/activate
python -m pip install -r requirements.txt
python Color_Picker_OpenCV.py
```

Use regular `opencv-python`; the headless variant cannot display the interface.

## Controls

- Set `ON/OFF` to **1** to enable the preview.
- Adjust `R`, `G`, and `B` from 0 to 255.
- Press **q** while the preview window has focus to exit.

The sliders use RGB labels; the NumPy canvas uses OpenCV's BGR order. This example previews colors without sampling other windows or exporting color values. GUI behavior has not been verified in the current environment.
