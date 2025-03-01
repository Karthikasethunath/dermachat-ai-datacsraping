# Project: SkinChat AI: Conversational Health Monitoring Assistant 

## JIRA Ticket: [CLINICAL-717]

## Description
Develop an advanced chatbot for eczema management that integrates image recognition to analyze user-provided images and natural language processing to review relevant research papers. Leverage this analysis and stored user data to provide personalized recommendations for managing eczema.

## Structure
- **api/**: Contains API-related files and scripts.
- **config.py**: Configuration file for the project.
- **.env**: Environment variables.
- **main.py**: Main execution script.
- **models/**: Directory for storing trained models.
- **notebooks/**: Jupyter notebooks for exploration and prototyping.
- **requirements.txt**: List of dependencies for the project.
- **src/**: Source code for helpers, parsers, and other functions.
- **TODO.md**: List of tasks and to-dos.
- **venv/**: Virtual environment for the project.

## Setup Instructions
1. **Clone the repository**: `git clone [repository URL]`
2. **Navigate to the project directory**: `cd [project directory]`
3. **Create a virtual environment**: `python -m venv venv`
4. **Activate the virtual environment**:
   - On Windows: `venv\Scripts\activate`
   - On macOS/Linux: `source venv/bin/activate`
5. **Install dependencies**: `pip install -r requirements.txt`
6. **Run the project**: `python main.py`

## Usage
Provide instructions on how to use the scripts and notebooks in this project.

## Contributors
- [Pushpanjali] - [s3976146@student.rmit.edu.au]

## Notes
**About CLINICAL-718**
- eczemadatacollection.ipynb
- Several important steps have been achieved in the provided code to collect, preprocess, and prepare a skin condition image dataset for training a machine learning model.
- The dataset is collected, labeled, and preprocessed effectively, using augmentation and normalization techniques.
- The dataset is split into training, validation, and test sets to ensure proper model evaluation.
- A model training structure is set up, including a custom callback for dynamic learning rate adjustments and early stopping.
- Visualizations (sample images, training performance, and confusion matrix) are provided to help monitor and evaluate model progress.

