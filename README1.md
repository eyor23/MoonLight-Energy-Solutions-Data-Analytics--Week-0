# This is the Week 0 Project for MoonLight Energy Solutions Data Analytics

Sure! Here’s a summary for your README notes based on the tasks and steps we've discussed:

---

# MoonLight Energy Solutions Data Analytics

## Description
This project focuses on analyzing energy data using various data visualization techniques.

## Project Structure
```
.
├── .github/              # GitHub configurations
├── .vscode/              # VSCode settings
├── data/                 # Dataset files
├── notebooks/            # Jupyter notebooks for analysis
│   └── README.md         # Overview of Jupyter notebooks
├── requirements.txt      # Python dependencies
├── scripts/              # Scripts for data processing
│   └── README.md         # Overview of scripts
├── src/                  # Source code for the project
├── tests/                # Test files for the project
└── app.py                # Streamlit dashboard application
```

## Getting Started

### Prerequisites
- Python 3.12.2
- Virtual environment

### Installation
1. Clone the repository:
   ```bash
   git clone <repository-url>
   cd MoonLight-Energy-Solutions-Data-Analytics
   ```

2. Create and activate a virtual environment:
   ```bash
   python -m venv venv
   .\venv\Scripts\activate  # On Windows
   # source venv/bin/activate  # On macOS/Linux
   ```

3. Install required packages:
   ```bash
   pip install -r requirements.txt
   ```
```

# Development Process
- **Data Cleaning**: Handled anomalies and missing values in the dataset, particularly in columns like Comments.
- **Analysis**: Conducted various analyses, including correlation and Z-score analyses.
- **Visualization**: Using histogram, line graph and others.

## Contributing
- Create a new branch for each feature or bug fix.
- Submit a pull request with a descriptive message summarizing your changes.

## License
This project is licensed under the MIT License.

## All the scripts are in /src folder.
## I analyze benin-malanville.csv and sierraleone-bumbuna.csv.