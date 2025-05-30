
# 🖌️ Air-Canvas

![Python](https://img.shields.io/badge/Python-3.x-blue?logo=python)
![OpenCV](https://img.shields.io/badge/OpenCV-RealTime-green?logo=opencv)
![Platform](https://img.shields.io/badge/Platform-Windows%20%7C%20Linux-lightgrey)
![Status](https://img.shields.io/badge/Status-Active-brightgreen)

This project demonstrates **real-time color detection and drawing** using OpenCV. The application captures video from your webcam, detects specific colors based on HSV ranges, and allows you to draw on a virtual canvas simply by moving colored objects in front of the camera.

---

## ✨ Features

- 🎥 Real-time video capture and processing
- 🎨 HSV color space conversion for robust color detection
- 🧭 Trackbars for dynamic adjustment of HSV thresholds
- 🖼️ Draw on a virtual canvas using detected colors
- 🟡 Color selection for dynamic drawing
- 🧹 Clear the canvas with a button

---

## 💻 Requirements

- [Python 3.x](https://www.python.org/downloads/)
- [OpenCV (cv2)](https://pypi.org/project/opencv-python/)
- [NumPy](https://pypi.org/project/numpy/)

Install requirements via pip:

```bash
pip install opencv-python numpy
```

---

## 🧠 Code Explanation

- 🎚️ **HSV Trackbars**: Enable live adjustment of HSV thresholds for optimal color detection.
- 🖌️ **Drawing Mechanism**: Draws on the canvas using color-detected object positions.
- 🎨 **Color Buttons**: Switch between different drawing colors.
- 🧽 **Clear Button**: Wipe the entire canvas to start over.

---

## 🤝 Contributing

Contributions are welcome!  
Feel free to fork the repository and submit a pull request with your enhancements or bug fixes.

---

## 🙏 Acknowledgements

- 📘 [OpenCV Documentation](https://docs.opencv.org/)
- 📘 [NumPy Documentation](https://numpy.org/doc/)

---


## 📄 License

This project is open-source and available under the [MIT License](LICENSE).

