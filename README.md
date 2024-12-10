# DSC 210 Project: Comparing Image Compression Methods – Linear Algebra vs. Deep Learning

## Setup Instructions

Follow these steps to set up and run the Jupyter Notebook for this project.

### Step 1: Create a Conda Environment

First, create a new Conda environment with Python 3.10:

```sh
conda create -n dsc210 python=3.10
```


### Step 2: Activate the Conda Environment
Activate the newly created environment:

```sh
conda activate dsc210
```

**Note**: If you encounter the error CondaError: Run 'conda init' before 'conda activate', run the following command:

```sh
conda init
```
Then close your shell and reopen it to run `conda activate dsc210`

### 3: Install Required Packages
Install the required packages using `pip`:

```sh
pip install -r requirements.txt
```

**Warning**: Ensure that pip is from the activated environment by running:

```sh
which pip
```
The output should include something like `envs/dsc210/bin/pip`

### Step 4: Run the Jupyter Notebook

#### Using VS Code
It is recommended to use Visual Studio Code (VS Code) to run the Jupyter Notebook. Follow these steps:

1. Install the Python and Jupyter extensions in VS Code by Microsoft.
2. Open the notebook `Image_Compression.ipynb` in VS Code.
3. Ensure you are using the correct kernel:
    - Click the Select Kernel button on the top right.
    - Click on Python Environment.
    - Select dsc210.
4. Click on Run All Cells on the top left.

