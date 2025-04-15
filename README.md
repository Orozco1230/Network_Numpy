# Neural Network with NumPy
This project implements a simple neural network using NumPy for binary classification. Here you will find the steps to clone and run the project.

## Prerequisites
- Python 3.10 or higher
- Git
- A virtual environment (recommended)

## Clone the Repository
To clone the project, run the following command in your terminal:

```bash
git clone https://github.com/LorenzoBlas/Neural_network_numpy.git
```

## Install Dependencies
1. **Create a Virtual Environment:**
   ```bash
   python3 -m venv .venv
   ```

2. **Activate the Virtual Environment:**
   - On Linux/Mac:
     ```bash
     source .venv/bin/activate
     ```
   - On Windows:
     ```cmd
     .\.venv\Scripts\activate
     ```

3. **Install Dependencies:**
   Since this project uses only NumPy and Matplotlib, you can install them using pip:
   ```bash
   pip install numpy matplotlib scikit-learn
   ```

## Run the Project
To run the project, simply execute the `main.py` file:

```bash
python main.py
```

## Troubleshooting Common Issues

### 1. Dependency Installation Errors
- **Module not found:**
  - Ensure that the virtual environment is activated and that dependencies are installed correctly.
- **Permission issues:**
  - Try running the command with `sudo` if necessary.

### 2. Import Errors
- **Module not found (e.g., `numpy` or `matplotlib`):**
  - Ensure that the virtual environment is activated and that dependencies are installed correctly.

### 3. Git Issues
- **Error cloning or pushing changes:**
  - Check that your internet connection is stable and that there are no issues with your GitHub account.

### 4. Project Execution Errors
- **MSE calculation error:**
  - Verify that the shapes of `Y` and `output` are compatible for the MSE calculation.
- **Visualization issues:**
  - Ensure that Matplotlib is installed and configured correctly.

### 5. Unexpected Indentation Error
- **Indentation issue in Python files:**
  - Check that all lines are correctly indented. Python uses indentation to define code blocks.

### Solving Remote Repository Issues

If you encounter issues with the remote repository, ensure that the URL is correct and that you have the necessary permissions.

---

I hope this guide is helpful. If you have any questions or need further assistance, feel free to ask.

---

### Additional Notes

- Ensure that you are working in the correct directory and that the repository is properly configured.
- If you continue to experience issues, verify that there are no conflicts between different versions of packages or environment configurations.
