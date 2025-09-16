1)Dataset:
SEWA - https://db.sewaproject.eu/
DFDC - https://www.kaggle.com/c/deepfake-detection-challenge/data

2)Software and Hardware requirements:
Hardware Specifications

    Processor: AMD Ryzen 7 5800H (8-core, 16-thread)

    RAM: 16 GB DDR4

    GPU: NVIDIA GeForce RTX 3050 (dedicated), AMD Radeon Graphics (integrated)

    OS: Windows 11

Software Specifications

    OS: Windows 11

    Programming: Python 3.10.11, Visual Studio Code (v1.98.2)

    ML Frameworks: TensorFlow 2.17.0, Keras, Scikit-learn

    Data Tools: NumPy, Pandas, Matplotlib

    Feature Extraction: OpenFace (visual AUs), OpenSMILE (audio MFCCs)

3)Instructions to execute

1. Core:  
   - Install the required datasets and OpenFace, OpenSMILE tools.  
   - Update the file paths accordingly before execution.  

2. UI:  
   - Open the UI folder in Visual Studio Code for easy navigation.  
   - Go to the backend folder:  
     cd backend  
     python app.py  
   - Go to the frontend folder:  
     cd frontend  
     npm install  
     npm run build  
     npm run dev  
   - Open the localhost link provided in the terminal, upload the video, and view the result.  
