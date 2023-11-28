# Project A4 - Motor Imagery Classification from EEG for Brain-Computer Interface

## Overview
This project focuses on classifying motor imagery (MI) data from electroencephalograms (EEG) for use in brain-computer interfaces (BCIs). The goal is to develop algorithms that accurately interpret EEG signals generated when individuals imagine physical movements, and use these signals to control external devices or interfaces.

## Getting Started

### Prerequisites
- **Git**: Ensure you have Git installed on your computer. Download and install from [Git's official website](https://git-scm.com/).
- **Python**: This project requires Python. We recommend using `pyenv` for managing Python versions.

### Setting up the Project

1. **Clone the Repository**
   ```bash
   git clone https://github.com/menglutao/Motor-imagery-classification-from-EEG-for-brain-computer-interface.git

### Navigate to the Project Directory
Navigate to the project directory with the following command:

    cd Motor-imagery-classification-from-EEG-for-brain-computer-interface

### Setting up Python Environment

#### Install `pyenv`
Follow the instructions on the [`pyenv` GitHub page](https://github.com/pyenv/pyenv) to install `pyenv`.

#### Install Python
Install the Python version needed for this project using `pyenv` with the following command:

    pyenv install 3.8

Currently we can set to version 3.8 but can be open for other versions as well.

#### Create a Virtual Environment
Create a new virtual environment for the project:

    pyenv virtualenv 3.8 my_env

#### Activate the Virtual Environment
Navigate to your project directory and set the local Python version to your virtual environment:
    
    cd path/to/your/project
    pyenv activate my_env

#### Install Dependencies
Install required Python packages using `pip` with the following command:

    pip install -r requirements.txt

#### Deactivate the Virtual Environment
When you're done working in the virtual environment, you can deactivate it:
    pyenv deactivate


### Working in a Different Branch

#### Create a New Branch
Create a new branch with the following command:

    git branch new_branch

Replace `new_branch` with a relevant name.

#### Switch to Your New Branch
Switch to your new branch with the following command:

    git checkout new_branch

### Basic Git Workflow

#### Check Current Branch
Check your current branch with the following command:

    git branch

#### Add Changes
Add changes with the following command:

    git add .

#### Commit Changes
Commit your changes with the following command:

    git commit -m "Your commit message"

#### Push Changes
Push changes to the repository with the following command:

    git push origin new_branch

#### Pull Latest Changes
Pull the latest changes from the main branch with the following command:

    git pull origin main

### Contributing
Discuss significant changes via issue, email, or other methods with the maintainers before contributing.
