# MATH 271
Collection of my notes in Professor Charles Roth's MATH 271 "Linear Algebra and Partial Differential Equations" course at McGill. Taken in F2024. Both the .tex code and rendered PDFs can be found in their respective folders.  

All done! see [full PDF](./main.pdf) and [full LaTeX code](./main.tex) 

## Contents  
MATH 271 is an advanced math course taken exclusively by Mechanical Engineering majors at McGill. It roughly covers boundary value problems of various forms of the Diffusion, Wave, and Laplace's equations alongside aspects of advanced linear algebra. It is comparable to an introductory undergraduate-level partial differential equations course. Here is the [official course outline](./Course%20Outline.pdf) in the Fall 2024 semester. Part 4: "Linear Systems of Ordinary Differential and Difference Equations" was omitted in my year. It appears to have been removed when the credit load of MATH 271 was reduced to 3 from 4 around ten years ago.  

### Prerequisites
If you are a Mechanical Engineering undergrad at McGill taking this class, MATH 263 and MATH 264 are enforced prerequisites. If you are comfortable with the content of the aforementioned classes, you should be fine.  

If you are an external individual, the following is a rough list of necessary prerequisite knowledge. 
- **Multivariable & Vector Calculus**  
  You should be comfortable with partial derivatives, multiple integrals, gradients, the Laplacian operator, and infinite series (particularly Fourier series). Knowledge of vector calculus, namely divergence, curl, flux, line and surface integrals, scalar & vector fields, Gauss' theorem, and common vector identities, is highly recommended.  
  
- **Differential Equations:**  
  Knowledge of first-order and second-order ODEs is essential. You should be able to solve first-order ODEs using separation of variables and integrating factors. You should be able to solve second-order constant coefficient and Euler-Cauchy ODEs. Understanding how the method of undetermined coefficients and variation of parameters works is also useful, but not explicitly tested. Higher-order constant-coefficient ODEs may appear. Separation of variables is a recurring theme and should be well-understood. 

- **Linear Algebra:**  
  Familiarity with matrix algebra, determinants, and row reduction is useful, alongside the concepts of linear dependence and independence. An understanding on what eigenvalues and eigenvectors represent will be very useful, but is not required. Likewise, concepts of vector spaces, inner products, linear operators, basis, dimension, null space, and rank are good to know, but will be reviewed.

### Outline  
  
My notes are split into five sections, as outlined below. Every section below has a corresponding PDF and .tex file (or will have, once I finish transcribing and uploading them). The subsections outlined here are also consistent with the subsections found in the PDF and .tex files. 

**1. Partial Differential Equations in Engineering.** An introduction to the fundamental theorems governing partial differential equations. The derivations of common PDEs used in engineering and their physical interpretations. Uniqueness theorems.  
&nbsp;&nbsp;&nbsp;&nbsp;1.1. Fundamental Lemma of PDEs  
&nbsp;&nbsp;&nbsp;&nbsp;1.2. Fluid Flow  
&nbsp;&nbsp;&nbsp;&nbsp;1.3. Diffusion of Heat  
&nbsp;&nbsp;&nbsp;&nbsp;1.4. Vibrating String  
&nbsp;&nbsp;&nbsp;&nbsp;1.5. Vibrating Membrane  
&nbsp;&nbsp;&nbsp;&nbsp;1.6. Three Fundamental Equations  
&nbsp;&nbsp;&nbsp;&nbsp;1.7. Solving PDEs  
&nbsp;&nbsp;&nbsp;&nbsp;1.8. Uniqueness Theorems  

**2. Boundary Value Problems.**  General solutions of boundary value problems with separation of variables in cartesian and polar coordinates. Particular solutions using Fourier series. Solutions of inhomogenous boundary value problems with slave functions and variation of parameters.  
&nbsp;&nbsp;&nbsp;&nbsp;2.1. BVP 1(A): Diffusion of Heat in a Thin Bar, Ends Maintained at 0&deg;   
&nbsp;&nbsp;&nbsp;&nbsp;2.2. BVP 1(B): Diffusion of Heat in a Thin Bar, Ends Insulated  
&nbsp;&nbsp;&nbsp;&nbsp;2.3. BVP 2: Vibrating String  
&nbsp;&nbsp;&nbsp;&nbsp;2.4. Newton's Law of Heating and Cooling  
&nbsp;&nbsp;&nbsp;&nbsp;2.5. BVP 3: Steady-State Temperature in Rectangular Regions  
&nbsp;&nbsp;&nbsp;&nbsp;2.6. BVP 4: Steady-State Temperature in Circular Regions  
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;2.6.1. BVP 4a: Interior of a Disc  
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;2.6.2. BVP 4b: Exterior of a Disc  
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;2.6.3. BVP 4c: Annular Regions  
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;2.6.4. BVP 4d: Flow Around a Long Circular Cylinder  
&nbsp;&nbsp;&nbsp;&nbsp;2.7. BVP 5: Time-Indepedent Non-Homogenous Aspects  
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;2.7.1. BVP 5a: Diffusion of Heat in a Thin Bar, Ends Maintained at β&deg; and γ&deg;   
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;2.7.2. BVP 5b: Heat Generation/Absorption in a Thin Bar  
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;2.7.3. BVP 5c: Vibrating String with Gravity  
&nbsp;&nbsp;&nbsp;&nbsp;2.8. BVP 6: Time-Dependent Non-Homogenous Aspects  
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;2.8.1. BVP 6a: Generalized Diffusion, ends at 0&deg;  
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;2.8.2. BVP 6b: Generalized Diffusion, Dirichlet B.C.s Function of Time  
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;2.8.2. BVP 6b: Generalized Diffusion, Neumann B.C.s Function of Time  
&nbsp;&nbsp;&nbsp;&nbsp;2.9. BVP 7: 3-Variable Problems  
&nbsp;&nbsp;&nbsp;&nbsp;2.10. BVP 8: Poisson's Equation  

**3. Inner Product Spaces.**  Inner products. Standard inner products of functions and vectors.  

**4. Linear Algebra.**  Review of linear algebra. Generalizations to functions and arbitrary vector spaces. The Gram-Schmidt orthogonalization process. Eigenvalues and eigenfunctions of linear operators. Conditions and consequences of Hermitian operators.  
&nbsp;&nbsp;&nbsp;&nbsp;4.1. Linear Dependence and Independence  
&nbsp;&nbsp;&nbsp;&nbsp;4.2. Wronskian  
&nbsp;&nbsp;&nbsp;&nbsp;4.3. Dimension and Basis  
&nbsp;&nbsp;&nbsp;&nbsp;4.4. Linear Operators  
&nbsp;&nbsp;&nbsp;&nbsp;4.5. Null Spaces  
&nbsp;&nbsp;&nbsp;&nbsp;4.6. Gram-Schmidt Process  
&nbsp;&nbsp;&nbsp;&nbsp;4.7. Eigenvalues/Eigenvectors of Differential Equations  
&nbsp;&nbsp;&nbsp;&nbsp;4.8. Hermitian Operators  
&nbsp;&nbsp;&nbsp;&nbsp;4.9. Parseval's Theorem  

**5. Sturm-Liouville Boundary Value Problems.**  Conditions and consequences of the Strum-Liouville theorem. Solutions of boundary value problems in cylindrical and spherical coordinates using the Sturm-Liouville theorem. Legendre polynomials and Bessel functions.  
&nbsp;&nbsp;&nbsp;&nbsp;5.1. Introduction to Sturm-Liouville Equations  
&nbsp;&nbsp;&nbsp;&nbsp;5.2. Sturm-Liouville Theorem  
&nbsp;&nbsp;&nbsp;&nbsp;5.3. Sturm-Liouville BVPs  
&nbsp;&nbsp;&nbsp;&nbsp;5.4. Legendre Polynomials  
&nbsp;&nbsp;&nbsp;&nbsp;5.5. BVP 9: Steady-State Temperature in Spherical Regions  
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;5.5.1 BVP 9a: Interior of a Sphere  
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;5.5.2 BVP 9b: Exterior of a Sphere  
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;5.5.3 BVP 9c: Cocentric Spheres  
&nbsp;&nbsp;&nbsp;&nbsp;5.6. BVP 10: Steady-State Temperature in Cylindrical Regions  
&nbsp;&nbsp;&nbsp;&nbsp;5.7. BVP 11(A): Diffusion of Heat in a Circular Plate  
&nbsp;&nbsp;&nbsp;&nbsp;5.8. BVP 11(B): Vibrating Circular Membrane  
&nbsp;&nbsp;&nbsp;&nbsp;5.9. BVP 12: Diffusion of Heat in a Sphere  
&nbsp;&nbsp;&nbsp;&nbsp;5.10. BVP 13: Steady-State Temperature in an Annular Semicircle  
&nbsp;&nbsp;&nbsp;&nbsp;~~5.11. BVP 14: Diffusion of Heat in a Thin Bar, Robin Boundary Conditions~~ (Omitted in my year)  
&nbsp;&nbsp;&nbsp;&nbsp;~~5.12. BVP 15: Poisson's Equation in a Cylinder~~ (Omitted in my year)  

### Notes  
These notes were originally written by hand (Goodnotes) and then transcribed into LaTeX. Parts of the transcription were done with automated software (and proofread manually) while other parts of the notes were transcribed manually in their entirety. Although I have attempted to correct any errors, it is possible that I have made errors, omissions, or have applied unsound logic. When in doubt, consult with the professor or a TA.  

It should also be noted that these notes do not necessarily account for a rigorous or complete treatment of partial differential equations. Although I have added extra details on subjects that interested me, the primary purpose of my notes was to serve as a repository of the material I needed to know in order to succeed in Roth's MATH 271 course. Nevertheless, having compared my notes with *"Applied Partial Differential Equations"* by Richard Haberman, it mostly appears to be comparable to a typical introductory PDEs course (like its math department counterpart MATH 319 here in McGill). As MATH 271 is taken by engineering students, it is likely more applied and less theoretical than typical PDE courses.  

If you notice a mistake in the notes, please open an issue outlining the error(s) you've found, and I will fix it as soon as possible. I will credit you if you wish. Please be as specific as possible with regards to the location of the error, the reason my statement is erroneous, and the proposed change. Additionally, if you want to be credited, state how (name/link/etc).

## License  
MIT License. See the [LICENSE](./LICENSE) file for details.
