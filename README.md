# Norm of a matrix
## Aim
To write a program to find the 1-norm, 2-norm and infinity norm of the matrix and display the result in two decimal places.
## Equipment’s required:
1.	Hardware – PCs
2.	Anaconda – Python 3.7 Installation / Moodle-Code Runner
## Algorithm:
1. Get the input matrix using np.array()   
2. Find the 2-norm of the matrix using np.linalg.norm()
3. Print the norm of the matrix in two decimal places.

## Program:

```
python
# Register No:22008879
# Developed By:Vikash S

# 1-Norm of a Matrix
import numpy as np
mat = np.array(eval(input()))
ans = np.linalg.norm(mat,1)
Norm_of_matrix = "{:.2f}".format(ans)
print(Norm_of_matrix)
```
```
# 2-Norm of a Matrix
import numpy as np
mat = np.array(eval(input()))
ans = np.linalg.norm(mat,2)
Norm_of_matrix = "{:.2f}".format(ans)
print(Norm_of_matrix)
```
```
# Infinity Norm of a Matrix
import numpy as np
mat = np.array(eval(input()))
ans = np.linalg.norm(mat,np.inf)
Norm_of_matrix = "{:.2f}".format(ans)
print(Norm_of_matrix)
```

## Output:
### 1-Norm of a Matrix

![Screenshot 2023-01-23 191553](https://user-images.githubusercontent.com/119433834/214055463-c2463498-1442-4988-a737-ad016d6f2765.png)



### 2-Norm of a Matrix


![Screenshot 2023-01-23 191616](https://user-images.githubusercontent.com/119433834/214055501-b30ccd64-96dd-4ffb-bd98-3cfc19488207.png)


### Infinity Norm of a Matrix

![Screenshot 2023-01-23 191532](https://user-images.githubusercontent.com/119433834/214055518-7c6a30b9-badc-484e-ae48-4d15a7552257.png)


## Result
Thus the program for 1-norm, 2-norm and Infinity norm of a matrix are written and verified.
