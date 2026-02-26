#  Image Dataset Preparation Tool

## Overview
A Google Colab-based Python tool that prepares image datasets for machine learning projects by automatically renaming images and packaging them into a downloadable ZIP file.

This project was created to simplify dataset organization for computer vision training.

---

## Features
- Upload images directly in Google Colab
- Automatic renaming (`Squirrel_001.jpg`, etc.)
- Converts `.jpeg` to `.jpg`
- Batch processing
- Automatic ZIP packaging

---

## Resources Used
- Python
- Google Colab
- File handling
- Automation scripting

---

## How It Works
1. User uploads images
2. Script detects JPEG/JPG files
3. Images are renamed sequentially
4. Dataset packaged into ZIP archive
5. Ready for ML training

---

## Example Workflow

Input:
```
dasdsquilrxld.jpeg
Squilejdiknv.jpg
Squirrel_image.jpeg
```

Output:
```
Squirrel_001.jpg
Squirrel_002.jpg
Squirrel_003.jpg
```

---

## Run in Google Colab
Open notebook and run all cells.

---

## What I Learned
- Dataset preprocessing
- File automation in Python
- Preparing data for ML pipelines
- Efficient batch processing

---

## Future Improvements
- Custom class naming
- Drag & drop interface
- Direct export to ML frameworks
- Adding this stright to my Ml algorith
- I can make this code Modular like using a function and ask for the user input on what to name it
