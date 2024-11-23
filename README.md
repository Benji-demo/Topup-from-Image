#Topup-from-Image
Overview

Topup-from-Image is a project that utilizes OCR (Optical Character Recognition) technology to detect and extract numbers from an image. This is particularly useful for automating tasks such as recharging mobile credit using numbers captured from a screenshot or an image.
Key Features

    Resizable and Draggable GUI
        Built with Tkinter, the interface allows users to resize and reposition the GUI.
        Right-click to resize the GUI to cover the desired area of numbers.

    Automatic Screenshot Capture
        Powered by PyAutoGUI, it captures the region of interest after resizing the GUI.

    OCR Functionality
        Uses PyTesseract to recognize and extract numeric data from the captured image.

    Data Filtering and Processing
        Leverages the re module to filter and extract valid numbers.

    Automated Dialing
        Uses ADB (Android Debug Bridge) commands to automate dialing on Android devices.
        The dialing logic can be adjusted to accommodate specific carrier top-up codes.

Usage Instructions

    Launch the application.
    Adjust the GUI size and position to cover the area with the numbers you want to top up.
    Right-click to finalize the area and trigger the OCR process.
    The extracted numbers will be filtered and used to construct a dialing sequence.
    Ensure your device is connected via ADB to complete the automated top-up process.
