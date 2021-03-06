**Only Mathematical libraries and packages**

* [CRYPTOGRAPHY](#cryptography)
   * [Cryptocurrency](#cryptocurrency)
* [MATH](#math)
   * [Algebra](#algebra)
      + [Orthogonal Polynomials](#orthogonal-polynomials) 
      + [Symbolic Computation](#symbolic-computation)
   * [Algebraic Geometry](#algebraic-geometry)
   * [Calculus](#calculus)
      + [Ordinary Differential Equations](#ordinary-differential-equations)
         + [Org-JuliaLang](#org-julialang)
         + [Org-JuliaDiff](#org-juliadiff)
   * [Discrete Math](#discrete-math)
   * [Geometry](#geometry)
         + [Org-JuliaGeometry](#juliageometry)
   * [Numerical Analysis](#numerical-analysis)
      + [Numerical Linear Algebra](#numerical-linear-algebra)
   * [Special Functions](#special-functions)   
* [PUZZLES](#puzzles)


----

# CRYPTOGRAPHY
- [BlockCipherSelfStudy.jl](https://github.com/andrewcooke/BlockCipherSelfStudy.jl) :: Blocks, and RC5.
- [Crypto.jl](https://github.com/danielsuo/Crypto.jl) :: A library that wraps OpenSSL, but also has pure Julia implementations for reference.
- [Hashlib.jl](https://github.com/samgre/Hashlib.jl) :: SHA1 implementation for Julia.
- [Nettle.jl](https://github.com/staticfloat/Nettle.jl) :: is a simple wrapper around libnettle, a cryptographic library.
- [OpenSSL.jl](https://github.com/dirk/OpenSSL.jl) :: WIP OpenSSL bindings for Julia.
- [OpenSSLCrypto.jl](https://github.com/amitmurthy/OpenSSLCrypto.jl) :: Julia interface to the crypto API of openssl.
- [RNGTest.jl](https://github.com/andreasnoackjensen/RNGTest.jl) :: A package that is a Julia interface to the test suite TestU01 of Pierre l'Ecuyer to test random numbers.
- [RNGTesting](https://github.com/johnmyleswhite/RNGTesting) :: Scripts for testing Julia's RNG's.
- [SHA.jl](https://github.com/staticfloat/SHA.jl) :: a performant, 100% native-julia SHA2-{224,256,384,512} implementation.
- [Sha256.jl](https://github.com/mad4alcohol/Sha256.jl) :: [Sha256 hash algorithm for Julia.
- [Stupid.jl](https://github.com/andrewcooke/Stupid.jl) :: Analysis of an 8 bit version of the cipher at http://news.quelsolaar.com/#comments101.

### Cryptocurrency 
- Bit[Coin.jl](https://github.com/danielsuo/Coin.jl) :: A library for working with Bitcoin written in Julia.

----

# MATH 
- DOCS : [Mathematical Operations](http://docs.julialang.org/en/release-0.2/manual/mathematical-operations/) and a [list of all overloadable operators](https://github.com/JuliaLang/julia/blob/master/src/julia-parser.scm#L1-L19) in Julia.
- [Accelereval.jl](https://github.com/lindahua/Accelereval.jl) :: A Julia framework for accelerated re-compiled evaluation of numerical functions that ensures faster computation.
- [AppleAccelerate.jl](https://github.com/simonbyrne/AppleAccelerate.jl) :: Julia interface to OS X's Accelerate framework.
- [Bijections.jl](https://github.com/scheinerman/Bijections.jl) :: Bijection datatype for Julia.
- [Church.jl](https://github.com/LaurenceA/Church.jl) :: helps you perform inference in complex, and simple, probabilistic models.
- [Cartesian.jl](https://github.com/timholy/Cartesian.jl) :: Fast multidimensional algorithms.
- [Calculus.jl](https://github.com/johnmyleswhite/Calculus.jl) :: Calculus package.
- [Calculus2.jl](https://github.com/johnmyleswhite/Calculus2.jl) :: A draft of a new interface for the Calculus package.
- [Catalan.jl](https://github.com/andrioni/Catalan.jl) :: a combinatorics library for Julia.
- [CRF.jl](https://github.com/slyrz/CRF.jl) :: Conditional Random Fields in Julia.
- [CellularAutomata.jl](https://github.com/natj/CellularAutomata.jl) :: Cellular Automata package.
- [ContinuedFractions.jl](https://github.com/johnmyleswhite/ContinuedFractions.jl) :: Types and functions for working with continued fractions in Julia.
- [Devectorize.jl](https://github.com/lindahua/Devectorize.jl) :: A Julia framework for delayed expression evaluation.
- [DoubleDouble.jl](https://github.com/simonbyrne/DoubleDouble.jl) :: A Julia package for performing extended-precision arithmetic using pairs of floating-point numbers.
- [Dierckx.jl](https://github.com/kbarbary/Dierckx.jl ):: A Julia wrapper for the Dierckx Fortran library for spline fitting.
- [Entropy.jl](https://github.com/grero/Entropy.jl) :: This package contains functionality for computing binless estimates of entropy from discrete and continuous samples for continuous distributions.
- [FastAnonymous.jl](https://github.com/timholy/FastAnonymous.jl) :: Fast "anonymous functions" for Julia.
- [FastGauss.jl](https://github.com/ajt60gaibb/FastGauss.jl) :: Computes Gauss quadrature rules to 16-digit precision (so far Legendre, Jacobi, Lobatto, Radau).
- [FloorLayout.jl](https://github.com/joehuchette/FloorLayout.jl) ::  Framework and various drivers for floor layout formulation analysis.
- [GSL.jl](https://github.com/jiahao/GSL.jl) :: Julia interface to the GNU Scientific Library - GSL.
- [Glmnet.jl](https://github.com/simonster/Glmnet.jl) :: Julia wrapper for fitting Lasso/ElasticNet GLM models using glmnet.
- [Hexagons.jl](https://github.com/dcjones/Hexagons.jl) :: Useful tools for working with hexagonal grids.
- [MPFR.jl](https://github.com/andrioni/MPFR.jl) :: A Julia package for the GNU MPFR library.
- [Multicombinations.jl](https://github.com/jlep/Multicombinations.jl) :: An iterator for k-combinations with repetitions, k-multicombinations, k-multisubsets.
- [NaNMath.jl](https://github.com/mlubin/NaNMath.jl) :: Julia math built-ins which return NaN.
- [NumericExtensions.jl](https://github.com/lindahua/NumericExtensions.jl) :: Julia extensions to provide high performance computational support for fast vectorized computation.
   * _DOCS_:: are available at [numericextensionsjl.readthedocs.org](http://numericextensionsjl.readthedocs.org/en/latest/)
- [NLreg.jl](https://github.com/dmbates/NLreg.jl) :: Nonlinear regression in Julia.
- [NLsolve.jl](https://github.com/EconForge/NLsolve.jl) :: Julia solvers for systems of nonlinear equations.
- [nrmm.jl](https://github.com/juho-lee/nrmm.jl) :: Posterior inference algorithms for normalized random measure mixtures.
- [NumericFuns.jl](https://github.com/lindahua/NumericFuns.jl) :: Math functions and functors for numerical computations.
- [NumericalShadow.jl](https://github.com/pgawron/NumericalShadow.jl) :: Library to calculate numerical shadows in Julia language.
- [Quadrature.jl](https://github.com/kofron/Quadrature.jl) : Gauss quadrature in Base.
- [Quat.jl](https://github.com/forio/Quat.jl) :: Quaternions, octonions and dual-quaternions.
- [quaternion.jl](https://github.com/peakbook/quaternion.jl) :: Quaternion for Julia Language.
- [Shannon.jl](https://github.com/kzahedi/Shannon.jl) :: Entropy, Mutual Information, KL-Divergence related to Shannon's information theory and functions to binarize data.
- [SimilarityMetrics.jl](https://github.com/johnmyleswhite/SimilarityMetrics.jl) :: Standard similarity metrics in Julia.
- [Smolyak](https://github.com/EconForge/Smolyak) :: Efficient implementations of Smolyak's algorithm for function approxmation in Python and Julia.
- [Sobol.jl](https://github.com/stevengj/Sobol.jl) :: is a generation of Sobol low-discrepancy sequence (LDS) implementation, that generates "quasi-random" sequences of points in N dimensions which are equally distributed over an N-dimensional hypercube.
- [SurfaceMesh.jl](https://github.com/michelk/SurfaceMesh.jl) :: is a Finite element surface mesh manipulation library to work with polygon-surface-meshes.
- [SymPy.jl](https://github.com/jverzani/SymPy.jl) :: Julia interface to SymPy via PyCall.
- [TrussPlotter.jl](https://github.com/sjkelly/TrussPlotter.jl) :: This is a package to plot trusses for finite element results.
- [TSne.jl](https://github.com/lejon/TSne.jl) :: Julia port of L.J.P. van der Maaten and G.E. Hinton's T-SNE visualisation technique. Read about the [t-Distributed Stochastic Neighbor Embedding](http://homepage.tudelft.nl/19j49/t-SNE.html)
- [Uncertain.jl](https://github.com/rephorm/Uncertain.jl) :: Uncertain quantities and error propagation for the Julia language.
- [univariate__opt.jl](https://github.com/matthewclegg/univariate_opt.jl) :: Univariate optimization and root-finding code for Julia and its [newly maintained fork](https://github.com/EconForge/univariate_opt.jl).
- [utils.jl](https://github.com/juho-lee/utils.jl) :: basic utilities needed for scientific coding with julia.
- [ValidatedNumerics.jl](https://github.com/dpsanders/ValidatedNumerics.jl) :: Rigorous floating-point calculations via interval arithmetic.

----

## Algebra
- [algebra](https://github.com/alrahimi/algebra/) :: A hierarchy of abstract algebraic structures in Julia.
- [AMVW.jl](https://github.com/andreasnoackjensen/AMVW.jl) :: Fast and backward stable computation of roots of polynomials in Julia
- [BitCircuits.jl](https://github.com/um-tech-evolution/BitCircuits.jl) :: Boolean circuit evaluation using bitwise operations.
- [CLBLAS.jl](https://github.com/ekobir/CLBLAS.jl) :: CLBLAS integration for Julia.
- [Cuhre.jl](https://github.com/tflovorn/Cuhre.jl) :: Simplified Julia interface to Cuhre integration routine.
- [DeepConvert.jl](https://github.com/jlapeyre/DeepConvert.jl) :: This package provides convenient literal construction of values of large data types.
- [Elliptic.jl](https://github.com/nolta/Elliptic.jl) :: Elliptic integral and Jacobi elliptic special functions.
- [ErrorFreeTransforms.jl](https://github.com/dsiem/ErrorFreeTransforms.jl) :: Map rounding errors in floating point arithmetic with error-free transformations (EFT).
- [MultiPoly.jl](https://github.com/daviddelaat/MultiPoly.jl) :: Sparse multivariate polynomials in Julia.
- [OrderedCollections.jl](https://github.com/kmsquire/OrderedCollections.jl) :: OrderedDict and OrderedSet for Julia.
- [SemiringAlgebra.jl](https://github.com/ViralBShah/SemiringAlgebra.jl) :: Semiring Algebra.


### Orthogonal Polynomials
- [ChebyshevApprox](https://github.com/RJDennis/ChebyshevApprox) :: Julia code to approximate continuous functions using Chebyshev polynomials.
- [Jacobi.jl](https://github.com/pjabardo/Jacobi.jl) :: Jacobi polynomials and Gauss quadrature related functions.
- [Orthopolys.jl](https://github.com/daviddelaat/Orthopolys.jl) :: Orthogonal Polynomials - Currently supports Jacobi polyonomials, Gegenbauer polynomials, Hermite polynomials.
- [Polynomial.jl](https://github.com/vtjnash/Polynomial.jl) :: Polynomial manipulations and [PolyExt.jl](https://gist.github.com/mathpup/8514578), an extension of Polynomial.jl to support polynomial division, with handy conversions and promotion rules. 
- [InterPol.jl](https://github.com/pwl/InterPol.jl) :: Interpolating polynomial for Julia.

### [Symbolic Computation](https://en.wikipedia.org/wiki/Symbolic_computation)
+ [SJulia](https://github.com/jlapeyre/SJulia) :: A partial implementation of a language for symbolic computation, based on pattern matching and an evaluation sequence closely modeled on Mathematica.
+ [Symbolic.jl](https://github.com/scidom/Symbolic.jl) :: Symbolic computations and computer algebra in Julia.

----

## [Algebraic Geometry](http://en.wikipedia.org/wiki/Category:Algebraic_geometry)
- [CSoM.jl](https://github.com/goedman/CSoM.jl) :: Investigate Julia version of "Programming the FEM" by I M Smith, D V Griffiths.
- [EllipticCurves.jl](https://github.com/wwilson/EllipticCurves.jl) :: Elliptic Curves in Julia.
- [khypot.jl](https://github.com/intdxdt/khypot.jl) :: k dimensional hypotenuse.
- [FEM.jl](https://github.com/pjabardo/FEM.jl) :: Simple finite elements in Julia.
- [ols.jl](https://github.com/forio/ols.jl) :: Julia type for multiple (multivariate) regression using OLS - Performs least squared regression on linear equations of multiple independent variables.
- [SurfaceMesh.jl](https://github.com/michelk/SurfaceMesh.jl) :: Finite element surface mesh manipulation library.
- [VoronoiDelaunay.jl](https://github.com/skariel/VoronoiDelaunay.jl) :: Fast robust Voronoi and Delaunay triangulations, using GeometricalPredicates.jl package.

----

## Calculus
- [AutoDiff.jl](https://github.com/scidom/AutoDiff.jl) :: Juila package for performing automatic differentiation.
- [ApproxFun](https://github.com/dlfivefifty/ApproxFun) :: Julia IFun Implementation is a package for approximating functions. It currently supports intervals, the real line, periodic intervals and the unit circle. It is heavily influenced by the Matlab package chebfun and the Mathematica package RHPackage.
- [FeynmanKacSpde.jl](https://github.com/scidom/FeynmanKacSpde.jl) :: Feynman-Kac SPDE Inference.
- [HyperNumbers.jl](https://github.com/goedman/HyperNumbers.jl) :: Julia implementation of HyperNumbers.
- [Lifts.jl](https://github.com/scheinerman/Lifts.jl) :: Linear fractional transformations in Julia. 
- [pdetools.jl](https://github.com/GaZ3ll3/pdetools.jl) :: Toolbox for solving PDEs.
- [PowerSeries.jl](https://github.com/jwmerrill/PowerSeries.jl) :: Truncated Power Series for Julia, which exports a Series type that represents a truncated power series by its coefficients. You can do arithmetic on Series and apply functions to series just as you would Real or Complex numbers.
   * _Power Series Blog_::
   * Jason Merrill's blog series highlighting the basic aspects of floating point arithmetic with examples in Julia - [The first one, on bisecting floating point numbers](http://squishythinking.com/2014/02/22/bisecting-floats/)
- [PolyMath.jl](https://github.com/cfbaptista/PolyMath.jl) :: a package for polynomial arithmetic, calculus, interpolation and quadrature algorithms implemented in Julia.
- [RAD.jl](https://github.com/adamkapor/RAD.jl) :: package defines a macro, @autodiff, for reverse-mode automatic differentiation.
- [RDE.jl](https://github.com/scidom/RDE.jl) :: Simulation and Bayesian Inference for Rough Differential Equations (RDEs).
- [ReverseDiffOverload.jl](https://github.com/LaurenceA/ReverseDiffOverload.jl) :: Reverse mode differentiation for pre-defined functions.
- [ReverseDiffSparse.jl](https://github.com/mlubin/ReverseDiffSparse.jl) :: Hessian algorithmic differentiation to compute hessian sparsity pattern.
- [RiemannComplexNumbers.jl](https://github.com/scheinerman/RiemannComplexNumbers.jl) :: The RiemannComplexNumbers module is an alternative Complex type for Julia (with a single complex infinity value). 
- [SIE.jl](https://github.com/ApproxFun/SIE.jl) :: Julia package for solving singular integral equations and Riemann–Hilbert problems Julia package for solving singular integral equations and Riemann–Hilbert problems.
- [TaylorSeries.jl](https://github.com/lbenet/TaylorSeries.jl) :: A julia package for Taylor expansions in one independent variable.

###### Learning Resources
+ An IJulia notebook showing [Taylor's method integration of the pendulum](http://nbviewer.ipython.org/gist/lbenet/616fa81f3c12c9cfcf97)


### Ordinary Differential Equations (ODE)
+ [DASSL.jl](https://github.com/pwl/DASSL.jl) :: An implementation of the Differential Algebraic System SoLver (DASSL) algorithm for solving algebraic differential equations.
+ [DualNumbers2.jl](https://github.com/johnmyleswhite/DualNumbers2.jl) :: Another Julia implementation of dual numbers for automatic differentiation.
+ [DynamicalSystems.jl](https://github.com/timothyrenner/DynamicalSystems.jl) :: A collection of Julia functions that produce the systems of ODEs for various dynamical systems. 
+ [IVPTestSuite.jl](https://github.com/mauro3/IVPTestSuite.jl) :: DE solver test suite of Ordinary differential equations (ODE) and algebraic differential equations (DAE).
+ [JFinEALE.jl](https://github.com/PetrKryslUCSD/JFinEALE.jl) :: A Finite Element Analysis Learning Environment (FinEALE) package for finite element analysis of continua. This toolkit is a redesign of the Matlab toolkit.
+ [Makhno.jl](https://github.com/pjabardo/Makhno.jl) :: Spectral element code implemented in Julia.
+ [ODEDSL.jl](https://github.com/AleMorales/ODEDSL.jl) :: Domain specific language to write ODE models with tests. Automatic code generation for Julia, R and CPP (via Rcpp). 
+ [RiemannHilbert.jl](https://github.com/dlfivefifty/RiemannHilbert.jl) :: Riemann–Hilbert problems, named after [Bernhard Riemann and David Hilbert](http://en.wikipedia.org/wiki/Riemann%E2%80%93Hilbert_problem), are a class of problems that arise in the study of differential equations in the complex plane.


####### Learning Resources
+ [FinealeBook.jl](https://github.com/goedman/FinealeBook.jl) :: Trying to understand Petr Krysl's FinEALE book.

#### Org-JuliaLang
+ [ODE.jl](https://github.com/JuliaLang/ODE.jl) :: Assorted basic Ordinary Differential Equation solvers.
- [Roots.jl](https://github.com/JuliaLang/Roots.jl) :: Root finding functions for Julia.
- [SortingAlgorithms.jl](https://github.com/JuliaLang/SortingAlgorithms.jl) :: extra sorting algorithms extending Julia's sorting API.
+ [Sundials.jl](https://github.com/JuliaLang/Sundials.jl) :: A Julia package that interfaces to the Sundials library and includes a nonlinear solver (KINSOL), ODE's (CVODE), and DAE's (IDA).

#### Org-[JuliaDiff](http://www.juliadiff.org/)
+ [JuliaDiff on Github](https://github.com/JuliaDiff/)
- [ReverseDiffSource.jl](https://github.com/JuliaDiff/ReverseDiffSource.jl) :: Automated differentiation by reverse accumulation. [Documentation](http://reversediffsourcejl.readthedocs.org/en/master/index.html).
- [HyperDualNumbers.jl](https://github.com/JuliaDiff/HyperDualNumbers.jl) :: Hyper-Dual Numbers for Exact Second-Derivative Calculations, is structured similar to the DualNumbers package, which aims for complete support for HyperDual types for numerical functions within Julia's Base. Currently, basic mathematical operations and trigonometric functions are supported.
- [ForwardDiff.jl](https://github.com/JuliaDiff/ForwardDiff.jl) :: Juila package for performing forward mode automatic differentiation.
- [DualNumbers.jl](https://github.com/JuliaDiff/DualNumbers.jl) :: Julia package for representing dual numbers and for performing dual algebra.

----

## [Discrete Math](https://en.wikipedia.org/wiki/Category:Discrete_mathematics)
- [Intervals.jl](https://github.com/andrioni/Intervals.jl) :: A pure Julia reimplementation of MPFI, a multiple precision interval arithmetic library.
- [IntModN.jl](https://github.com/andrewcooke/IntModN.jl) :: Ring(s) of Integers Modulo-N.
- [IPPMath.jl](https://github.com/lindahua/IPPMath.jl) :: A Julia package for vectorized math computation based on Intel IPP.
- [PermPlain.jl](https://github.com/jlapeyre/PermPlain.jl) :: Permutations implemented with plain data types - This package implements methods for manipulating permutations. The methods operate on data types in the Base module, or in modules providing generic data types. 
- [Permutations.jl](https://github.com/scheinerman/Permutations.jl) by @scheinerman :: Permutations class for Julia.
- [PermutationsA.jl](https://github.com/jlapeyre/PermutationsA.jl) by @jlapeyre :: Permutation data types and methods. 
- [PrimeSieve.jl](https://github.com/jlapeyre/PrimeSieve.jl) :: This package provides an interface to tables of primes and a sieve library.
- [RomanNumerals.jl](https://github.com/anthonyclays/RomanNumerals.jl) :: Support for Roman numerals in Julia.
- [Shannon.jl](https://github.com/kzahedi/Shannon.jl) :: Entropy, Mutual Information, KL-Divergence related to Shannon's information theory and functions to binarize data.
- [ZChop.jl](https://github.com/jlapeyre/ZChop.jl) :: This package replaces small numbers with zero, works on complex and rational numbers, arrays, and some other structures. The idea is for zchop to descend into structures, chopping numbers, and acting as the the identity on anything that can't be sensibly compared to eps.

----

## Geometry
- [AffineTransforms.jl](https://github.com/timholy/AffineTransforms.jl) :: Computational geometry with affine transformations
- [ConicHulls.jl](https://github.com/toivoh/ConicHulls.jl) :: Exact dynamic conic hulls of integer vectors.
- [ConvexHull.jl](https://github.com/joehuchette/ConvexHull.jl) :: A Julia library for polyhedral computations.
- [GeoAlg.jl](https://github.com/andrioni/GeoAlg.jl) :: A basic geometric algebra library in Julia.
- [Geometry2D.jl](https://github.com/mroughan/Geometry2D.jl) :: 2D computational geometry package for Julia programming language.
- [GeometricalPredicates.jl](https://github.com/skariel/GeometricalPredicates.jl) :: Fast, robust 2D and 3D geometrical predicates on generic point types. Implementation follows algorithms described in the Arepo paper and used (for e.g.) in the Illustris Simulation. 
- [mbr.jl](https://github.com/intdxdt/mbr.jl) :: axis aligned minimum bounding box.
- [Tensors.jl](https://github.com/pgawron/Tensors.jl) :: Julia package for tensor decompositions.
- [TensorOperations.jl](https://github.com/Jutho/TensorOperations.jl) :: Julia package for tensor contractions and related operations.

#### Org-[JuliaGeometry](https://github.com/JuliaGeometry)
+ [OctTrees.jl](https://github.com/JuliaGeometry/OctTrees.jl) :: Fast quad and oct-trees.
+ [TetGen.jl](https://github.com/JuliaGeometry/TetGen.jl) :: TetGen wrapper. 

----

## [Numerical Analysis](https://en.wikipedia.org/wiki/Category:Numerical_analysis)
- [Dopri.jl](https://github.com/helgee/Dopri.jl) :: A Julia wrapper for the DOPRI5 and DOP853 integrators.
- [EiSCor.jl](https://github.com/andreasnoack/EiSCor.jl) :: A Julia wrapper of the Fortran library "eiscor" (Fortran 90 subroutines for structured matrix eigenvalue problems using 2x2 unitary matrices) for efficiently solving structured matrix eigenvalue problems using unitary core transformations 
- [Expokit.jl](https://github.com/acroy/Expokit.jl) :: A package that provides Julia implementations of some routines contained in EXPOKIT.
- [Grid.jl](https://github.com/timholy/Grid.jl) :: Interpolation and related operations on grids.
- [GridInterpolations.jl](https://github.com/sisl/GridInterpolations.jl) :: Multi-dimensional grid interpolation in arbitrary dimensions on a recti-linear grid. 
- [InplaceOps.jl](https://github.com/simonbyrne/InplaceOps.jl) :: Convenient macros for in-place matrix operations in Julia.
- [LinearExpressions.jl](https://github.com/cdsousa/LinearExpressions.jl) :: is a Julia package to manipulate symbolic linear expressions with both scalar and matrix coefficients - large linear matrix inequalities (LMI) for SDP optimization.
- [LinearMaps.jl](https://github.com/Jutho/LinearMaps.jl) :: A Julia package for defining and working with linear maps, also known as linear transformations or linear operators acting on vectors. The only requirement for a LinearMap is that it can act on a vector (by multiplication) efficiently.
- [linop.jl](https://github.com/dpo/linop.jl) :: Basic linear operator package for Julia.
- [RandomMatrices.jl](https://github.com/jiahao/RandomMatrices.jl) :: Random Matrices.
- [juliaSpot](https://github.com/slimgroup/juliaSpot) :: The Julia implementation of the Spot Linear Algebra Package.
- [Knitro.jl](https://github.com/yeesian/Knitro.jl) :: Julia interface to the Knitro solver.
- [LinearMaps.jl](https://github.com/Jutho/LinearMaps.jl) :: A Julia package for defining and working with linear maps, also known as linear transformations or linear operators acting on vectors. The only requirement for a LinearMap is that it can act on a vector (by multiplication) efficiently.
- [MovcolN.jl](https://github.com/pwl/MovcolN.jl) :: Moving collocation method to solve one dimensional partial differential equations.
- [NAG.jl](https://github.com/StefanKarpinski/NAG.jl) :: Julia package to wrap the NAG Numerical Library, a propreitary software library of numerical analysis routines, mathematical and statistical algorithms for linear algebra, optimization, quadrature, the solution of ordinary and partial differential equations, regression analysis, and time series analysis.

### Numerical Linear Algebra (NLA)
__Julia implementations of solvers for Numerical Linear Algebra (NLA) == Numerical Analysis and Linear Algebra algorithms for the numerical solution of matrix problems.__
- [BSplines.jl](https://github.com/gusl/BSplines.jl) :: This package provides B-Splines for 1D signals, i.e. functions of type Real -> Real.
- [IncrementalSVD.jl](https://github.com/aaw/IncrementalSVD.jl) :: Simon Funk's approach to collaborative filtering using the singular value decomposition, implemented in Julia.
- [InteriorPoint.jl](https://github.com/IainNZ/InteriorPoint.jl) :: Primal-dual interior point solver for linear programs.
- [IterativeLinearSolvers.jl](https://github.com/andreasnoackjensen/IterativeLinearSolvers.jl)
- [NumericFunctors.jl](https://github.com/lindahua/NumericFunctors.jl) :: Typed functors for numerical computations.
- [ParallelLinalg.jl](https://github.com/intirb/ParallelLinalg.jl) :: Distributed Dense Linear Algebra for Julia.
- [PNLA_Julia](https://github.com/kbatseli/PNLA_Julia) :: Polynomial Multi-functional Numerical Linear Algebra package for solving all kinds of problems with multivariate polynomials in double precision in Julia.
- [RK4.jl](https://github.com/ntezak/RK4.jl) :: This package implements a fairly fast Runge-Kutta 4th order with fixed stepsize, also implements a stochastic solver that is not technically provably accurate, but works well for finite bandwidth SDE's.
- [SpecialMatrices.jl](https://github.com/timbers/SpecialMatrices.jl) :: Package that adds support for several common matrices: Strang, Hankel, Toeplitz, and Vander matrices.
- [SpecialMatrices.jl](https://github.com/jiahao/SpecialMatrices.jl) :: Julia package for working with special matrix types.
- [ToeplitzMatrices.jl](https://github.com/andreasnoackjensen/ToeplitzMatrices.jl) :: Fast matrix multiplication and division for Toeplitz matrices in Julia.
- [VML.jl](https://github.com/simonster/VML.jl) :: Julia bindings for the Intel Vector Math Library.

**Linear Algebra**
+ [Hypre.jl](https://github.com/jgoldfar/Hypre.jl) :: A wrapper for the [Hypre](http://acts.nersc.gov/hypre/) library.
+ [KrylovSolvers.jl](https://github.com/cfbaptista/KrylovSolvers.jl) :: Solve sparse linear systems in an efficient and iterative manner with Krylov Solvers.
+ [LDA.jl](https://github.com/remusao/LDA.jl) :: Linear Discriminant Analysis and Kernel Fisher Analysis.
+ [LMCLUS.jl](https://github.com/wildart/LMCLUS.jl) :: Julia's package for Linear Manifold Clustering.
+ [MUMPS](https://github.com/lruthotto/MUMPS) :: A wrapper for a MUltifrontal Massively Parallel sparse direct Solver of large linear systems in Julia.
+ [MUMPS1.jl](https://github.com/dmbates/MUMPS1.jl) :: An alternative implementation of a Julia interface to the sparse direct solver MUMPS. A MUMPS package for Julia is already registered but that package does not conform to the packaging standards for Julia.
+ [NonuniformArray.jl](https://github.com/ReidAtcheson/NonuniformArray.jl) :: This library handles the case of "array of arrays" where each subarray may have different lengths - but enforces contiguity of data for ease of passing to outside linear algebra packages.
+ [PolarFact.jl](https://github.com/weijianzhang/PolarFa.jl) :: A Julia package for the matrix polar decomposition.
+ [SuperLU.jl](https://github.com/dmbates/SuperLU.jl) :: Julia interface to the SuperLU solver package for sparse systems.


###### Learning Resources
* [The Performance Cost of Integer Overflow Checking](http://danluu.com/integer-overflow/)

## [Special Functions](http://en.wikipedia.org/wiki/Category:Special_functions)
+ [LambertW.jl](https://github.com/jlapeyre/LambertW.jl) :: A package implementing the Lambert_W function and associated omega constant.

----

# PUZZLES
**Puzzles, problem solving games**
- [Deepthought.jl](https://github.com/dejakaymac/Deepthought.jl)
- [euler](https://github.com/somu/euler) :: Project Euler solutions in Julia.
- [sudoku](https://github.com/Alexander-N/sudoku) :: Reimplementing the Python version of Peter Norvig's Sudoku solver in Julia by @Alexander-N.
- [sudoku.jl](https://github.com/johnmyleswhite/sudoku.jl) :: A simple Sudoku solver in Julia by @johnmyleswhite.
- [Sudoku.jl](https://github.com/hayd/Sudoku.jl) :: A port of Peter Norvig's "Solving Every Sudoku Puzzle" to Julia by @hayd.
- [SudokuService](https://github.com/IainNZ/SudokuService) :: Sudoku-as-a-service, powered by Julia, JuMP modelling, and CoinOR CBC integer programming solver.
- [TowerOfHanoi.jl](https://github.com/thiruk/TowerOfHanoi.jl) :: Solution to Tower Of Hanoi using Julia.
- [Project_Euler_Julia.ipynb](http://nbviewer.ipython.org/github/punkrockpolly/Playing-with-Julia/blob/master/Project_Euler_Julia.ipynb) :: Solutions to [Project Euler](http://projecteuler.net) Problems, algorithm & math puzzles.


