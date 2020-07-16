## T-LARS v1.0.0

# Tensor Least Angle Regression (T-LARS) for Sparse Representations of Multidimensional Signals

Sparse signal representations have gained much interest recently in both signal processing and statistical communities. Compared to Orthogonal Matching Pursuit (OMP) and Basis Pursuit that solve the L0 and L1 constrained sparse least-squares problems, respectively, Least Angle Regression (LARS) is a computationally efficient method to solve both problems for all critical values of the regularization parameter λ. However, all these methods are not suitable for solving large multidimensional sparse least-squares problems, as they would require extensive computational power and memory. An earlier generalization of OMP, known as Kronecker-OMP, was developed to solve the L0 problem for large multidimensional sparse least-squares problems. However, its memory usage and computation time increase fast with the number of problem dimensions and iterations. In this paper, we develop a generalization of LARS, Tensor Least Angle Regression (T-LARS) that could efficiently solve either large L0  or large L1 constrained multidimensional sparse least-squares problems (underdetermined or overdetermined) for all critical values of the regularization parameter λ, and which has lower computational complexity and lower memory usage than Kronecker-OMP. To demonstrate the validity and performance of our T-LARS algorithm, we used it to successfully obtain different sparse representations of two relatively large 3-D brain images, using fixed and learned separable over-complete dictionaries, by solving both L0 and L1 constrained sparse least-squares problems. Our different numerical experiments demonstrate that our T-LARS algorithm is significantly faster (46 - 70 times) than Kronecker-OMP, in obtaining K-sparse solutions for multilinear least-squares problems. However, the K-sparse solutions obtained using Kronecker-OMP always have a slightly lower residual error (1.55% - 2.25%) than ones obtained by T-LARS. Therefore, T-LARS could be an important tool for numerous multidimensional biomedical signal processing applications.

## Example

MATLAB Version: MATLAB R2017b and above

. / T-LARS/Example.m

## Authors
Ishan Wickramasingha,
Ahmed Elrewainy,
Michael Sobhy,
Sherif S. Sherif

Department of Electrical and Computer Engineering, University of Manitoba, 75 Chancellors Circle, Winnipeg, MB, R3T 5V6, Canada.
Biomedical Engineering Program, University of Manitoba, Winnipeg, MB, R3T 2N2, Canada.

## License

See [LICENSE](LICENSE).

## References

If you use this software in a scientific publication, you will have to cite following papers:

[Wickramasingha, Ishan, Ahmed Elrewainy, Michael Sobhy, and Sherif S. Sherif. " Tensor Least Angle Regression for Sparse Representations of Multi-dimensional Signals." Neural Computation, Volume 32, Issue 9, Sept 2020](https://www.mitpressjournals.org/forthcoming/neco) 

[Elrewainy, A., & Sherif, S. S. (2019). Kronecker least angle regression for unsupervised unmixing of hyperspectral imaging data. Signal, Image and Video Processing, 14(2), 359–367. https://doi.org/10.1007/s11760-019-01562-w](https://doi.org/10.1007/s11760-019-01562-w)



