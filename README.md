# PhysioNet ECG Image Digitization

Welcome to FrogCode’s repository for the PhysioNet ECG Image Digitization competition. The goal of the competition is to develop robust methods to automatically digitize electrocardiogram (ECG) signals from images enabling conversion of ECG print-outs or scanned images into time-series waveform data.

<p align= "center">
<img src="https://www.kaggle.com/competitions/97984/images/header" width="450">
</p>

Our solution combines preprocessing of ECG images, deep learning segmentation/line-tracing, signal extraction, post-processing and quality control.

>[!warning] 🚧 Project Status: Early Development
> *This repository is currently under active development. Features, code structure, and documentation are subject to significant changes.*  
>
> *Contributions and feedback are welcome as the project evolves.*


## Getting Started

### Prerequisites

- Python 3.8+
- Virtual environment (recommended)
- Install dependencies:

```bash
git clone https://github.com/edserranoc/PhysioNet_ECG_Image_Digitization.git
cd PhysioNet_ECG_Image_Digitization

pip venv .venv
source .venv/bin/activate
pip install -r requirements.txt
```

### Data Download

- Join the competition at Kaggle.
- Download the provided dataset and place in `data/raw/`.
- Ensure data/processed/ is cleaned and ready for pipeline input.

## FrogCode Team Members

- Edison Serrano - PhD student in Applied Mathematics (University of Duisburg-Essen).
- Ezau Torres - Data Science Consultant (Algorithia).

## License

This project is licensed under the CC0-1.0 License – see the LICENSE file for details.
