# TeamTestDrive_NRSCOfflineCodingChallenge2025
NRSCOfflineCodingChallenge2025

# 🌥️ Cloud and Shadow Segmentation from Satellite Imagery

This repository contains the implementation for segmenting cloud and shadow regions in satellite images using deep learning techniques. The work is part of a research and competition initiative and demonstrates an end-to-end pipeline from preprocessing to mask generation and visualization.

## 📌 Objective

To develop an efficient and lightweight dual-model pipeline capable of accurately identifying cloud and shadow regions from remote sensing data using simple convolutional architectures.

## 🧠 Methodology

* Two independent segmentation models (SimpleSegNet) were trained for cloud and shadow masks respectively.
* Input patches were normalized TOA reflectance data derived from raw DN bands (B2, B3, B4).
* Sun angle correction was incorporated to improve radiometric normalization.
* Binary masks were predicted per chunk and reassembled into georeferenced output masks.
* Performance was evaluated using metrics such as IoU and loss curves.

## 🛠️ Tools & Frameworks Used

* PyTorch (Deep Learning Framework)
* Rasterio, Fiona (Geospatial Data Processing)
* NumPy, Matplotlib, OpenCV (General Utilities)


## 📊 Sample Results

Loss curves and example output masks (cloud and shadow) are included in the repository. Evaluation includes visual inspection and percentage cover metrics.

## 🙏 Acknowledgements

We sincerely thank the organizers of the competition (NRSC) for the opportunity to participate in this meaningful challenge. It was a valuable experience to apply deep learning to a real-world remote sensing problem.

## 📬 Contact

For any queries or collaboration, please contact Kamalesh R. Email ->  kamalesh20200@gmail.com

---

