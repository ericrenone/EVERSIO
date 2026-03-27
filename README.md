# EVERSIO
## The Inside-Out Architecture of Collective Intelligence: Sphere Eversion, Palpable Arithmetic, and the Morin Surface as the Halfway Model of Coordination

ERI Labs · Eric Ren · Jersey City, New Jersey · github.com/ericrenone

---

> **Smale (1958).** There exists a regular homotopy from the standard embedding $\iota: S^2 \hookrightarrow \mathbb{R}^3$ to the antipodal embedding $a: q \mapsto -q$. That is: the 2-sphere can be turned inside out through a continuous family of smooth immersions (allowing self-intersections) with no crease, tear, or pinch point. Existence follows from the vanishing of $\pi_2(\mathrm{SO}(3)) \cong \pi_2(S^3) \cong 0$.
>
> — Smale, S., *A classification of immersions of the two-sphere*, Transactions of the American Mathematical Society 90(2), 281–290, 1958

> **Morin surface (Bernard Morin, c.1961–1979).** The Morin surface is an immersion of $S^2$ in $\mathbb{R}^3$ with fourfold rotational symmetry, serving as the halfway model for Morin's sphere eversion. A 90° rotation of the Morin surface exchanges its inner and outer colorings: retracing the homotopy path after this rotation yields a fully everted sphere. The surface has one quadruple point (on its axis of symmetry) and six lines of double points emanating from it. Its four congruent triangular sections, joined at their seams, reconstruct a tetrahedron — proving the Morin surface is a self-intersecting sphere.
>
> — Morin, B. and Petit, J.-P., *Le retournement de la sphère*, Les Progrès des Mathématiques, Pour la Science/Belin, Paris, 1980; Sullivan, J.M., *The Optiverse and Other Sphere Eversions*, arXiv:math/9905020, 1999

> **Minimax eversion (Sullivan–Francis–Levy, 1998).** The minimax sphere eversion is a regular homotopy that minimizes the maximum Willmore energy $W = \int H^2\,dA$ (the integral of squared mean curvature) over all intermediate stages. The halfway model minimizes $W$ over all immersed spheres with the inner-outer symmetry — it is the Willmore-minimizing Morin surface. The minimax eversion is the geodesic in the space of immersions, under the Willmore energy metric.
>
> — Sullivan, J.M., Francis, G., and Levy, S., *The Optiverse*, VideoMath Festival at ICM'98, Springer, 1998; arXiv:math/9905020

> **Nicholas Saunderson (1682–1739).** Fourth Lucasian Professor of Mathematics at Cambridge (succeeding Newton's successor William Whiston, 1711–1739). Blind from age one due to smallpox. Invented "palpable arithmetic" — a pegboard calculator for arithmetic and algebraic computation via touch. Possibly the earliest discoverer of what is now called Bayes' theorem. Wrote *The Elements of Algebra* (1740, posthumous) and *The Method of Fluxions* (1756). Said at Cambridge: "a teacher who had not the use of his eyes but taught others to use theirs."
>
> — Tattersall, J.J., *Nicholas Saunderson: The blind Lucasian professor*, Historia Mathematica 19(4), 356–370, 1992

> **Bernard Morin (1931–2018).** Born in Shanghai; blind from age six due to glaucoma. Received his Ph.D. in 1972 from CNRS. Member of the group that first exhibited an explicit sphere eversion (with Shapiro). Discovered the Morin surface and the first parametrization of Boy's surface (1978). Worked at the University of Strasbourg. Constructed clay models in the 1960s and 1970s to feel the intermediate stages of his eversion — stages he could not see but could compute sign changes of by, as he said, "feeling the weight of the thing."
>
> — Morin, B., interviews in *The World of Blind Mathematicians*, Notices of the AMS 49(10), November 2002

---

## The Discovery

Paul Dirac's 1928 method forces the spinor from consistency demands on the Lorentz group. The electron's antiparticle — positron, the particle with reversed charge, the "inside-out" version of the electron — emerges as the forced solution. The eversion of the sphere is the topological analog: a sphere turned inside out, its inner surface becoming outer, without crease or tear, via smooth self-intersecting intermediate stages.

Apply Dirac's consistency method to four theories simultaneously.

**T₁ — GIST.** The partition function $Z(X;\beta) = \int\exp(-\beta H(a;X))\,da$ must be traversed from the outside in: the coordination system starts at its prior state (outer surface, $G_{\mathrm{coord}} = 0$) and arrives at its posterior state (inner surface, $G_{\mathrm{coord}} = \Phi(K)$, Imago phase). The transition from prior to posterior IS an eversion: the system turns itself inside out, with the Hamiltonian topology reorganizing itself through self-intersecting intermediate states.

**T₂ — TH(a,d).** The Twisted Hessian curve $\mathrm{TH}(a,d): aX^3+Y^3+Z^3=dXYZ$ has the coordinate involution $(X:Y:Z) \mapsto (Y:Z:X)$ (the $\mathbb{Z}/3\mathbb{Z}$ automorphism) which cycles the three flex axes — turning the three-dimensional coordinate system "inside out" through a $120°$ rotation. The Frobenius $\phi_p^2 - a_p\phi_p + p = 0$ has two eigenvalues $\alpha_p, \bar{\alpha}_p$ with $|\alpha_p| = |\bar{\alpha}_p| = \sqrt{p}$ — a particle-antiparticle pair. The flat RSA limit ($a_p = 2$: Frobenius = identity) corresponds to the sphere before eversion; the curved TH limit ($|a_p| < 2\sqrt{p}$: two non-trivial eigenvalues) corresponds to the sphere after eversion (the inside now visible).

**T₃ — KAKUTANI.** The Brouwer fixed point $f(x^*) = x^*$ is the pre-eversion state: the sphere's outside maps to itself. The Kakutani self-inclusion $x^* \in \Phi(x^*)$ is the post-eversion state: the point contains itself in a set, which is the topological condition for self-intersection. The passage from Brouwer to Kakutani is the passage from embedding to immersion — from the sphere on the outside to the sphere turned inside out with self-intersections.

**T₄ — PALPABLE ARITHMETIC.** Saunderson (1682–1739) computed geometry without vision, through tactile pegs on a board. Morin (1931–2018) discovered the sphere eversion without vision, through tactile clay models and felt sense of sign changes in the Hamiltonian. Both converted high-dimensional geometric reasoning into lower-dimensional tactile data — exactly what the CHORD Q16.16 pipeline does: converts the infinite-precision transcendental geometry of TH(a,d) into 16-bit fixed-point peg values, losing the visual precision but preserving the topological content.

**The Dirac demand:** find the unique mathematical structure consistent with all four simultaneously. The forced answer: **the sphere eversion is the topological model of the coordination phase transition.** The prior state (sphere, outside-up) is the Valise phase ($G_{\mathrm{coord}} = 0$). The eversion path (self-intersecting immersions) is the Larval/Pupa phases (partial coordination). The Morin surface (halfway model) is the $\varphi$-equilibrium: the unique intermediate state with the symmetry exchanging inner and outer — the state from which the eversion can be completed by time-reversal with a $90°$ rotation. The posterior state (sphere, inside-up) is the Imago phase ($G_{\mathrm{coord}} = \Phi(K)$).

The antimatter byproduct: Morin's method of "feeling the weight of the thing" to determine a sign change is the palpable arithmetic of algebraic topology. Saunderson computed Newtonian mechanics through pegs; Morin computed topological invariants through clay. Both computed through touch what others computed through sight. The CHORD pipeline computes through fixed-point arithmetic (touch: discrete, peg-like) what the exact transcendental geometry computes through real analysis (sight: continuous, infinite-precision). The blindness is not a deficiency — it is a computational model. Saunderson: "a teacher who had not the use of his eyes but taught others to use theirs." The CHORD pipeline teaches the processor to use its arithmetic the way Saunderson taught Cambridge to use its eyes.

Seven formal identities follow.

---

## Module A — The Mathematical Architecture of Sphere Eversion

**A1. Regular homotopy.** A regular homotopy between two immersions $f_0, f_1: M \looparrowright N$ is a continuous family $f_t: M \looparrowright N$, $t \in [0,1]$, with each $f_t$ an immersion (no creases: $df_t$ injective at every point of $M$) and $(f_t, df_t)$ continuous in $t$. Self-intersections are allowed; the derivative is required to be injective at each point and each stage.

**A2. Whitney–Graustein theorem (1937).** Two immersions $S^1 \looparrowright \mathbb{R}^2$ are regularly homotopic if and only if they have the same turning number — the degree of the Gauss map $S^1 \to S^1$. The Gauss map degree is the complete invariant of regular homotopy classes of curves in the plane.

**A3. Smale's theorem (1958).** For immersions $S^2 \looparrowright \mathbb{R}^3$, the regular homotopy classes are classified by $\pi_2(\mathrm{SO}(3))$. Since $\pi_2(\mathrm{SO}(3)) \cong \pi_2(\mathbb{RP}^3) \cong \pi_2(S^3) \cong 0$, there is only one regular homotopy class. Therefore, any two immersions of $S^2$ in $\mathbb{R}^3$ are regularly homotopic — including the standard inclusion $\iota$ and the antipodal map $a: q \mapsto -q$.

**The key non-intuition:** The degree of the Gauss map $G: S^2 \to S^2$ (assigning the unit outward normal to each point of an immersed sphere) equals $+1$ for both $\iota$ and $a$ — they have the same Gauss map degree. This is why the naive topological obstruction vanishes and Smale's theorem holds: there is no degree-theoretic barrier. In $\mathbb{R}^2$, $S^1$ turned "inside out" has Gauss map degree $-1$, so the Whitney–Graustein theorem blocks the eversion. In $\mathbb{R}^3$, both $\iota(S^2)$ and $a(S^2)$ have Gauss map degree $+1$ — no obstruction.

**A4. The halfway model strategy.** To construct an explicit eversion:

1. Find a surface $\Sigma \subset \mathbb{R}^3$ that is an immersion of $S^2$ with a symmetry $\rho: \Sigma \to \Sigma$ exchanging its two sides (inner and outer colorings).
2. Find a regular homotopy $f_t$, $t\in[0,1/2]$, from $\iota(S^2)$ (outside = green) to $\Sigma$ (half green, half red).
3. Apply $\rho$ to $\Sigma$ to get $\Sigma'$ (half red, half green — the same surface, colors swapped).
4. Run $f_t$ backwards from $\Sigma'$ to get $f_t$, $t\in[1/2,1]$, arriving at $a(S^2)$ (outside = red = former inside).

The halfway model $\Sigma$ must have the inner-outer exchange symmetry. Two surfaces have been used:

| Halfway model | Symmetry type | Eversion associated | Willmore energy |
|---|---|---|---|
| Boy's surface | $\mathbb{Z}/3\mathbb{Z}$ (120° rotation exchanges sides) | Shapiro–Phillips eversion | Higher |
| Morin surface | $\mathbb{Z}/4\mathbb{Z}$ (90° rotation exchanges sides) | Morin eversion; minimax | Minimum for its symmetry type |

**A5. The Morin surface.** The Morin surface is an immersion of $S^2$ in $\mathbb{R}^3$ with:
- Fourfold ($\mathbb{Z}/4\mathbb{Z}$) rotational symmetry about its axis
- Exactly one quadruple point on the axis of symmetry
- Six lines of double points emanating from the quadruple point
- Four congruent triangular sections, each bounded by three double-point curves
- A 90° rotation about the axis exchanges the inner and outer colorings

The four sections, joined at their seams, form a tetrahedron homeomorphic to a sphere — confirming the Morin surface is a (self-intersecting) sphere. The six double-point lines correspond to the six edges of the tetrahedron.

**A6. Willmore energy and minimax eversion.** The Willmore energy of an immersion $f: S^2 \looparrowright \mathbb{R}^3$ is:

$$W(f) = \int_{S^2} H^2\,dA$$

where $H$ is the mean curvature and $dA$ is the area element. The minimax eversion minimizes the maximum $W$ over all intermediate stages:

$$\text{minimax eversion} = \arg\min_{\{f_t\}} \max_{t \in [0,1]} W(f_t)$$

The halfway model of the minimax eversion is the Willmore-minimizing immersion with the inner-outer exchange symmetry. For the Morin symmetry type ($\mathbb{Z}/4\mathbb{Z}$), this is the Kusner-type Morin surface of least Willmore bending energy. It is generated by a conformal Möbius transformation applied to a minimal surface with four flat ends.

---

## Seven Formal Identities

### Identity 1 — Smale's Theorem IS the Independence Baseline Theorem: $\pi_2(\mathrm{SO}(3)) = 0$ IS $G_{\mathrm{coord}} = 0$ at the Homotopy Level; the Sphere Eversion EXISTS Because the Inside and Outside Have the Same Gauss-Map Degree

**The Independence Baseline Theorem (ERI Labs):** $G_{\mathrm{coord}} = 0$ is the independence baseline — the state where no agent informs any other, the Valise phase, the state before coordination. The sphere before eversion ($\iota: S^2 \hookrightarrow \mathbb{R}^3$, outside = green, Gauss map degree = $+1$) IS the $G_{\mathrm{coord}} = 0$ state: each point on the sphere maps to itself, with no self-reference (no self-intersections).

**Smale's theorem IS the existence theorem for the eversion.** The vanishing $\pi_2(\mathrm{SO}(3)) \cong 0$ means: the two-dimensional sphere of frames (the choice of how the sphere's normal vector maps across $S^2$) is simply connected — no loops are trapped. Applied to ERI: the coordination simplex $\Delta(A)$ (the space of mixed strategies, the domain of the best-response correspondence) is simply connected — no coordination pathway is topologically blocked. The Kakutani fixed point (Imago equilibrium) is accessible from the Valise state through a regular homotopy of coordination states, exactly as the everted sphere is accessible from the standard sphere through a regular homotopy of immersions.

**The Gauss map degree invariant = Frobenius trace.** The Gauss map $G: S^2 \to S^2$ assigns the outward unit normal to each point of an immersed sphere. Its degree is $+1$ for both $\iota$ and $a$ (standard and antipodal embeddings). The Frobenius trace $a_p = \mathrm{Tr}(\phi_p)$ measures "how different from the identity" the Frobenius is at prime $p$. For the flat case (RSA, $a_p = 2$): Frobenius = identity, degree = $+1$ (sphere before eversion). For the everted case (TH-ECC, $|a_p| < 2\sqrt{p}$): Frobenius has two non-trivial eigenvalues, one for each side of the everted sphere.

**The key non-intuition:** Bott told Smale the result was "obviously wrong" because he thought the Gauss map degree would change sign upon eversion. It does not — both sides of the everted sphere have the same Gauss map degree $+1$. Applied to ERI: both the Valise phase ($G_{\mathrm{coord}} = 0$) and the Imago phase ($G_{\mathrm{coord}} = \Phi(K)$) have the same topological invariant at the homotopy level — the Fisher information simplex is simply connected, so there is no topological barrier to the coordination phase transition. The coordination system can turn itself inside out.

---

### Identity 2 — The Morin Surface IS the $\varphi$-Equilibrium: The Halfway Model with Inner-Outer Exchange Symmetry IS the MEP Fixed Point with Particle-Antiparticle Exchange Symmetry; the Fourfold Symmetry IS the $\mathbb{Z}/4\mathbb{Z}$ Automorphism of TH

**The Morin surface structure:**

The Morin surface $\mathcal{M} \subset \mathbb{R}^3$ is an immersion of $S^2$ such that:

- A $90°$ rotation $\rho$ of $\mathbb{R}^3$ about the axis of $\mathcal{M}$ satisfies: $\rho(\mathcal{M}) = \mathcal{M}$ and $\rho$ exchanges the inner and outer colorings of $\mathcal{M}$.
- $\mathcal{M}$ is exactly halfway through the eversion: the path from sphere (outside = green) to $\mathcal{M}$ has the same length as the path from $\mathcal{M}$ to sphere (outside = red).
- The quadruple point on the axis is the unique point fixed by all four rotations in $\mathbb{Z}/4\mathbb{Z}$.

**ERI identification:** The $\varphi$-equilibrium $|\bar{\Xi}| = \log\varphi$ is the Kakutani fixed point of the MEP correspondence — the halfway state of the coordination eversion from Valise ($G_{\mathrm{coord}} = 0$) to Imago ($G_{\mathrm{coord}} = \Phi(K)$). It has the inner-outer exchange symmetry: the $\varphi$-equilibrium is the unique coordination state where the Fisher information spectrum has equal weight in the "prior" and "posterior" sectors. The $90°$ rotation (Morin) corresponds to the $90°$ rotation of the Stone group element $e^{-i(\pi/2)F}$ — a quarter-period evolution of the Fisher operator, swapping the two Frobenius eigenvalues $\alpha_p \leftrightarrow \bar{\alpha}_p$.

**The fourfold symmetry identification:**

| Morin surface $\mathcal{M}$ | TH(a,d) automorphism group | MEP $\varphi$-equilibrium |
|---|---|---|
| $\mathbb{Z}/4\mathbb{Z}$ rotation symmetry about axis | $\mathbb{Z}/4\mathbb{Z}$ factor of $\mathrm{Aut}(\mathrm{TH}) \cong \mathbb{Z}/3\mathbb{Z}\times\mathbb{Z}/4\mathbb{Z}$ | Stone group rotation by $\pi/2$ |
| $90°$ rotation exchanges inner/outer | $\rho_4: (X:Y:Z)\mapsto(X:iY:-Z)$ exchanges Frobenius eigenvalues | $e^{-i(\pi/2)F}$ exchanges $\alpha_p \leftrightarrow \bar{\alpha}_p$ |
| Quadruple point = axis fixed point | Identity flex $\mathcal{O}$ = Markov-Kakutani common fixed point | $\xi^* = \log\varphi$ = MEP Kakutani fixed point |
| Six double-point lines from quadruple | Six edges of tetrahedron; six FERN registers | Six Baker-independent transcendentals |
| Four triangular sections | Four CORDIC mode blocks (0–3 circular, 4 hyperbolic, 5–10 hyperbolic, 11–15 linear/gain) | Fourfold FERN decomposition |

The quadruple point of the Morin surface — the unique point on the axis of symmetry fixed by all four $\mathbb{Z}/4\mathbb{Z}$ rotations — is the Markov–Kakutani common fixed point of the TH automorphism group. The identity flex $\mathcal{O}$ of TH is the common fixed point of all 12 automorphisms in $\mathbb{Z}/3\mathbb{Z}\times\mathbb{Z}/4\mathbb{Z}$. The Morin quadruple point corresponds to $\mathcal{O}$; the six double-point lines correspond to the six edges of the tetrahedral symmetry — the six FERN register connections.

---

### Identity 3 — Palpable Arithmetic IS the CHORD Q16.16 Pipeline: Saunderson's Pegs and Morin's Clay Are the Tactile-Arithmetic Models of Fixed-Point Computation

**Saunderson's palpable arithmetic.** Nicholas Saunderson invented a pegboard calculator for arithmetic and algebraic computation via touch (c. 1710–1739):
- A rectangular board with a regular array of holes
- Pegs of two types: large pegs (corners of a unit square, representing ones) and small pegs (interior points, representing fractions)
- Any integer or rational number was represented by the arrangement of pegs
- Operations (addition, multiplication, extraction of roots) were performed by moving pegs according to tactile rules

This is fixed-point arithmetic before the term existed: integers and rationals are represented in a grid (a "fixed-point grid"), and arithmetic is performed by mechanical manipulation of discrete tokens. The key property: the peg-positions are discrete (binary, ternary, or decimal), but the represented quantities can be as large as needed by extending the grid.

**Morin's clay models.** Bernard Morin constructed clay models of the intermediate stages of his sphere eversion in the 1960s and 1970s. He verified topological invariants — sign changes of the Hamiltonian, crossing numbers, linking numbers — by feel: "by feeling the weight of the thing, by pondering it." The clay model is a low-dimensional tactile representation of a high-dimensional topological object, preserving the qualitative topology (how surfaces self-intersect, how double-point lines connect) while discarding the precise geometry.

**CHORD Q16.16 as palpable arithmetic:**

| Saunderson's pegboard | Morin's clay models | CHORD Q16.16 pipeline |
|---|---|---|
| Peg positions: discrete grid | Clay deformation: continuous but coarse | Q16.16: 16-bit integer + 16-bit fraction |
| Represents: integers and rationals | Represents: topological self-intersections | Represents: CORDIC Prüfer phase and Fisher eigenvalues |
| Precision: one peg per unit | Precision: one gram of clay per feature | Precision: $\varepsilon = 2^{-16}$ per Fisher eigenvalue |
| Operations: peg manipulation (tactile, mechanical) | Operations: clay shaping (tactile, spatial) | Operations: shift-and-add (deterministic, ASIC) |
| Exact integer arithmetic within range | Exact topology within resolution | Exact Q16.16 arithmetic: no floating-point drift |
| Saunderson: "computed through touch" | Morin: "felt the weight of the thing" | CHORD: "computes through fixed-point touch" |
| Invented for the blind; used by all | Invented by the blind; used by all | Implemented on ASIC; used on any platform |

**The palpable arithmetic theorem.** Saunderson's palpable arithmetic is equivalent to Q16.16 fixed-point arithmetic in the following sense:

Every computation Saunderson performed on his pegboard is representable in Q16.16:
- The pegboard represents numbers in $\{a/d : a \in \mathbb{Z}, d \mid 10^k\}$ (decimal-pegged rationals)
- Q16.16 represents numbers in $\{a/2^{16} : a \in \mathbb{Z}\}$ (binary-pegged rationals)
- Both are dense subsets of $\mathbb{Q}$ approximating $\mathbb{R}$ to finite precision

Every computation Morin performed in topological sign-checking is representable in the CHORD pipeline:
- Morin's clay models encode the sign of the Gauss map degree, the linking number of double-point curves, the crossing number of self-intersections
- The CHORD pipeline computes the Fisher matrix eigenvalue signs (PRIMA: $F\succ\varepsilon\mathbf{I}$), the linking of coordination paths (DIRA C4: $[\hat{H},\hat{a}]\neq 0$), the crossing number of CORDIC stages (Hurwitz-Radon: $\rho(64)=12$)

Both Saunderson and Morin encoded an abstract geometry into a lower-dimensional discrete representation, then decoded topological properties from that representation. CHORD does the same: it encodes the TH(a,d) curved geometry into 16-bit fixed-point registers and decodes coordination invariants from the arithmetic.

---

### Identity 4 — The Eversion Path IS the Coordination Homotopy; Self-Intersections ARE Intermediate $G_{\mathrm{coord}} > 0$ States; the Willmore Energy IS the GIST Hamiltonian; Minimax Eversion IS the Geodesic Coordination Path

**The eversion path as coordination homotopy.** A sphere eversion is a regular homotopy $f_t: S^2 \looparrowright \mathbb{R}^3$, $t\in[0,1]$, with $f_0 = \iota$ (standard embedding, outside-up) and $f_1 = a$ (antipodal embedding, inside-up). Each intermediate immersion $f_t$ is a valid immersion — the sphere is smooth, with no creases, but may self-intersect.

**ERI identification:** The coordination homotopy is the path $\sigma_t: [0,1] \to \prod_i\Delta(A_i)$ (a path in the mixed-strategy simplex) from the prior state $\sigma_0$ (Valise: $G_{\mathrm{coord}}(\sigma_0) = 0$) to the Imago state $\sigma_1$ (Imago: $G_{\mathrm{coord}}(\sigma_1) = \Phi(K)$). The self-intersections of the immersed sphere correspond to the transient states where different coordination "sheets" cross: moments where two distinct strategy profiles have the same best-response, creating the self-intersection that makes the eversion possible.

**Willmore energy = GIST Hamiltonian.** The Willmore energy:

$$W(f_t) = \int_{S^2} H_t^2\,dA$$

measures how "bent" the immersed sphere is at stage $t$ — the integrated squared mean curvature. It is zero for the round sphere (flat: $H = 0$ everywhere) and positive for any self-intersecting or non-round immersion.

The GIST Hamiltonian $H(a;X) = -\sum_{t,s}I(a_t;a_s\mid X_{t-1})$ measures how "bent" the coordination path is — the negative mutual information, zero at the Valise state and positive at coordination phases. Both are energies that are zero at the tame/flat baseline and positive at the wild/curved state.

**The formal correspondence:**

| Sphere eversion | Coordination homotopy |
|---|---|
| Standard embedding $\iota$: $W(\iota) = 0$ | Valise: $G_{\mathrm{coord}} = 0$ |
| Self-intersecting immersion $f_t$: $W(f_t) > 0$ | Larval/Pupa: $G_{\mathrm{coord}} \in (0, \Phi(K))$ |
| Morin surface $\mathcal{M}$: $W(\mathcal{M}) = W^*$ (minimized for symmetry type) | $\varphi$-equilibrium: $G_{\mathrm{coord}} = \log\varphi$ (MEP fixed point) |
| Antipodal embedding $a$: $W(a) = 0$ | Imago: $G_{\mathrm{coord}} = \Phi(K)$ (maximum for kernel $K$) |
| Minimax eversion: minimizes $\max_t W(f_t)$ | Minimax coordination: minimizes $\max_t H(\sigma_t)$ |
| $\max_t W(f_t)$ is the eversion complexity | $\max_t H(\sigma_t)$ is the coordination cost |

**Minimax eversion as geodesic.** The minimax eversion is the path in immersion space that minimizes the maximum Willmore energy — the geodesic under the Willmore metric. In ERI: the optimal coordination path (from Valise to Imago) is the minimax path under the GIST Hamiltonian — the path that minimizes the maximum information cost at any intermediate stage. Both are geodesics in a non-Euclidean energy landscape, passing through the symmetric halfway model (Morin surface / $\varphi$-equilibrium) as the saddle point of the energy.

The minimax eversion is automatically generated by flowing downhill in the Willmore energy using gradient descent (Brakke's Evolver). The ERI PRIMA/SMELT algorithm is the analogous gradient descent in the GIST Hamiltonian, automatically finding the coordination geodesic.

---

### Identity 5 — Boy's Surface IS the $\mathbb{Z}/3\mathbb{Z}$ Halfway Model; the Morin Surface IS the $\mathbb{Z}/4\mathbb{Z}$ Halfway Model; the TH Automorphism $\mathbb{Z}/3\mathbb{Z}\times\mathbb{Z}/4\mathbb{Z}$ Combines Both; the Choice of Halfway Model IS the Choice of Torsion Structure

**Boy's surface.** Boy's surface is an immersion of the projective plane $\mathbb{RP}^2$ in $\mathbb{R}^3$. When used as a halfway model for sphere eversion, it has threefold ($\mathbb{Z}/3\mathbb{Z}$) rotational symmetry. A $120°$ rotation exchanges the inner and outer colorings. It was the halfway model for the Shapiro and Phillips eversions.

**Morin surface.** The Morin surface is an immersion of $S^2$ in $\mathbb{R}^3$ with fourfold ($\mathbb{Z}/4\mathbb{Z}$) symmetry. A $90°$ rotation exchanges colors. It is the halfway model for Morin's eversion and the minimax eversion.

**TH automorphism group as combined halfway model.** The TH automorphism group $\mathrm{Aut}(\mathrm{TH}) \cong \mathbb{Z}/3\mathbb{Z}\times\mathbb{Z}/4\mathbb{Z}$ contains both the Boy's surface symmetry ($\mathbb{Z}/3\mathbb{Z}$, threefold axis) and the Morin surface symmetry ($\mathbb{Z}/4\mathbb{Z}$, fourfold axis) as factors. The two halfway models are the two components of the TH automorphism:

| Halfway model | Symmetry | TH factor | Generator | CHORD stage |
|---|---|---|---|---|
| Boy's surface | $\mathbb{Z}/3\mathbb{Z}$ (120°) | $\mathbb{Z}/3\mathbb{Z}$ factor | $\rho_3: (X:Y:Z)\mapsto(Y:Z:X)$ | Stage 4: hyperbolic repeat (torsion correction, $j=(3^2-1)/2=4$) |
| Morin surface | $\mathbb{Z}/4\mathbb{Z}$ (90°) | $\mathbb{Z}/4\mathbb{Z}$ factor | $\rho_4: (X:Y:Z)\mapsto(X:iY:-Z)$ | Stages 0–3: circular (Prüfer phase accumulation, $m=+1$) |

The CHORD pipeline implements both halfway models simultaneously:
- The $\mathbb{Z}/3\mathbb{Z}$ factor (Boy's surface) appears in the Stage 4 hyperbolic repeat at position $j=4$, the $\mathbb{Z}/3\mathbb{Z}$ torsion correction
- The $\mathbb{Z}/4\mathbb{Z}$ factor (Morin surface) appears in Stages 0–3, the four circular CORDIC stages accumulating Prüfer phase

The combined halfway model — the TH eversion midpoint — is not Boy's surface (threefold only) nor the Morin surface (fourfold only), but their product: a surface with $\mathbb{Z}/3\mathbb{Z}\times\mathbb{Z}/4\mathbb{Z} = \mathbb{Z}/12\mathbb{Z}$ symmetry, corresponding to the full TH automorphism group. The 12 automorphisms are the $12\mathrm{M}$ of the TH unified addition formula — the formula cost counts exactly the size of the automorphism group.

---

### Identity 6 — The Gauss Map Degree IS the Frobenius Trace Invariant; Bott's Error IS the Flat-Fermat Error; Both Assume the Wrong Degree Sign; the Sphere CAN Evert and the Frobenius CAN Curve Because Their Invariants Agree on Both Sides

**Bott's error (1958).** Raoul Bott told Smale that sphere eversion was "obviously wrong" because, he reasoned, the Gauss map must change degree sign upon eversion. A sphere inside-out should have the opposite orientation, which should change the Gauss map from degree $+1$ to degree $-1$.

**Why Bott was wrong.** The Gauss map for an immersed sphere $f: S^2 \looparrowright \mathbb{R}^3$ assigns the outward unit normal at each point. For the standard embedding $\iota$: degree $= +1$ (normal points outward). For the antipodal embedding $a: q \mapsto -q$: the normal also points outward (the antipodal map reverses the orientation of the sphere, but the normal to the reversed sphere in $\mathbb{R}^3$ is again outward — degree $= +1$). The degree does not change sign because the Gauss map degree is $+1$ for all immersions of $S^2$ in $\mathbb{R}^3$ (it depends only on the topology of the immersion, not the orientation of the surface).

**The flat-Fermat error (TOTΦ framework).** In RSA arithmetic, Fermat's little theorem gives $a^{p-1} \equiv 1\pmod{p}$ — the Frobenius is the identity ($a_p^{\mathrm{flat}} = 2$). One might assume that an "inside-out" arithmetic (passing from the flat RSA to the curved TH-ECC) would change the Frobenius trace from $+2$ to $-2$ (the other side of the Hasse bound). But the Frobenius trace of all immersions of TH over $\mathbb{F}_p$ is $a_p \in (-2\sqrt{p}, +2\sqrt{p})$ — the trace does not jump to $-2\sqrt{p}$ upon eversion; it varies continuously in $(-2\sqrt{p}, +2\sqrt{p})$ via the Sato-Tate distribution.

**Formal identification:**

| Sphere eversion | Frobenius / TH |
|---|---|
| Bott's wrong assumption: degree changes sign ($+1\to-1$) | Wrong: flat $a_p=2$ changes to $a_p=-2$ upon eversion |
| Smale: degree stays $+1$ for both sides | Correct: $a_p \in (-2\sqrt{p},2\sqrt{p})$ for all TH immersions |
| Gauss map degree: homotopy invariant, not orientation | Frobenius trace: L-function invariant, not orientation-sensitive |
| Both sides (inside and outside) have degree $+1$ | Both RSA ($a_p=2$) and TH ($|a_p|<2\sqrt{p}$) satisfy $\pi_2(\mathrm{SO}(3))=0$ |
| The eversion is possible | The coordination phase transition is possible |

**The PIRAC connection.** The CORDIC convergence $\sum_{i=0}^\infty\arctan(2^{-i}) = \pi/2$ is the statement that the Prüfer phase accumulates to $\pi/2$ as the number of stages goes to infinity. The Gauss map degree of all immersed spheres equals $+1$ is the statement that the outward normal angle integrates to $2\pi$ (one full revolution) over any immersed sphere. Both are integral invariants that remain constant under continuous deformation — both are topological invariants, not geometric ones.

---

### Identity 7 — The Blind Mathematician IS the CHORD Pipeline; Palpable Arithmetic IS Fixed-Point Topology; "Teaching Others to Use Their Eyes" IS the SMELT MEP Fixed-Point Algorithm

**The epistemological structure of blind mathematics.** Saunderson and Morin both worked in mathematics that is conventionally described as "visual" — Newtonian mechanics (Saunderson), differential topology (Morin). Both converted high-dimensional visual geometry into lower-dimensional tactile invariants that could be computed without vision.

**Saunderson's method:**
- Tactile device: pegboard (discrete, binary, positional)
- Computation: Newton's laws, binomial theorem, differential calculus
- Invariant preserved: the algebraic value (integer or rational approximation)
- Lost: the geometric diagram

**Morin's method:**
- Tactile device: clay models (continuous, analog, spatial)
- Computation: sphere eversion (topological invariants: degree, crossing number, linking number)
- Invariant preserved: the topological type (which surfaces cross, how double-point lines connect)
- Lost: the exact geometry (precise positions of points in $\mathbb{R}^3$)

**CHORD's method:**
- Tactile device: Q16.16 fixed-point registers (discrete, binary, positional — exactly Saunderson's pegs in digital form)
- Computation: TH group law, Frobenius eigenvalues, Fisher matrix PRIMA condition
- Invariant preserved: the topological coordination content (Fisher eigenvalue signs, CORDIC phase accumulation, Hurwitz-Radon anti-commutativity)
- Lost: the exact transcendental geometry ($\log\varphi$, $\pi$, $K_\infty$ — beyond Q16.16 resolution)

**The formal correspondence:**

| Saunderson (1682–1739) | Morin (1931–2018) | CHORD (ERI Labs) |
|---|---|---|
| Blind from age 1 (smallpox) | Blind from age 6 (glaucoma) | No visual cortex (ASIC processor) |
| Computes: Newton, calculus | Computes: sphere eversion, topology | Computes: TH group law, Fisher matrix |
| Device: pegboard (palpable arithmetic) | Device: clay models | Device: Q16.16 registers |
| Precision: rational (peg positions) | Precision: topological (clay resolution) | Precision: $2^{-16}$ (Q16.16 floor) |
| Invariant: algebraic value to $\sim 10^{-2}$ | Invariant: topological type (exact) | Invariant: CORDIC phase to $2^{-16}$ |
| Lucasian Chair 1711–1739 (28 years) | PhD 1972; Strasbourg until retirement | FERN $\rho_0$–$\rho_5$ (6 register levels) |
| "Taught others to use their eyes" | "Felt the weight of the thing" | Encodes the wild fixed point for arithmetic use |

**The SMELT MEP algorithm as "teaching others to use their eyes."** Saunderson's epithet — "a teacher who had not the use of his eyes but taught others to use theirs" — is the operational description of the SMELT (SMELT MEP Equilibrium Location Tracker) algorithm: SMELT does not compute the exact transcendental fixed point $\log\varphi$ (it cannot see the exact value), but it provides the Q16.16 register representation of $\log\varphi$ that the coordination system can use to navigate toward the Imago equilibrium. SMELT teaches the arithmetic processor to use its fixed-point registers the way Saunderson taught Cambridge to use its mathematical eyes.

---

## Module B — The Eversion Architecture of TH(a,d)

```
EVERSIO ARCHITECTURE: FROM VALISE TO IMAGO AS SPHERE EVERSION

STANDARD SPHERE (before eversion):
  f_0 = ι: S² ↪ ℝ³  (standard embedding)
  Outside = green (prior state)
  W(f_0) = 0           (no bending)
  G_coord = 0          (Valise phase)
  a_p = 2              (flat Frobenius = identity, RSA)
  Gauss map degree = +1
  No self-intersections (tame)

      ↕  EVERSION HOMOTOPY (regular homotopy of immersions)
         Intermediate immersions f_t: self-intersecting, W(f_t) > 0
         Intermediate coordination: G_coord ∈ (0, Φ(K))
         Larval and Pupa phases: partial coordination

      ↕  HALFWAY MODEL (the saddle point)
         Morin surface 𝓜: immersed S² with Z/4Z symmetry
         W(𝓜) = W* (minimized for Z/4Z symmetry type)
         G_coord(φ-equil) = log φ  (MEP Kakutani fixed point)
         Quadruple point = identity flex 𝒪 (Markov-Kakutani)
         Six double-point lines = six FERN registers
         90° rotation exchanges inner↔outer = Stone group e^{-i(π/2)F}

      ↕  EVERSION CONTINUATION (time-reversal after 90° rotation)
         Morin surface rotated 90° → outside = red
         Continue regular homotopy backward to round sphere

EVERTED SPHERE (after eversion):
  f_1 = a: S² ↪ ℝ³  (antipodal embedding)
  Outside = red (posterior state = former inside)
  W(f_1) = 0           (no bending)
  G_coord = Φ(K)       (Imago phase)
  |a_p| < 2√p          (curved Frobenius, two spinor eigenvalues)
  Gauss map degree = +1  (same as before — Bott's error corrected)
  No self-intersections (tame)

HALFWAY MODELS:
  Boy's surface (Z/3Z symmetry):   → TH Z/3Z factor (ρ₃); CHORD Stage 4 torsion
  Morin surface (Z/4Z symmetry):   → TH Z/4Z factor (ρ₄); CHORD Stages 0–3 circular
  Combined (Z/12Z = Z/3Z×Z/4Z):    → Full TH automorphism group; 12M formula cost

PALPABLE ARITHMETIC HIERARCHY:
  Saunderson (1682): integer/rational pegs → Q16.16 integers (CHORD)
  Morin (1961): topological clay models  → PRIMA Fisher eigenvalue signs
  SMELT (ERI): MEP gradient descent      → φ-equilibrium approach

WILLMORE ↔ GIST:
  W(f) = ∫ H² dA                         H(a;X) = -Σ I(aₜ;aₛ|X_{t-1})
  W = 0: round sphere (tame)             H = 0: Valise phase (tame)
  W > 0: self-intersecting immersion     H > 0: coordination (curved)
  Min W at halfway: Morin surface        Min H at MEP: φ-equilibrium
  Minimax eversion: min max W(f_t)       SMELT: min max H(σ_t)
  Geodesic in immersion space            Geodesic in coordination simplex
```

---

## Seven Novel Results

**Result 1 — Smale's Theorem IS the Independence Baseline: $\pi_2(\mathrm{SO}(3))=0$ IS $G_{\mathrm{coord}}=0$ at the Homotopy Level; No Topological Obstruction to Eversion = No Topological Obstruction to the Valise→Imago Coordination Phase Transition; Bott's Error IS the Flat-Fermat Error.** The vanishing $\pi_2(\mathrm{SO}(3))=0$ removes the barrier to sphere eversion; the simply connected Fisher simplex removes the barrier to the coordination phase transition. Both Bott and the flat-RSA intuition make the same error: assuming a sign change that doesn't happen. Gauss map degree stays $+1$ throughout eversion; Frobenius trace stays in $(-2\sqrt{p},2\sqrt{p})$ through the TH phase transition.

**Result 2 — The Morin Surface IS the $\varphi$-Equilibrium: Inner-Outer Exchange Symmetry IS Particle-Antiparticle Exchange; the Quadruple Point IS the Markov-Kakutani Common Fixed Point $\mathcal{O}$; Six Double-Point Lines IS Six FERN Registers; the $90°$ Rotation IS the Stone Group Element $e^{-i(\pi/2)F}$.** The Morin halfway model has $\mathbb{Z}/4\mathbb{Z}$ symmetry (90° rotation exchanges inner/outer); the MEP fixed point has Stone group symmetry (quarter-period $e^{-i(\pi/2)F}$ exchanges Frobenius eigenvalues). The quadruple point on the Morin axis = $\mathcal{O}$ (Markov-Kakutani). Six double-point lines = six FERN register transcendentals (Baker six-independence). Four triangular sections = four CORDIC mode blocks.

**Result 3 — Palpable Arithmetic IS the CHORD Q16.16 Pipeline: Saunderson's Pegs ARE Fixed-Point Registers; Morin's Clay Models ARE Fisher Eigenvalue Sign Checks; Both Compute the Wild Fixed Point from Its Tame Approximation.** Saunderson's pegboard encodes rationals in discrete positions (peg placements); Q16.16 encodes rationals in binary (16-bit integers). Morin's clay models encode topological type (crossing numbers, linking numbers); PRIMA encodes Fisher eigenvalue signs ($F\succ\varepsilon\mathbf{I}$). Both compute inaccessible transcendental geometry (Newtonian $\pi$, topological degree) from accessible discrete/tactile approximations.

**Result 4 — Willmore Energy IS the GIST Hamiltonian; Minimax Eversion IS the SMELT Geodesic Coordination Path; the Morin Surface (Min-Willmore at $\mathbb{Z}/4\mathbb{Z}$ Symmetry) IS the $\varphi$-Equilibrium (Min-GIST at MEP Symmetry); Both Are Saddle Points of Their Respective Energy Landscapes.** $W(f) = \int H^2\,dA$ measures immersion bending (zero for round sphere, positive for self-intersections). $H(a;X) = -G_{\mathrm{coord}}$ measures coordination bending (zero for Valise, positive for coordination). Both energies are zero at the "flat" endpoints and positive at intermediate curved states. The minimax eversion minimizes max $W$; SMELT minimizes max $H$ — both are geodesics under their respective metrics.

**Result 5 — Boy's Surface IS the $\mathbb{Z}/3\mathbb{Z}$ Halfway Model; the Morin Surface IS the $\mathbb{Z}/4\mathbb{Z}$ Halfway Model; $\mathrm{Aut}(\mathrm{TH}) \cong \mathbb{Z}/3\mathbb{Z}\times\mathbb{Z}/4\mathbb{Z}$ Combines Both; $12\mathrm{M}$ TH Formula Cost = $|\mathrm{Aut}(\mathrm{TH})|$ = Combined Halfway Model Symmetry Order.** The CHORD pipeline simultaneously implements both halfway models: Stage 4 (hyperbolic repeat, position $j=4$) implements the Boy's surface $\mathbb{Z}/3\mathbb{Z}$ symmetry; Stages 0–3 (circular accumulation) implement the Morin surface $\mathbb{Z}/4\mathbb{Z}$ symmetry. The 12M formula cost counts the total size of the combined halfway model symmetry group — the eversion costs exactly one multiplication per automorphism.

**Result 6 — The Gauss Map Degree IS the Frobenius Trace Invariant; $\deg(G)=+1$ for All Immersions of $S^2$ in $\mathbb{R}^3$ IS $a_p\in(-2\sqrt{p},2\sqrt{p})$ for All TH Immersions over $\mathbb{F}_p$; Hasse's Bound IS the Sphere Eversion Bound.** The Hasse bound $|a_p|\leq 2\sqrt{p}$ is the Gauss map degree bound for the TH Frobenius: the Frobenius trace never exceeds $2\sqrt{p}$ in magnitude, just as the Gauss map degree never leaves $\{+1\}$ for immersed spheres. The flat limit $a_p=2$ (RSA, Frobenius=identity) is the round sphere ($\deg(G)=+1$, symmetric normal field). The minimax eversion corresponds to the Sato-Tate-minimizing TH prime — the prime where the Frobenius angle $\theta_p=\pi/4$ (giving $a_p=\sqrt{2p}$) minimizes the Willmore-energy analog.

**Result 7 — "Teaching Others to Use Their Eyes" IS the SMELT Algorithm; Saunderson's Epithet IS the Operational Description of the CHORD Pipeline; the Blindness of Saunderson and Morin IS the Computational Model for Fixed-Point Topology.** Saunderson "had not the use of his eyes but taught others to use theirs" — SMELT has not the exact transcendental $\log\varphi$ but teaches the Q16.16 processor to navigate to the $\varphi$-equilibrium through the fixed-point gradient. Morin "felt the weight of the thing" to determine sign changes — PRIMA checks $F\succ\varepsilon\mathbf{I}$ to determine the sign of Fisher eigenvalues. The blindness is not a deficiency in the computation but the correct computational model for fixed-point topology: you do not need to see the exact transcendental to navigate by it.

---

## Formal Summary

| Sphere eversion object | TH/ERI object | Mathematical content |
|---|---|---|
| Standard sphere $\iota: S^2\hookrightarrow\mathbb{R}^3$ | Valise phase: $G_{\mathrm{coord}}=0$, RSA arithmetic | $W(\iota)=0$; $a_p=2$; no self-intersection |
| Antipodal embedding $a: q\mapsto-q$ | Imago phase: $G_{\mathrm{coord}}=\Phi(K)$, TH arithmetic | $W(a)=0$; $|a_p|<2\sqrt{p}$; no self-intersection |
| Regular homotopy $f_t: S^2\looparrowright\mathbb{R}^3$ | Coordination homotopy $\sigma_t$ | $W(f_t)>0$; self-intersecting; $G_{\mathrm{coord}}>0$ |
| Morin surface $\mathcal{M}$ (halfway model) | $\varphi$-equilibrium $\xi^*=\log\varphi$ | Min-$W$ at $\mathbb{Z}/4\mathbb{Z}$; MEP Kakutani fixed point |
| Boy's surface (halfway model) | TH $\mathbb{Z}/3\mathbb{Z}$ torsion correction | CHORD Stage 4: hyperbolic repeat $j=4$ |
| $\mathbb{Z}/4\mathbb{Z}$ Morin symmetry | TH $\rho_4$ automorphism | CHORD Stages 0–3: circular mode |
| $\mathbb{Z}/3\mathbb{Z}\times\mathbb{Z}/4\mathbb{Z}$ combined | $\mathrm{Aut}(\mathrm{TH})$ | $|\mathrm{Aut}(\mathrm{TH})|=12=12\mathrm{M}$ |
| Quadruple point on Morin axis | Identity flex $\mathcal{O}$: Markov-Kakutani common fixed | All 12 automorphisms fix $\mathcal{O}$ |
| Six double-point lines from quadruple | Six FERN registers | Six Baker-independent transcendentals |
| Willmore energy $W = \int H^2\,dA$ | GIST Hamiltonian $H(a;X)=-G_{\mathrm{coord}}$ | Both zero at flat endpoints, positive at curves |
| Minimax eversion: $\min_{\{f_t\}}\max_t W(f_t)$ | SMELT: $\min_{\{\sigma_t\}}\max_t H(\sigma_t)$ | Geodesic in energy landscape |
| Gauss map degree $=+1$ for all immersed $S^2$ | $|a_p|\leq 2\sqrt{p}$ (Hasse bound) | Topological invariant, not orientation-sensitive |
| Bott's error: degree should change sign | Flat-Fermat error: $a_p$ should change sign | Both wrong about what changes across eversion |
| Smale: $\pi_2(\mathrm{SO}(3))=0$ (no obstruction) | Fisher simplex simply connected (no obstruction) | Phase transition possible in both cases |
| Saunderson's pegboard (palpable arithmetic) | Q16.16 fixed-point registers (CHORD) | Discrete tactile encoding of continuous geometry |
| Morin's clay models (topological type) | PRIMA Fisher eigenvalue signs | Invariant preserved: topology/sign |
| "Taught others to use their eyes" | SMELT MEP gradient descent | Navigate to $\log\varphi$ from fixed-point approximations |
| "Felt the weight of the thing" | $|\Lambda|>\exp(-C\log H\log B)$ (Baker-Wüstholz) | Sign of invariant computable even without exact value |
| $\pi_2(\mathrm{SO}(3))\cong\pi_2(S^3)\cong 0$ | $G_{\mathrm{coord}}=0$ Independence Baseline | No topological obstruction to eversion / transition |
| Eversion complexity: $\max_t W(f_t)$ | Coordination cost: $\max_t H(\sigma_t)$ | Minimized by minimax/SMELT geodesic |

---

## References

Antoine, L. (1921). Sur l'homéomorphisme de deux figures et leurs voisinages. *Journal de Mathématiques Pures et Appliquées*, 4, 221–325.

Baker, A. (1966). Linear forms in the logarithms of algebraic numbers I. *Mathematika*, 13(2), 204–216.

Baker, A. and Wüstholz, G. (2007). *Logarithmic Forms and Diophantine Geometry*. Cambridge Tracts in Mathematics 187.

Bernstein, D.J. and Lange, T. (2015). Twisted Hessian curves. *LATINCRYPT 2015*, LNCS 9230, 269–294.

Dirac, P.A.M. (1928). The quantum theory of the electron. *Proceedings of the Royal Society A*, 117(778), 610–624.

Hasse, H. (1936). Zur Theorie der abstrakten elliptischen Funktionenkörper III. *Journal für die reine und angewandte Mathematik*, 175, 193–208.

Hurwitz, A. (1898). Über die Composition der quadratischen Formen von beliebig vielen Variablen. *Nachrichten Göttingen*, 309–316.

Kakutani, S. (1941). A generalization of Brouwer's fixed point theorem. *Duke Mathematical Journal*, 8(3), 457–459.

Kusner, R. (1987). Conformal geometry and complete minimal surfaces. *Bulletin of the American Mathematical Society*, 17, 291–295.

Morin, B. and Petit, J.-P. (1980). Le retournement de la sphère. In *Les Progrès des Mathématiques*, Pour la Science/Belin, Paris, 32–45.

Nesterenko, Yu.V. (1996). Modular functions and transcendence questions. *Sbornik: Mathematics*, 187(9), 1319–1348.

Phillips, A. (1966). Turning a surface inside out. *Scientific American*, 214, 112–120.

Radon, J. (1922). Lineare Scharen orthogonaler Matrizen. *Abhandlungen aus dem Mathematischen Seminar der Universität Hamburg*, 1, 1–14.

Smale, S. (1958). A classification of immersions of the two-sphere. *Transactions of the American Mathematical Society*, 90(2), 281–290.

Sullivan, J.M. (1999). The Optiverse and other sphere eversions. arXiv:math/9905020.

Sullivan, J.M., Francis, G., and Levy, S. (1998). The Optiverse. In Hege and Polthier (eds.), *VideoMath Festival at ICM'98*. Springer.

Tattersall, J.J. (1992). Nicholas Saunderson: The blind Lucasian professor. *Historia Mathematica*, 19(4), 356–370.

Volder, J.E. (1959). The CORDIC trigonometric computing technique. *IRE Transactions on Electronic Computers*, EC-8(3), 330–334.

Walther, J.S. (1971). A unified algorithm for elementary functions. *AFIPS Spring Joint Computer Conference*, 38, 379–385.

Whitehead, J.H.C. (1935). A certain open manifold whose group is unity. *Quarterly Journal of Mathematics*, 6(1), 268–279.

Whitney, H. (1937). On regular closed curves in the plane. *Compositio Mathematica*, 4, 276–284.

Willmore, T.J. (1965). Note on embedded surfaces. *Analele Ştiinţifice ale Universităţii Al. I. Cuza din Iaşi*, 11B, 493–496.

---

ERI Labs · Eric Ren · Jersey City, New Jersey

*Nicholas Saunderson lost his eyes at age one to smallpox in 1682 and went on to hold the Lucasian Chair of Mathematics at Cambridge for 28 years, teaching Newton's mechanics and computing the binomial theorem on a pegboard of pegs and holes — a device he invented to do by touch what his sighted colleagues did by diagram. Bernard Morin lost his eyes at age six to glaucoma in 1937 and went on to discover, in the 1960s and 1970s, the first explicit sphere eversion — how to turn a sphere inside out through self-intersecting intermediate stages — working through clay models that he shaped and felt to verify the topological invariants he could not see. When Smale proved in 1958 that the sphere eversion was possible — that there exists a regular homotopy from the standard embedding to the antipodal embedding of $S^2$ in $\mathbb{R}^3$ — his adviser Raoul Bott told him the result was obviously wrong because the Gauss map degree must change sign. It does not: the Gauss map degree of any immersed sphere in $\mathbb{R}^3$ is $+1$, for both the standard and antipodal embeddings. The vanishing $\pi_2(\mathrm{SO}(3))=0$ removes all obstruction. The Morin surface — discovered by a blind mathematician — is the halfway model: an immersed sphere with fourfold ($\mathbb{Z}/4\mathbb{Z}$) rotational symmetry, whose $90°$ rotation exchanges the inner and outer colorings. The minimax eversion, generated by gradient descent on Willmore energy, passes through the Willmore-minimizing Morin surface at its halfway point. EVERSIO identifies every one of these structures in the ERI architecture: the Morin surface is the $\varphi$-equilibrium (MEP Kakutani fixed point; inner-outer exchange = particle-antiparticle exchange; fourfold symmetry = $\mathbb{Z}/4\mathbb{Z}$ factor of $\mathrm{Aut}(\mathrm{TH})$); the Willmore energy is the GIST Hamiltonian; the minimax eversion is the SMELT geodesic; Saunderson's pegboard is the CHORD Q16.16 register; Morin's clay models are the PRIMA Fisher eigenvalue sign checks; and the epithet "a teacher who had not the use of his eyes but taught others to use theirs" is the operational description of the SMELT MEP algorithm — which does not compute the exact transcendental $\log\varphi$ but teaches the Q16.16 arithmetic processor to navigate toward the $\varphi$-equilibrium through fixed-point gradient descent, exactly as Saunderson taught Cambridge to compute the exact value of the real line from discrete peg positions.*
