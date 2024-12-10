# DSC 210 Project: Comparing Image Compression Methods – Linear Algebra vs. Deep Learning

## Setup Instructions

Follow these steps to set up and run the Jupyter Notebook for this project.

### Step 1: Download Project Code

First, click on Code --> Download ZIP from this page of the GitHub repository.

Next, open this zipped file and move this folder to a desired location on your device.

Then, open a new terminal window and navigate into this DSC_210_Project-main folder.

### Step 2: Create a Conda Environment

First, create a new Conda environment with Python 3.10:

```sh
conda create -n dsc210 python=3.10
```


### Step 3: Activate the Conda Environment
Activate the newly created environment:

```sh
conda activate dsc210
```

**Note**: If you encounter the error CondaError: Run 'conda init' before 'conda activate', run the following command:

```sh
conda init
```
Then close your shell and reopen it (again navigate into this DSC_210_Project-main folder) to run `conda activate dsc210`

### 4: Install Required Packages
Install the required packages using `pip`:

```sh
pip install -r requirements.txt
```

**Warning**: Ensure that pip is from the activated environment by running:

```sh
which pip
```
The output should include something like `envs/dsc210/bin/pip`

### Step 5: Run the Jupyter Notebook

#### Using VS Code
It is recommended to use Visual Studio Code (VS Code) to run the Jupyter Notebook. Follow these steps:

1. Install the `Python` and `Jupyter` extensions in VS Code by Microsoft.
2. Open the notebook `Image_Compression.ipynb` in VS Code.
3. Ensure you are using the correct kernel:
    - Click the `Select Kernel` button on the top right.
    - Click on `Python Environment`. Note: If you do not see `Python Environment` and instead see an option to install the `Python` and `Jupyter` extensions, please do so.
    - Select `dsc210`.
    - If a pop up appears to install the `ipykernel`, please do so and continue.
4. Click on Run All Cells on the top left.

