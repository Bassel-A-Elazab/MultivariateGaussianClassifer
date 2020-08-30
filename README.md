# MultivariateGaussianClassifer

# Overview 
   - I illustrated, and created Gaussian Distribution in one domension, And I explained how it worked,
      And more details in this link (https://github.com/Bassel-A-Elazab/GaussianClassiferFromScratchOneDimension)
   - I complete a gaussian but using multi-vairate/multi-dimension features, 
      And looks at different between it and univariate gaussian.
   - I used a gaussian in two dimensions to look how it works, And looks at different calculations from the one-dimension.
   - We can extend it for using more two dimenions, we created the basics and concepts.
   - Finally gaussian in two dimensions is called (bivariate-normal distribution).
   
   
# What is the multi-variate gaussian?
        
      - Is a vector in multiple normally distributed variables.
      - is a generalization of the one-dimensional (univariate) normal distribution to higher dimensions.
  
# How Multivariate Gaussian Classifer Works ?
    
   The concepts as discussed in one-dimensions (above link) with many different in equations.
   gaussian paramters are( mean, variance, and covariance matrix)
   
      - Step One:
         mean: 
         Calculates the mean for each variables,
         Then we have the mean vector consists of the means of each variable.
         mean = mean of [x1, x2, ..... , xn]
 
<img src="Pic/1.png" width="500">

      - Step Two: 
         Covariance Matrix: It's the hardest, and important part in algorithm.
            - Is a square matrix giving the covariance between each pair of elements of a given random vector.
            - In the matrix diagonal there are variances, i.e., the covariance of each element with itself. 
            - Is a measure of how much two random variables vary together.
            - Is symmetric.
<img src="Pic/2.png" width="500">

         How gets value of the above matrix?
            we divide it individually:
               First:
               Variance: is a measure of the variability or spread in a set of data.
               we calculate variance for variable one (x) and variable two (y) by using next equation.
               Note:
               X and Y are represents two features of sample data.
              
<img src="Pic/3.png" width="500">


              

         
