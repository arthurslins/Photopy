# Photopy

PhotoPy - Software for fitting photosynthesis  vs.  Irradiance curve in aquatic environment. 
Many nonlinear models equations have been developed to expresses the relationship of photosynthesis  vs. Irradiance .The parameters obtained from these equations such as Pmax 
(the maximum photosynthetic rate),α (light-limited initial slope of curve) Ek (light saturation parameter), Rd (dark respiration), Ec ( light compensation point ) 
and β ( photoinhibition index) are  useful tools to predict primary productivity, and  access to information photo-physiological  of the photosynthesis 
in response to environmental variable. PhotoPy is a  program for solving  the most commonly models employed describing photosynthesis  vs.  Irradiance curve 
in aquatic environment: exponential model (Webb et al. 1974); hyperbolic tangent model (Jassby and Platt, 1976); double exponential model  (Platt et al. 1980)  and Rational (Eilers and Peeters, 1988).

The software  using nonlinear,least-squares fitting based on the Levenberg–Marquardt algorithm, by the python package named scipy. All data were reported as the means and standard errors in the calculations. Goodness of fit of the mathematical models to experimental data was assessed using the adjusted coefficient of determination (R2), R-adjusted,Standard deviation of the residuals ( Syx) and Akaike information criterion (AICc) for  standard measure the best-fits of statistical models.When sample size (n) is small compared to the number of parameters (i.e., n/k < 40), the use of a second order, AICc(= AIC + 2k(k + 1)/(n − k − 1)) is recommended

Is recommended to read the program in the google colab environment cause it is already adjusted for it. You just need to execute all the cells to run the program.
For instructions of input data, you can input just the mean of the data or theirs duplicated and triplicated values.


Users are encouraged to report problems with the software and to suggest improvements or additions for future releases. 
 





