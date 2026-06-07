# EIGENVALUES-AND-EIGENVECTORS
## Aim:
To write a python program to find the Eigenvalues and Eigen Vectors
## Equipment’s required:
1. 	Hardware – PCs
2. 	Anaconda – Python 3.7 Installation / Moodle-Code Runner
## Algorithm:
1.Start.
2.Import the required library (numpy).
3.Define the square matrix A.
4.Compute eigenvalues and eigenvectors using the eigenvalue decomposition function:

## Program:
```
import os
os.environ["OPENBLAS_NUM_THREADS"]="1"
import numpy as np
a= np.array([[-2,2,-3],[2,1,-6],[-1,-2,0]])
values,vectors=np.linalg.eig(a)
print('Eigen values are {} and Eigen Vectors are {} '.format(values,vectors))
```

## Output:
<img width="1045" height="611" alt="{6ADBE58D-911C-4337-BBE1-6CA63B097988}" src="https://github.com/user-attachments/assets/a7df17d2-eb9e-4a22-9f32-348c8a2ebf25" />

## Result:
Thus the Eigenvalue and Eigenvector is successfully solved using python pro
