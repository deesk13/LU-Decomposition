# LU Decomposition 
## Name: Deva dharshini I
## RegisterNumber: 212223240026
## AIM:
To write a program to find the LU Decomposition of a matrix.

## Equipments Required:
1. Hardware – PCs
2. Anaconda – Python 3.7 Installation / Moodle-Code Runner

## Algorithm
1.Read the elements of augmented matrix into arrays a and b

2.Calculate elements of L and U

3.Print elements of L and U

4.Find V by solving LV = B by forward substitution

5.Find X by solving UX = V by backward substitution

6.Print Array X as the solution

## Program:
(i) To find the L and U matrix
```
/*
Program to find the L and U matrix.
Developed by: 
RegisterNumber: 
*/
```
Developed by: Deva dharshini I
RegisterNumber: 212223240026

from scipy.linalg import lu
a=eval(input())
P,L,U=lu(a)
print(L)
print(U)
(ii) To find the LU Decomposition of a matrix
```
/*
Program to find the LU Decomposition of a matrix.
Developed by: 
RegisterNumber: 
*/
```
## Program to find the L and U matrix.
Developed by: Deva dharshini I
RegisterNumber: 212223240026

from scipy.linalg import lu
a=eval(input())
P,L,U=lu(a)
print(L)
print(U)
## Output:
![lu decomposition]()
![Screenshot 2024-05-16 192657](https://github.com/deesk13/LU-Decomposition/assets/150927063/4219e401-e59b-44e9-8b2d-e2594f386166)
![Screenshot 2024-05-16 192707](https://github.com/deesk13/LU-Decomposition/assets/150927063/356845f9-2a35-4b93-befb-e8d483e50741)


## Result:
Thus the program to find the LU Decomposition of a matrix is written and verified using python programming.

