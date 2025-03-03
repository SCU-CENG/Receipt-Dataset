# Turkish Receipt Dataset

## Overview
This repository provides two distinct datasets for research and development in Optical Character Recognition (OCR) and document analysis. The datasets contain Turkish receipt images collected from various sectors across Turkey, along with corresponding annotations.

## Dataset 1: Receipt Field Dataset
### Description
The first dataset consists of **1,068 receipt images** captured using various mobile devices under different conditions. These receipts exhibit significant variability in:
- Color, structure, font type, and font size
- Image quality, ncluding blurriness, skewness, and low resolution
- Physical distortions such as fading, bending, and tearing due to storage conditions

### Annotation Details
Two distinct labeling approaches were used:

  **1. Bounding Box Annotations**
   - Images were annotated with bounding boxes for **nine predefined categories**:
     - Company Name
     - Date
     - Time
     - ID
     - Item Name
     - Item Tax Rate
     - Item Amount
     - Total Tax
     - Total Amount
   - The dataset was split into **80% training** and **20% testing**.
   - Annotations are provided in a JSON file with three sections:
     - **Annotations**: Bounding box coordinates, class labels, area measurements, and segmentation curves.
     - **Categories**: Class names and their corresponding numerical identifiers.
     - **Images**: Metadata such as file name, width, and height.

2. **Key Information Annotations**
   - An annotation file was generated for each image, containing extracted key receipt details.

## Dataset 2: OCR Dataset
### Description
The second dataset is an **OCR dataset** created by extracting **21,315 image fragments** from receipt images, each paired with its corresponding transcript.
- The dataset is compatible with **Tesseract OCR**.
- It can be converted into other OCR training formats as needed.

## Usage
These datasets can be used for:
- OCR model training and evaluation
- Automated receipt processing
- Document image analysis research
- Improving OCR accuracy on real-world receipt images

## License
This project is licensed under the **MIT License**. See the [LICENSE](LICENSE) file for more details.

## Citation
Will be updated.

