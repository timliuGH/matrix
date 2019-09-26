Shell script for matrix manipulation  

Matrix must be tab-delimited  

Available commands:  

$ matrix dims [MATRIX]  
- takes an MxN matrix from MATRIX file or stdin and outputs dimensions in the format "ROWS COLS"  

$ matrix transpose [MATRIX]  
- takes an MxN matrix from MATRIX file or stdin and outputs an NxM matrix with elements flipped across the diagonal

$ matrix mean [MATRIX]  
- takes an MxN matrix from MATRIX file or stdin and outputs a 1xN row with each element representing the mean of that column in the original MxN matrix

$ matrix add [LEFT_MATRIX] [RIGHT_MATRIX]  
- takes two MxN matrices from two files and outputs an MxN matrix resulting from adding the elements from the input matrices at corresponding positions

$ matrix multiply [LEFT_MATRIX] [RIGHT_MATRIX]
- takes an MxN matrix and an NxP matrix and outputs an MxP matrix resulting from
performing matrix multiplication
