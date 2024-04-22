

# MultiLinear regression

This project contains the implementation of multilinear regression from scratch. The project includes functions to compute the cost function and the gradient descent algorithm.

![Cost function](https://latex.codecogs.com/svg.image?\color{white}f_{(w_n,b)}(x_n)=w_{1}x_{1}+...+w_{n}x_{n}+b)

## Implementation Details

### 1. Cost Function

The cost function is a crucial component of machine learning algorithms. The cost function calculates the difference between the values predicted by the model and the actual values in the training data.



![Cost function](https://latex.codecogs.com/svg.image?\color{white}J(w_1,...,w_n,b)=\frac{1}{2m}\sum_{i=1}^{m}(f_{w_n,b}(x_n^{(i)})-y^{(i)})^{2})

- \( m \) is the number of training examples.
- \( X \) is the feature vector.
- \( y \) is the target variable.
- \( w \) is the slope vector.
- \( b \) is the intercept.

### 2. Gradient descent
Gradient descent is an optimization algorithm used to minimize the cost function by iteratively updating the model parameters (w,b). This process continues until the algorithm converges to the minimum of the cost function.

The formula for updating the parameters using gradient descent is:

![Cost function](https://latex.codecogs.com/svg.image?\color{white}w_j=w_j-a*\frac{1}{m}\sum_{i=1}^{m}(f_{w_n,b}(x_n^{(i)})-y^{(i)})*x^{(i)}_j)

![Cost function](https://latex.codecogs.com/svg.image?\color{white}b=b-a*\frac{1}{m}\sum_{i=1}^{m}(f_{w_n,b}(x_n^{(i)})-y^{(i)}))


- \( m \) is the number of training examples.
- \( X \) is the feature vector.
- \( y \) is the target variable.
- \( w \) is the slope vector.
- \( b \) is the intercept.
- \( a \) is the learning rate.