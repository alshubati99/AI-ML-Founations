# Machine Learning Foundations: Linear Algebra
# [*Course Certificate*](https://www.linkedin.com/learning/certificates/c6f96f9fb84d75e7d0df400f3d989bfc09ad4e3052bf6abc8f76c52c3cb39591)

### Introduction to Linear Algebra:
- Linear Algebra: 
    - Algebra != Linear Algebra.
    - Algebra: study of mathmatical sympoles.
    - Linear algebra: branch of linear algebra. 
- Applications of Linear Algebra in ML:
    1. Data set and Data files.
    2. Images and Photographs.
    3. Data Preparation.
    4. Linear Regression.
    5. Regularization. 
    6. Principal Component Analysis.
    7. Latent Semantic Analysis. 
    8. Recommender Systems.
    9. Deep Learning. 
### Vectors Basics:
- Vectors: An ordered list of numbers denoted by lowercases bolded roman letters => [1,2,3]
- Scalars: A number denoted by a lowercase letter => a,b.
- Dimentionality: horizontal by vertical. 
- Vector representations in python = List or arrays. 
    - vectorAsList = `[1,2,3]`
    - vectorASArray = `np.array([1,2,3])`
    - rowVector = `np.array([[1,2,3]])`
    - columnVector = `np.array([[1],[2],[3]])`
- Coordinate System:
    - like a chess board. 
    - Describes certain positions. 
    - Point. 
    - x-axes and y-axes (coordinates).
    - Unit vectors: ` (0,0), (1,0), (0,1) `

### Vector Projections and Basis: 
- Dot Product of Vectors: 
    - Widely  used in ML algorithms. 
    - It is commutative.
- Scalar and Vector Projection: 
    - Magnitude of a vector: has a formula. 
    - Very important in ML.
    - Vector projection. 
- Changing basis of vectors: 
    - Linearly independent of each other.
    - Aren't unique.
    - Span the whole space. 
- Linear independence and spanning set

### Introduction to Matrices:
- Matrices Introduction:
    - Matix: 2D array of numbers => rows and columns. 
    - can be of any size, has elements.
    - In python we arrays start from zero. 
- Types of matrices: 
    1. Rectangular: nbym matix
    2. Square: nbyn matrix
    3. Symmetric.
    4. Zero: all elements are zero. 
    5. Identity: identity (I) diagonal are all 1
    6. Diagonal: all diagonal have numbers.
    7. Triangular: square matrix but upper or lower trainglular. 
- Types of matrix transformation: 
    - Rotation.
    - Inversion. 
    - Rescaling
- Composition or combination of matrix transformation:
    - Very useful in ML.
    - Calculate it after calculating the product of matrices. A.B
    - Multiplication = dot product. 
### Gaussian Elimination:
- Solving linear equations using Gaussian Elimination:
    - used to solve linear equations by Gauss.
    - U can use column or row operations. 
    1. Create a coefficient matrix.
    2. Create constant matrix.
    3. Form augmented matrix by combining constant and coefficient matrix.
    4. Echelon form.
    5. Map the matrix back to equation.
    6. Substitute.
- Finding the inverse matrix: 
    - A.B=B.A=I
    - x = A^-1.B
- Inverse and Determinant: 
    - det(A) = 0 then matrix has no inverse.
    - det(A) = a.d - b.c for [[a,b],[c,d]]
### Matrices from Orthogonality to Gram-Schmidt Process:
- Matrices changing basis. 
- Transformation martix. 
    - Arise from matrix multiplication. 
- y = Ax 
- Orthogonal Matrix: 
    - Their dot product = 0. 
    - Denotated with Q. 
    - Transpose matrix: rows = columens and columens = rows. A^t.A = I
    - Save computational time. 
- Gram-Schmidt Process
### Eigenvalues and Eigenvectors:
- Eigenvalues and Eigenvectors: A.v = w
    - A = Trasformation matrix.
    - v = Input vector.
    - w = Output vector. 
    - AK = lamdaK. 
    - Used from recomendations systems. 
    - A.v - Lamda.v = 0 = (A-lamda.I)v = 0 => det(A-lamda.I) = 0.
- Changing to eigenbasis. 
- Google PageRank Algorithm:
    - The more important the page it the more likely it appears in other page links and thus it appears to searches fast. 
    - can be represented by stochastic or probability matrix. 
