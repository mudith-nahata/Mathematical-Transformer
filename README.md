**Purpose of Mathematical Transformation**

--> The mathematical transformation used to transform the input features by applying the mathematical  Formulas in the input Columns.

--> It uses to convert the the data from Probability density function to the Normalization.

**Types of Mathematical Transformer**

--> We have three types of Mathematical Transformer
                1) Functional Transformer
                2) Power Transformer
                3) Quantile Transformer

**Functional Transformer**

--> Functional Transformer is a type of Mathematical Transformation.


--> By Using  Feature Transformation we can apply
                 1) Log Transformation
                 2) Reciprocal Transformation
                 3) sqr/sqrt

--> This Transformation used to improve the efficiency of Linear Machine Learning Model.

--> We can also make the Custom Transformers

--> Custom transformers are those where we can create our on transformation and can apply on the data.

**Log Transformation**

       --> Log Transformation is a technique of functional transformtion.
       
       --> Log Transformation cannot be used for the negative values on the input columns of the data.

       --> Log Transformation is applicable on right skewed data.

**Reciprocal Transformation**

         --> Reciprocal Transformation is a technique of functioal  transformation.
         
         --> This transformation use to convert the large values to the small and small values to the large(viceversa).
         
**Power Transformer**

          --> Power Transformer is a type of Mathematical Transformation.

          --> The Power Transformation can be done by the two techniques.
                                 1) Box-Cox Transformation
                                 2) Yeo-Jhonson
**Box-Cox Transformation**
--> Box-cox is used to convert the given distribution to the normal distribution.

--> It is called as Generat transformation technique

                Formula:

  ![image](https://github.com/mudith-nahata/Mathematical-Transformer/assets/96544398/fb2f6ae3-b918-43ec-8d70-9680a9d5c8fd)

--> The expoent here is variable called lambda.

--> The Value of lambda varies over the ranges of -5 to +5

--> while in the process of searching examine all the values of lambda.

--> We choose the optimal value to the variable.

--> We have two techniques in box-cox transformation.
              1) Max-likelihood
              2) Bayesian
--> Box-cox is only applicable for the numbers that are strictly greater than Zero.


**Yeo-Jhonson**

--> Yeo Jhonson transform used to improve the Box-Cox transformation.

--> This transformation can be used to zero and negative numbers.

                    Formula:-
                    
  ![image](https://github.com/mudith-nahata/Mathematical-Transformer/assets/96544398/91c8af3d-b2f8-47e4-9a69-fe11f82e721d)
  

