# Sound Classification

This repository contains notebooks and code for working with audio embeddings and sound classification.

## Installation

1. Create a Python virtual environment:
   ```bash
   python -m venv .venv
   source .venv/bin/activate  # On Windows: .venv\Scripts\activate
   ```

2. Install the required dependencies:
   ```bash
   pip install -r requirements.txt
   ```

3. Download the required data:
   - Download the file `amplab_machine_listening_module_data.zip` from the [shared folder](https://drive.google.com/drive/folders/1FHEmzEXgBV1CCAWo_F3KDpw9QM5ecuZf?usp=sharing)
   - Place it in the repository root and unzip it
   - Make sure the uncompressed folder is named `amplab_machine_listening_module_data`

## Running the Notebook

1. Start Jupyter:
   ```bash
   jupyter notebook
   ```

2. Open the notebook `AMPLAB Module 4 - Embedding extractor.ipynb`

3. If you encounter package compatibility issues, run the cell with the setup script and restart the kernel.

## Troubleshooting

If you encounter issues with dependencies:

1. Make sure you're using Python 3.9+ and have created a virtual environment
2. Run the setup script included in the notebook
3. Restart the kernel after installing dependencies
4. If problems persist, try uninstalling problematic packages and reinstalling them one by one
