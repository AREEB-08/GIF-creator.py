# 🎥 Video to GIF Converter

This **Python script** allows users to extract a specific portion of a video, rotate it by 90 degrees, and convert it into a **GIF**. The script uses the `moviepy` library for seamless video processing.

---
## 🌟 Features
✅ Extracts a selected portion of a video
✅ Rotates the clip by **90 degrees**
✅ Converts the extracted clip into a **GIF**
✅ User-friendly input prompts
✅ Automatically adds `.gif` extension if missing

---
## 🛠 Prerequisites
To use this script, you need to install the following tools and libraries:

1. **Python** (Ensure Python is installed on your system)
2. **FFmpeg** (Required for video processing)
3. **MoviePy** (Python library for video editing)
4. **A GIF Viewer** (To view the generated GIFs, such as IrfanView, XnView, or any web browser)

You can install them using the following commands:
To use this script, you need to install the following tools and libraries:

1. **Python** (Ensure Python is installed on your system)
2. **FFmpeg** (Required for video processing)
3. **MoviePy** (Python library for video editing)

You can install them using the following commands:

### 🔹 Install Python (if not installed):
Download and install Python from [official site](https://www.python.org/downloads/).

### 🔹 Install FFmpeg:
- **For Windows:** Download and install FFmpeg from [FFmpeg website](https://ffmpeg.org/download.html)
- **For Linux/macOS:** Run the following command:
```sh
sudo apt update && sudo apt install ffmpeg -y  # Debian/Ubuntu
brew install ffmpeg  # macOS
```

### 🔹 Install MoviePy:
```sh
pip install moviepy
```
Ensure you have **Python** installed on your system. You will also need the `moviepy` library, which you can install using:

```sh
pip install moviepy
```

---
## 🚀 How to Use

### 🔹 Step 1: Run the Script
Open your **terminal or command prompt** and execute:
```sh
python GIF-Creator-1.py
```

### 🔹 Step 2: Provide Required Inputs
When prompted, enter the following details:

📌 **Full file path of the video:**  
Example: `C:\Users\User\Videos\sample.mp4` (For Windows)  
Example: `/home/user/videos/sample.mp4` (For Linux/macOS)

📌 **Start and End Time (in seconds):**  
Example: Enter `5` to start at 5 seconds and `15` to end at 15 seconds.

📌 **Output GIF file name:**  
Example: `my_clip`  _(The script will automatically add `.gif` if omitted)_

### 🔹 Step 3: Script Execution
- The script will **load the video file** from the provided location.
- It will **extract the selected portion** from `start` to `end` time.
- The extracted clip will be **rotated by 90 degrees**.
- The processed clip will be **converted into a GIF** and saved in the same directory.

---
## 🎬 Example Usage

### 🔹 How to View the Generated GIF
After the script has successfully generated a GIF, you can view it using:
- **Windows:** Open it with **Photos**, **IrfanView**, or any web browser (Chrome, Firefox, Edge).
- **Linux/macOS:** Open it using **Image Viewer**, **XnView**, or a web browser.

If you need to download a GIF viewer, you can install:
```sh
# Windows (IrfanView)
winget install IrfanView.IrfanView

# Linux (XnView)
sudo apt install xnview

# macOS (XnView)
brew install xnview
```
```
Enter the full file path of the video (e.g., 'C:/videos/video1.mp4'): "C:/Users/User/Videos/sample.mp4"
Enter the start time in seconds (e.g., 0 for the beginning): 5
Enter the end time in seconds (e.g., 10 for 10 seconds): 15
Enter the name for the output GIF (e.g., 'output.gif'): my_clip
```

🎉 **Output:** The script will generate a GIF named **`my_clip.gif`** in the same directory.

---
## 📝 Notes
- ✅ Ensure the **video file exists** before running the script.
- ✅ If no `.gif` extension is provided, it **will be automatically added**.
- ✅ The script **rotates the video by 90 degrees**. If unwanted, **remove that line** from the script.
- ❌ Avoid using **special characters** in file names.

---
## 📜 License
This script is **open-source**. Feel free to modify and improve it!

---
## 👨‍💻 Author
📝 AREEB-08

