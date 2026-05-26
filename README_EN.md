# PNG Background Remover

<p align="center">
  <img src="screenshots/ico.ico" width="96" alt="App Icon">
</p>


<p align="center">
  <a href="./README.md">中文</a> | <a href="#-english">English</a>
</p>

---

**Download PNG Background Transparentizer**：[**Download**](https://drive.google.com/drive/folders/1bPKGqEdW9uTrhabXa1AXELAyy2JyFF4l?usp=drive_link) 

## 🇬🇧 English

### 📌 Introduction

**PNG Background Transparentizer** is a Python and PySide6-based desktop tool that effortlessly removes backgrounds from AI-generated PNGs. Whether it's a gray-white checkerboard, solid white, or any light-colored background, this tool quickly converts it to transparency. It's perfect for creating icons for scientific figures or preparing illustrations for your PowerPoint slides.

This tool is useful for processing:

- PNG images with gray-white checkerboard backgrounds
- Images with pure white backgrounds
- Fake transparent images saved from websites, design tools, or screenshots
- Image assets that need to be exported as transparent PNG files

---

### ✨ Features

- 🎨 Modern frameless UI design
- 🖱️ Drag-and-drop PNG import
- 🧩 Remove gray-white checkerboard backgrounds
- ⚪ Remove pure white backgrounds
- 🎚️ Adjustable parameters:
  - White threshold
  - Gray brightness range
  - Tolerance
  - Edge softness
- 🚀 Built-in processing modes:
  - Checkerboard
  - White Background
  - Strong Remove
  - Soft Remove
- 👀 Preview original image and processed result
- 🔍 Preview zoom, fit-to-window, and 100% view
- 💾 Export transparent PNG files
- 📦 Supports Windows EXE packaging with PyInstaller

---

### 🖼️ Screenshot

![Screenshot](./screenshots/screenshot.png)

------

### 📁 How to Use

1. Launch the application.
2. Drag a PNG image into the import area, or click the import area to select a PNG file.
3. Choose a suitable processing mode:
   - **Checkerboard**: for fake transparent checkerboard backgrounds
   - **White Background**: for white-background images
   - **Strong Remove**: for images with more obvious background residue
   - **Soft Remove**: for light-colored subjects, reducing the risk of removing important pixels
4. Adjust parameters if needed.
5. Click **Generate Preview**.
6. After confirming the result, click **Export PNG**.

------

### ⚙️ Parameters

| Parameter                    | Description                                                  |
| ---------------------------- | ------------------------------------------------------------ |
| White Threshold              | Controls the detection range of light background pixels. Lower values detect more pixels. |
| Gray Min Brightness          | Minimum brightness for detecting gray checkerboard areas.    |
| Gray Max Brightness          | Maximum brightness for detecting gray checkerboard areas.    |
| Tolerance                    | Controls how close RGB values must be to be treated as gray. |
| Edge Softness                | Reduces gray or white artifacts around object edges.         |
| Remove Pure White Background | Enables additional pure white background removal.            |
| Pure White Threshold         | Controls the strength of pure white background detection.    |

------

### ⚠️ Notes

- This tool is mainly designed for removing light-colored, white, and gray-white checkerboard backgrounds.
- If the image subject contains a lot of white or light gray colors, it is recommended to use the **Soft Remove** mode.
- Complex backgrounds may require manual parameter adjustment.
- The output format is PNG in order to preserve transparency.

------

### 🤝 Contributing

Issues and Pull Requests are welcome.

You can help improve:

- UI design
- Background removal algorithm
- Multi-language support
- Batch processing
- macOS / Linux compatibility