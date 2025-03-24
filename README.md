# IntelImageClassification

## Overview
This project focuses on building and evaluating image classification models using the Intel Image Classification dataset from Kaggle. The dataset contains images categorized into six classes: buildings, forests, glaciers, mountains, seas, and streets.

## Project Structure
```plaintext
IntelImageClassification/
├── data/                # Dataset downloaded from Kaggle
├── src/                 # Python scripts and notebooks
│   ├── download_data.py # Script to download and extract data
│   └── [Other scripts]
├── .gitignore
├── requirements.txt
├── kaggle.json          # Kaggle API credentials (not tracked by Git)
└── README.md
```

## Setup Instructions

**1. Clone the Repository**
```
git clone https://github.com/BikinGhimire/IntelImageClassification.git
cd IntelImageClassification
```

**2. Create and Activate Virtual Environment**
```
python3 -m venv .venv
source .venv/bin/activate
```

**3. Install Dependencies**
```
pip install -r requirements.txt
```

**4. Kaggle API Setup**
- Download your Kaggle API token (kaggle.json) from your Kaggle account settings.
- Place the kaggle.json file in the project root directory.

**5. Download Dataset**
```
python src/download_data.py
```

## Technologies
- Python
- Numpy/Pandas
- PyTorch

## License
This project is unlicensed.

---
© 2024 Bikin Ghimire. All rights reserved.
