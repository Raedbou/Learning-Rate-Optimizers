# Learning-Rate-Optimizers
Code to submit for the Optimization for Machine Learning course at EPFL 
Spring 2021

Code:
Two models were inverstigated. Each model has a main file:

	1- Auxiliary Model: Deep Net with Auxiliary Loss 
	implemented in PyTorch
	2- CNN: Convolutionl Neural Network implemented in Keras.

All optimizers has been implements from the SCIKIT library.

In each main the routine consists of the following:

	i) data import
	ii) Data pre-processing and data truncation
	iii) Model and fitness function definition
	iv) Optimization routines
	v) Visualizing optimizer results
	vi) Reimporting whole data set without truncation
	vii) Training models with optimal parameters found by optimizers
	viii) Visulatizing learning curves of the optimized models.

Note: The optimization steps are computationally expensive, 
ecpecially the CG algorithm. 
Therefore it is advised to GPU resources if available (For the second model)
