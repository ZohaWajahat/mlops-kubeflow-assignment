# mlops-kubeflow-assignment

## Objective
To design, implement, and manage a complete Machine Learning Operations (MLOps) pipeline for a simple machine learning project. This assignment involves data versioning, pipeline orchestration, model training, and continuous integration using industry-standard tools like DVC, Kubeflow Pipelines, and Jenkins.

## Tools Used:
• Git<br>
• GitHub<br>
• Docker<br>
• Python<br>
• DVC<br>
• Kubeflow Pipelines (on Minikube)<br>
• Kubernetes (minikube)<br>
• kubectl<br>
• Scikit-learn<br>
• Jenkins/GitHub Workflows<br>

## Task 1: Project Setup & DVC
The main objective of this task is to initialize the project structure and establish data versioning for reproducibility. <br>

### Steps to be done in Task 1
* [ ] Create public GitHub repository named `mlops-kubeflow-assignment`.
* [ ] Clone the repository and create the directory structure (`data/`, `src/`, `components/`).
* [ ] Create all required base files (`pipeline_components.py`, `model_training.py`, `pipeline.py`, `requirements.txt`, `Dockerfile`, `Jenkinsfile`).
* [ ] Choose a simple dataset (e.g., Boston housing) and place it in `data/`.
* [ ] Initialize DVC (`dvc init`).
* [ ] Set up DVC remote storage (e.g., local folder, GDrive, or S3).
* [ ] Track the dataset with DVC (`dvc add data/raw_data.csv`).
* [ ] Push the data to the DVC remote (`dvc push`).
* [ ] Commit DVC meta-files (`.dvc/` files and data pointers) to Git (`git commit` and `git push`).

### Task 1 Deliverable Requirements
The following specific items are required as proof of completion for Task 1:

• **Repository Screenshot:** A clear screenshot of your GitHub repository's main page showing the complete file structure created in this task.<br>
• **DVC Execution Screenshot:** A screenshot of your terminal/command line showing the successful execution of both the `dvc status` and `dvc push` commands. This proves the data is versioned and successfully mirrored to the remote storage.<br>
• **`requirements.txt` Content:** The raw text content of your `requirements.txt` file, listing the essential libraries.
