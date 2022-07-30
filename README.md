# Disease Modelling - Alzheimer’s Disease
![alt text](Images/senior_woman_adult_daughter_unrecognizable_50.jpeg)

Alzheimer's disease is a progressive disorder in which dementia symptoms gradually worsen over time.Even though current Alzheimer's treatments cannot reverse the disease, they can temporarily slow the onset of dementia symptoms and enhance quality of life for those with Alzheimer's. Detecting Alzheimer's disease as soon as it begins is essential, as there is no way to reverse irreversible changes in the brain after they have occurred. Image processing plays a critical role in this process.

## Software
Jupyter Notebook (Python 3.9) - Installation details can be found [here](https://docs.jupyter.org/en/latest/install/notebook-classic.html#:~:text=Jupyter%20installation%20requires%20Python%203.3,%2C%20pip%2C%20instead%20of%20Anaconda.)

## Dependencies

Following libraries needs to be installed using the command ``` pip install "library name" ```

- numpy
- matplotlib
- seaborn
- os
- math
- shutil
- random
- squarify
- tensorflow
- keras
- sklearn
- zipfile

## Dataset

The MRI scans dataset (**MRIData.zip**) is archived and uploaded into the repository.The folder must be downloaded from repository and uploaded into the working diroctory of the note book. It is essential that user upload the folder without extracting it, since extracting is covered in the code.

The Dataset consist of four classes:

Mild Demented            |  Moderate Demented           |  Non Demented        |  Very Mild Demented
:-------------------------:|:-------------------------: |:-------------------------: |:-------------------------:
![alt text](Images/mildDem6.jpg)  |  ![alt text](Images/moderateDem10.jpg) |![alt text](Images/nonDem10.jpg) | ![alt text](Images/verymildDem9.jpg)



## Execution of code

Upload the **Alzheimer’s Multi Class Prediction.ipynb** into Jupyter notebook.

User can run all the code at once by following the below path :
- Cell > Run All

## Prediction and Result

To predict the stage of Alzheimer's disease, user must provide the path of the intended MRI scan in the code as shown in the below snippet of the chunk. The MRI scan can be either the droped out image (not a part modelling or testing process) from original directory or any desired MRI scan.

![alt text](Images/Images/Capture.JPG)
