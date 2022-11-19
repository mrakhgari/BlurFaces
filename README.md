# BlurFaces
Face blur methods are used to develop privacy-preserving deep learning and computer vision applications.  


Practical applications of face blurring and anonymization include:
- Privacy and identity protection in public/private areas
- Protecting children online (i.e., blur faces of minors in uploaded photos)
- Photo journalism and news reporting (e.g., blur faces of people who did not sign a waiver form)
- Dataset curation and distribution (e.g., anonymize individuals in dataset)
- … and more [source](https://pyimagesearch.com/2020/04/06/blur-and-anonymize-faces-with-opencv-and-python/)!

In this project, we used [open-cv](https://github.com/opencv/opencv) as main library. The library provides functions for loading neural models. One of the successful models for face recognition is the [Yunet](https://github.com/geaxgx/depthai_yunet) model, to load this model and use it, it is necessary to give the `.onnx` file of this model to Open-cv, and this file was put in the [model folder](/model). 


## Requirements 
You need python 3.6 or upper versions to run the codes. The other requirements are listed in the first cell of the code and you can install them by running the cell. 



