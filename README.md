# Hot Spot Conjecture

This repository collects research manuscripts and drafts on the hot spot conjecture for the first positive Neumann eigenfunction on bounded domains. Together the drafts establish the strict hot-spots property and complete extremal-set classifications on several classes of highly symmetric domains: the regular cube, regular tetrahedron, regular simplex in every dimension, regular dodecahedron, ellipsoids in arbitrary dimension, diagonal foliated domains in $$\mathbb{R}^n$$, and $$C^{2,\alpha}$$ radial perturbations of the ball. The first four manuscripts treat exactly solvable product and polyhedral domains, where the first eigenspace has dimension greater than one and the global extrema are classified exactly. The remaining three manuscripts address smooth strictly convex domains: ellipsoids without any bound on eccentricity or dimension, an explicit foliated family with unbounded diameter–volume ratio, and a perturbative near-ball regime with a uniform gradient lower bound.

**Draft status:** All manuscripts present candidate proofs. The team is continuing to verify every argument. The summaries below describe the statements and proofs as currently drafted.

* * *

## Manuscripts

### 1. Hot spots and complete extremal sets on a regular cube

**[Read the PDF](https://github.com/mingfeng87/Hot-Spot-Conjecture/blob/main/hot_spots_cube.pdf)**

| Detail | Value |
|---|---|
| **Dimension** | $$3$$ (solid cube $$Q = (-1,1)^3$$) |
| **Range** | First positive Neumann eigenvalue, multiplicity three |
| **Length** | 9 pages |

The manuscript gives a self-contained proof of the hot spots property for the regular solid cube and determines the entire first positive Neumann eigenspace together with the complete global extremal sets of every nonzero real element. For $$Q = (-1,1)^3$$, the first positive eigenvalue is $$\pi^2/4$$ with multiplicity three, and its eigenspace has basis $$\sin(\pi x_i/2)$$, $$1 \le i \le 3$$. For $$a \in \mathbb{R}^3 \setminus \{0\}$$ and $$u(x) = \sum_{i=1}^3 a_i \sin(\pi x_i/2)$$, the maximum is $$\sum_i |a_i|$$ and is attained exactly where $$x_i = \operatorname{sgn}(a_i)$$ for every nonzero coefficient, with zero-coefficient coordinates free; the minimum is attained on the antipodal face. The extremal sets are therefore opposite closed faces, opposite closed edges, or opposite vertices, according as one, two, or three coefficients are nonzero. A complete product basis establishes spectral exhaustiveness, and an explicit quadratic deficit quantifies strictness away from the extremal sets.

* * *

### 2. Hot spots and vertex interpolation on a regular simplex in every dimension

**[Read the PDF](https://github.com/mingfeng87/Hot-Spot-Conjecture/blob/main/hot_spots_regular_n_simplex.pdf)**

| Detail | Value |
|---|---|
| **Dimension** | $$n \ge 2$$ (regular simplex $$T \subset \mathbb{R}^n$$) |
| **Range** | First positive Neumann eigenvalue, eigenspace dimension $$n$$ |
| **Length** | 21 pages |

For a regular simplex $$T \subset \mathbb{R}^n$$ with $$n \ge 2$$, the manuscript proves that the first positive Neumann eigenspace has dimension $$n$$ and that evaluation at the $$n+1$$ vertices identifies this eigenspace with the space of zero-sum real vertex data. Every nonzero first eigenfunction attains its global maximum and minimum exactly at the vertices carrying the largest and smallest vertex values, respectively, and the inequalities are strict at every nonvertex point of the closed simplex, including all lower-dimensional boundary strata. The proof identifies the eigenspace via an injective mean-gradient map and simplex symmetry. A chamber for the stabilizer of one vertex is an orthoscheme; an absolute-value argument for tangent vector fields gives strict signs for all derivatives in its orthonormal edge coordinates, and a local Neumann argument supplies strict comparison along closed segments in every dimension. Normalized vertex modes then give positive interpolation weights, yielding the classification for arbitrary eigenfunctions and every pattern of tied extrema.

* * *

### 3. The first Neumann eigenspace of a regular tetrahedron: hot spots and the complete classification of global extrema

**[Read the PDF](https://github.com/mingfeng87/Hot-Spot-Conjecture/blob/main/hot_spots_regular_tetrahedron.pdf)**

| Detail | Value |
|---|---|
| **Dimension** | $$3$$ (solid regular tetrahedron) |
| **Range** | First positive Neumann eigenvalue, multiplicity three |
| **Length** | 18 pages |

The manuscript proves the strict hot-spots assertion and determines every global extremum of every first positive Neumann eigenfunction on a solid regular tetrahedron. The eigenspace is three-dimensional, and evaluation at the four vertices identifies it with the zero-sum subspace of $$\mathbb{R}^4$$. For vertex values $$c_1,\dots,c_4$$, the global maximum is $$\max_i c_i$$, attained exactly at the vertices having that value; the analogous statement holds for the minimum. In particular, no nonvertex point of an edge or face is a global extremum, including when several vertex values tie. The proof establishes a tangent vector-field variational principle and the mean-gradient parametrization. Absolute-value transformations on symmetry chambers give monotonicity of the vertex and opposite-edge-pair modes, a local Neumann cone-mean argument makes these monotonicities strict on boundary segments, and an ordered nonnegative decomposition into the three types of canonical modes completes the classification. All boundary steps are proved on the solid polyhedron, without assuming a reflection tiling of Euclidean space or an explicit eigenfunction formula.

* * *

### 4. Hot spots and extremum localization on the regular dodecahedron

**[Read the PDF](https://github.com/mingfeng87/Hot-Spot-Conjecture/blob/main/hot_spots_regular_dodecahedron.pdf)**

| Detail | Value |
|---|---|
| **Dimension** | $$3$$ (solid regular dodecahedron) |
| **Range** | First positive Neumann eigenvalue, eigenspace dimension three |
| **Length** | 26 pages |

The manuscript proves that every eigenfunction for the first positive Neumann eigenvalue of a solid regular dodecahedron attains its global maximum and minimum only on the boundary. The eigenspace is three-dimensional and is canonically isomorphic to the ambient reflection representation through the integral of the gradient. An invariant cone for the Jacobian of the coordinate Neumann heat flow yields a common strictly increasing direction for every dominant eigenfunction, including at intersections of internal symmetry mirrors. The manuscript gives all 28 generators and all projection identities of the exact algebraic certificate, and then locates extrema in explicit unions of boundary flag triangles according to the eigenfunction parameter. On one parameter mirror the maxima are confined to a physical edge; for a parameter pointing toward a vertex, the unique maximum is that vertex and the unique minimum is its antipode. The boundary arguments include weak tangential differentiation at physical edges and a local Neumann positivity lemma valid at vertices.

* * *

### 5. Neumann hot spots on ellipsoids in arbitrary dimension

**[Read the PDF](https://github.com/mingfeng87/Hot-Spot-Conjecture/blob/main/hot_spots_ellipsoids.pdf)**

| Detail | Value |
|---|---|
| **Dimension** | $$n \ge 2$$ (bounded ellipsoid in $$\mathbb{R}^n$$) |
| **Range** | Every bounded ellipsoid, no eccentricity or dimension bound |
| **Length** | 15 pages |

The manuscript proves the strict hot-spots property for every bounded ellipsoid in $$\mathbb{R}^n$$, $$n \ge 2$$. More precisely, each nonzero eigenfunction for the first positive Neumann eigenvalue is strictly increasing in an appropriate direction in the longest-axis subspace, so its gradient never vanishes in the interior. The proof uses Pütter's description of the first eigenspace, whose dimension equals the number of longest semiaxes, and rotational reduction to reduce the monotonicity problem to a positive longest-axis coordinate-odd ground state. For distinct semiaxes, a finite-dimensional continuation constructs this ground state in separated confocal form; the zeros of its separation polynomial determine the signs of the derivatives of its one-dimensional factors. Analytic extension handles the singular coordinate sets, and a limit argument treats coincident semiaxes. The manuscript also orders all least coordinate-odd eigenvalues by semiaxis length, using a lift to Robin problems on one fixed ball in dimension $$n+2$$.

* * *

### 6. Hot spots and rigidity on diagonal foliated domains in $$\mathbb{R}^n$$

**[Read the PDF](https://github.com/mingfeng87/Hot-Spot-Conjecture/blob/main/hot_spots_diagonal_foliated_domains.pdf)**

| Detail | Value |
|---|---|
| **Dimension** | $$n \ge 2$$ (explicit smooth convex domains in $$\mathbb{R}^n$$) |
| **Range** | Dimension-independent coefficient condition $$c_i \ge 2$$ for $$n \ge 3$$ |
| **Length** | 25 pages |

The manuscript proves the strict hot-spots property for an explicit family of smooth convex domains in every dimension $$n \ge 2$$, defined in a principal coordinate box by $$\sum_{i=1}^{n-1} c_i \sin^2(y_i/\sqrt{2}) < \cos s$$. For every $$n \ge 3$$, the dimension-independent condition $$c_i \ge 2$$ ensures that the first positive Neumann eigenvalue is simple and equals $$(n+1)/2$$, with eigenfunction $$\sin s \prod_i \cos(y_i/\sqrt{2})$$; a slightly wider coefficient range is proved in dimension two. The manuscript verifies real-analytic boundary regularity, global convexity, and strictly positive principal curvatures, including endpoint parameters and the two poles. The spectral identification combines an injective mean-gradient map with explicit comparison functions positive on transverse half-domains, and the gradient leaves give a foliation away from the poles that allows independent changes of all diagonal parameters. The diameter is exactly $$\pi$$, while the diameter–volume ratio is unbounded. The manuscript also classifies every connected $$C^2$$ domain in the principal box on whose boundary this prescribed function satisfies the Neumann condition: such a domain is determined by a positive definite matrix equal to the second fundamental form at either pole, and coordinate reflections force the matrix to be diagonal. In dimensions $$n \ge 3$$, a convex, reflection-symmetric $$C^{1,1}$$ example shows that twice differentiable pole regularity is essential for the classification.

* * *

### 7. Strict hot spots and boundary critical points on domains close to a ball

**[Read the PDF](https://github.com/mingfeng87/Hot-Spot-Conjecture/blob/main/hot_spots_near_balls_tine_epsilon.pdf)**

| Detail | Value |
|---|---|
| **Dimension** | $$n \ge 2$$ |
| **Range** | $$C^{2,\alpha}$$ radial perturbations of the unit sphere, $$0 < \alpha < 1$$ |
| **Length** | 12 pages |

Fix $$n \ge 2$$ and a Hölder exponent $$0 < \alpha < 1$$. The manuscript proves that every domain whose boundary is a sufficiently small $$C^{2,\alpha}$$ radial perturbation of the unit sphere has the following property: every nonzero first positive Neumann eigenfunction has no interior critical point and has exactly two critical points on the closure, namely its unique boundary maximum and minimum, both nondegenerate as critical points of the boundary restriction. Uniformly over these domains and eigenfunctions, the magnitude of the gradient is bounded below by a positive constant times the distance to the boundary times the supremum norm of the eigenfunction. The proof first establishes the complete structure of the first eigenspace of the ball, then proves uniform $$C^2$$ compactness under domain perturbations, and finally uses the Neumann condition and a nonzero second normal derivative to exclude critical points approaching the boundary. The argument accommodates arbitrary eigenvalue multiplicity and splitting, and a general stability criterion is proved along the way.

* * *

## Citing a manuscript

Use the full manuscript title and the date printed in the PDF, use M. Zhao et al. as the author of PDF files. Include the
[repository URL](https://github.com/mingfeng87/Hot-Spot-Conjecture)
and the commit hash or a commit-specific PDF link for the version consulted,
so that the cited draft can be identified after revisions.

* * *

## Repository structure

| File | Description |
|---|---|
| [`hot_spots_cube.pdf`](https://github.com/mingfeng87/Hot-Spot-Conjecture/blob/main/hot_spots_cube.pdf) | Dimension 3, regular cube, complete extremal sets |
| [`hot_spots_regular_n_simplex.pdf`](https://github.com/mingfeng87/Hot-Spot-Conjecture/blob/main/hot_spots_regular_n_simplex.pdf) | Every dimension $$n \ge 2$$, regular simplex, vertex interpolation |
| [`hot_spots_regular_tetrahedron.pdf`](https://github.com/mingfeng87/Hot-Spot-Conjecture/blob/main/hot_spots_regular_tetrahedron.pdf) | Dimension 3, regular tetrahedron, complete extremal classification |
| [`hot_spots_regular_dodecahedron.pdf`](https://github.com/mingfeng87/Hot-Spot-Conjecture/blob/main/hot_spots_regular_dodecahedron.pdf) | Dimension 3, regular dodecahedron, extremum localization |
| [`hot_spots_ellipsoids.pdf`](https://github.com/mingfeng87/Hot-Spot-Conjecture/blob/main/hot_spots_ellipsoids.pdf) | Every dimension $$n \ge 2$$, every bounded ellipsoid, strict monotonicity |
| [`hot_spots_diagonal_foliated_domains.pdf`](https://github.com/mingfeng87/Hot-Spot-Conjecture/blob/main/hot_spots_diagonal_foliated_domains.pdf) | Every dimension $$n \ge 2$$, explicit diagonal foliated family, rigidity |
| [`hot_spots_near_balls_tine_epsilon.pdf`](https://github.com/mingfeng87/Hot-Spot-Conjecture/blob/main/hot_spots_near_balls_tine_epsilon.pdf) | Every dimension $$n \ge 2$$, $$C^{2,\alpha}$$ near-ball domains, uniform gradient bound |

* * *

## Keywords

Hot spots conjecture; Neumann Laplacian; first positive eigenvalue; eigenfunction multiplicity; regular cube; regular simplex; regular tetrahedron; regular dodecahedron; ellipsoid; diagonal foliated domain; domain perturbation; boundary critical point; extremal set; invariant cone; vertex interpolation.
