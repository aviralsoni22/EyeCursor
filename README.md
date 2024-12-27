# EyeCursor
This project implements a hands-free cursor control system that uses real-time eye tracking to move the cursor based on eye movements. By leveraging OpenCV for video processing, Mediapipe for facial landmark detection, and PyAutoGUI for cursor manipulation, this solution provides an intuitive interface for hands-free computer interaction.

## Prerequisites
- Python 3.10
- Anaconda or Miniconda
- Git (optional, if you plan to clone via Git)
- Mediapipe
- OpenCV
- PyAutoGUI

## Setup Instructions

Follow these steps to set up the project locally on your machine.

### Step 1: Clone the Repository

Clone the repository using Git:

```bash
git clone https://github.com/aviralsoni22/EyeCursor.git
cd EyeCursor
```

### Step 2: Create a Virtual Environment
For Windows PowerShell, use the following command to create a virtual environment
```bash
conda create -p eye python==3.10 -y
```

### Step 3: Activate the virtual environment
```bash
conda activate eye
```

### Step 4: Install the required dependencies
```bash
pip install -r requirements.txt
```
### Step 5: Run the application
Navigate to the directory where crew.py is located and run the application:

```bash
python main.py
```

