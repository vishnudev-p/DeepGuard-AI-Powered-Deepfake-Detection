# DeepGuard-AI-Powered-Deepfake-Detection
## Requirements:

**Note :** Nvidia GPU is mandatory to run the application.
- CUDA version >= 10.0 for GPU
- GPU Compute Capability > 3.0 


```
Python >= v3.6
Django >= v3.0
```

## Directory Structure

- ml_app -> Directory containing code in views.py file
- project_settings -> Contains Django settings and files to run in production
- static -> Contains all css, js and json files (for face-api)
- templates -> Template files for HTML


# Running application locally on your machine

### Prerequisite
1. Copy your trained model to the models folder.
   - You can download our trained models from the [Google Drive](https://drive.google.com/drive/folders/1UX8jXUXyEjhLLZ38tcgOwGsZ6XFSLDJ-?usp=sharing) .

#### Step 1 : Clone the repo and Navigate to Django Application

`git clone https://github.com/abhijitjadhav1998/Deepfake_detection_using_deep_learning.git`

#### Step 2: Create virtualenv (optional)

`python -m venv venv`

#### Step 3: Activate virtualenv (optional)

`venv\Scripts\activate`

#### Step 4: Install requirements

`pip install -r requirements.txt`

### Step 5: Run project

`python manage.py runserver`

