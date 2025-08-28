# COVID-19 Image Classification with YOLOv8

This project implements a COVID-19 image classification system using YOLOv8. The model classifies chest X-ray images into three categories: COVID-19, Normal, and Viral Pneumonia.

[Türkçe README için tıklayınız](README_TR.md)

## Dataset

The dataset consists of chest X-ray images divided into three categories:
- COVID-19
- Normal
- Viral Pneumonia

Dataset distribution:
- Training: 12,121 images
- Validation: 1,514 images
- Test: 1,518 images

## Project Structure

```
├── data/
│   ├── covid_classification/
│   │   ├── train/
│   │   ├── val/
│   │   └── test/
│   └── covid_dataset/
├── runs/
│   └── classify/
└── requirements.txt
```

## Requirements

- Python 3.8+
- YOLOv8
- Other dependencies listed in requirements.txt

## Installation

1. Clone the repository:
```bash
git clone https://github.com/Semihkulekcioglu/covid19_xray_classification_yolov8.git
cd covid19_xray_classification_yolov8
```

2. Install dependencies:
```bash
pip install -r requirements.txt
```

## Usage

The project includes scripts for:
- Data preparation: `find_images.py`
- Dataset splitting: `split.py`
- Model training and evaluation using YOLOv8

## Results

The model's performance metrics and visualizations can be found in the `runs/classify/yolov8_covid_classification/` directory.

## License

This project is open-source and available under the MIT License.
