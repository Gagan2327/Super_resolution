# Super_resolution
# Enhance Your Images with Super Resolution using OpenCV and Deep Learning

Enhance low-resolution images using advanced deep learning models like **EDSR** and **LapSRN** in combination with **OpenCV's dnn_superres module**. This project compares traditional upscaling techniques (like bicubic interpolation) with deep learning-based super-resolution to demonstrate the improvements in image quality.
# Project Structure

- `EDSR_x4.pb` – Pretrained EDSR model (4x upscaling)
- `LapSRN_x8.pb` – Pretrained LapSRN model (8x upscaling)
- `test.png` – Sample low-resolution input image
- `upscaled_test.png` – Output using EDSR
- `upscaled_test_lapsrn.png` – Output using LapSRN
- `bicubic_test.png` – Traditional bicubic output (4x)
- `bicubic_test_8x.png` – Traditional bicubic output (8x)
- `super_resolution.py` – Core Python script

---

## 🛠️ Requirements

Install dependencies using pip:

```bash
pip install opencv-python
