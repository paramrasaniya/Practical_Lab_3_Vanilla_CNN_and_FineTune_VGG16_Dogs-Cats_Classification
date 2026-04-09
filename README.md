# Dogs vs Cats Fine-Tuning Assignment

## Project Overview
This project is a binary image classification assignment for **Dogs vs Cats**.  
The notebook covers:

- environment check
- dataset verification
- exploratory data analysis (EDA)
- train / validation / test split
- image generators
- a **Custom CNN**
- a **fine-tuned VGG16**
- model comparison
- confusion matrix, precision, recall, F1-score
- precision-recall curve
- failed prediction analysis
- final conclusions

## Project Folder Structure
Keep your project folder like this:

```text
PRACTICAL_LAB_3/
│
├── cats_dogs_5000/
├── venv311/
├── .gitignore
├── Dogs_vs_Cats_FineTuning_Assignment.ipynb
├── README.md
├── requirements.txt
├──
```

## Important Setup Note
The folder **`cats_dogs_5000`** must be kept in the **same folder** as the notebook file:

- `Dogs_vs_Cats_FineTuning_Assignment.ipynb`

That way, the notebook can correctly read the dataset.

## Dataset
This assignment uses the **Dogs vs Cats** image dataset with **5000 images total**:

- **2500 cat images**
- **2500 dog images**

## Files in This Project

### `Dogs_vs_Cats_FineTuning_Assignment.ipynb`
Main notebook containing all required steps for the assignment.

### `cats_dogs_5000/`
Extracted dataset folder used by the notebook.

### `requirements.txt`
Contains the Python packages needed to run the notebook.

### `.gitignore`
Prevents unnecessary files such as virtual environment files, checkpoints, and trained model files from being pushed to GitHub.

### `.keras` files
These are saved best-model files created after training:

- `best_custom_cnn.keras`
- `best_vgg16_phase1.keras`
- `best_vgg16_finetuned.keras`

These are useful for testing and loading the best versions of the trained models.  
Extra: Once the code run from top to bottom, these keras file will appear.

## Environment Setup in VS Code

### 1. Open the project folder
Open the full project folder in VS Code:

```powershell
PRACTICAL_LAB_3
```

### 2. Activate the Python 3.11 virtual environment
In PowerShell:

```powershell
.\venv311\Scripts\Activate.ps1
```

### 3. Install the required packages
```powershell
pip install -r requirements.txt
```

### 4. Select the correct kernel in VS Code
Choose the interpreter from:

```text
venv311
```

## How to Run the Notebook
Run the notebook from **top to bottom**.

Recommended order:

1. Environment check
2. Dataset verification
3. EDA
4. Data split
5. Data generators
6. Custom CNN training
7. VGG16 fine-tuning
8. Model evaluation
9. Failed prediction analysis
10. Final conclusions

## Main Models Used

### 1. Custom CNN
A convolutional neural network built from scratch for classifying cats and dogs.

### 2. VGG16 Fine-Tuning
A transfer learning model using **VGG16** pretrained weights, followed by fine-tuning for better classification performance.

## Output Files
After training, the notebook may generate these files:

- `best_custom_cnn.keras`
- `best_vgg16_phase1.keras`
- `best_vgg16_finetuned.keras`

These files store the best saved versions of the trained models.

## Author
**Name: Param Rasaniya,      Student ID: 9086095**
