# PyTorch Workstation for Deep Learning

Welcome to the PyTorch Workstation! This repository is set up for experimenting with PyTorch and working on introductory deep learning projects. Below you'll find information on how to get started and an overview of the repository structure.

## 🚀 Features

- PyTorch setup for deep learning experiments
- Pre-configured environment for smooth project initiation
- Organized project templates and documentation

## 📂 Repository Structure

```
root/
├── data/             # Store your datasets here (added to .gitignore)
├── notebooks/        # Jupyter notebooks for exploration and experimentation
├── src/              # Python scripts for reusable modules and training logic
├── saved_models/     # Directory for saving trained models (added to .gitignore)
├── requirements.txt  # Python dependencies
├── .gitignore        # Git ignore file
└── README.md         # This readme file
```

## 🛠️ Setup Instructions

### 1. Clone the Repository
```bash
git clone <your-repository-url>
cd <repository-name>
```

### 2. Create and Activate a Python Virtual Environment
```bash
# Create a virtual environment
python -m venv venv

# Activate it
# On Windows:
venv\Scripts\activate
# On macOS/Linux:
source venv/bin/activate
```

### 3. Install Dependencies
```bash
pip install -r requirements.txt
```

### 4. Run a Notebook
```bash
# Launch Jupyter Notebook
jupyter notebook
```

## 🧪 Projects and Experiments

- **Project 1**: Linear Regression using PyTorch
- **Project 2**: Training a Neural Network for MNIST
- **Project 3**: Exploring CNNs with CIFAR-10

## 🩲 Cleaning Up
To remove temporary files and clean up the repository, run:
```bash
find . -type d -name '__pycache__' -exec rm -rf {} +
```

## 🤝 Contributing

Feel free to fork this repository and submit a pull request for improvements or additional project templates.

## 📜 License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.
