## Environment
**Google Colab**:  
Ubuntu 18.04 with GPU enabled  
Python 3.6  
Pytorch 1.5 with Cuda 10.1  
Scikit-Learn 0.22.2  
Pandas 1.0.3
OpenCV 4.2  
NumPy 1.18.3  
Matplotlib 3.3.1

## Dataset and File Structure   
- The dataset can be obtained from: https://github.com/UCSD-AI4H/COVID-CT  
- The pre-traind model can be obtained from: https://drive.google.com/file/d/1-3SKFua_wFl2_aAQMIrj2FhowTX8B551/view     
- Please dowload and rearrange them according to the following file structure.  

```
├── Data
│   ├── CT_COVID [349 entries exceeds filelimit, not opening dir]
│   ├── CT_NonCOVID [397 entries exceeds filelimit, not opening dir]
│   └── Data-split
│       ├── COVID
│       │   ├── testCT_COVID.txt
│       │   ├── trainCT_COVID.txt
│       │   └── valCT_COVID.txt
│       └── NonCOVID
│           ├── testCT_NonCOVID.txt
│           ├── trainCT_NonCOVID.txt
│           └── valCT_NonCOVID.txt
├── model
│   └── COVIDNet_large_best_checkpoint.pth.tar
├── Project-COVID.ipynb
└── README.md
```

## How to Run Code
Open the given iPython Notebook, change the hyperparamters as indicated in the cells, then choose ```Run All``` to see the results at the last two cells.  