# AI Image Classifier (Python)

![AI Image Classifier Screenshot](screenshot.png)

A modern **AI image classification application** built with Python and PyTorch.  
It uses a pretrained ResNet-18 model to classify images into **1000 ImageNet categories**, with a clean GUI and real-time progress tracking.

---

## Features

### AI Classification
- Pretrained **ResNet-18 (ImageNet) model**
- Classifies images into **1000 classes**
- Shows **Top-5 predictions**
- Displays confidence percentages
- Automatically downloads and caches ImageNet labels

### Single Image Mode
- Select and classify a single image
- Instant prediction results
- Preview image inside GUI
- Shows best-matching class with confidence

### Folder Classification Mode
- Classify all images in a folder
- Supports multiple formats (jpg, png, bmp, gif, etc.)
- Progress bar with percentage
- Estimated time remaining (ETA)
- Logs results for each image

### Graphical User Interface
- Built with Tkinter + ttk styling
- Modern dark/light hybrid theme
- Image preview panel
- Activity log window
- Status bar with live updates
- Responsive layout with threading (UI never freezes)

---

## Technologies Used

- Python 3
- PyTorch
- Torchvision (ResNet-18 model)
- Pillow (PIL)
- Tkinter (GUI)
- ttk / ttk themes
- JSON (label caching)
- urllib (label download)

---

## How to Run

1. Install dependencies:

```bash
pip install torch torchvision pillow
