# LLM Setup Instructions

## IMPORTANT!! - STILL BUILDING
This repository contains instructions for setting up an LLM (Large Language Model) from scratch base.

## Instructions

1. Create a Python virtual environment named `cuda` using the following command:
   ```
   python -m venv cuda
   ```

2. Activate the virtual environment by running the appropriate activation script:
   ```
   cuda\Scripts\activate
   ```

3. Install the required Python packages using pip:
   ```
   pip3 install matplotlib numpy pylzma ipykernel jupyter
   ```

4. Install PyTorch. Use the following command to install PyTorch with CUDA support (replace the URL with the appropriate version if needed):
   ```
   pip3 install torch --index-url https://download.pytorch.org/whl/cu118
   ```

5. Verify the Python version. Ensure that Python is version 3.9 or later by running:
   ```
   python --version
   ```
   
   Note: The Python version should be greater than 3.9 for compatibility.

That's it! You have successfully set up the environment for the LLM. You can now proceed with using this repository.
