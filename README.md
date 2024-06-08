# Cohomology-of-moduli-spaces-of-curves

A compilation of results on the cohomology of moduli spaces of smooth and stable curves based on research from several different sources. 

## Details

All Euler characteristics will (be taken in compactly supported ell-adic étale cohomology and) have values in the Grothendieck group of ell-adic absolute Galois representations. The S_n-equivariant Euler characteristics also keep track of the action of the symmetric group S_n, whose irreducible representations will be indexed in the usual fashion by Schur polynomials s[mu] with mu a partition of $n$. 

We denote the cyclotomic character of Deligne weight 2 by L and by S[k], the Galois representation (of dimension 2*dim S_k) corresponding to the space S_k of elliptic cusp forms of weight k and level 1. 

Note that (by purity of a smooth and proper DM-stack), a Galois representation appearing in the S_n-equivariant Euler characteristic of any moduli space of stable curves of Deligne weight i will appear in (the semi-simplification of) its ith cohomology group.  

The S_n-equivariant Euler characteristic of the moduli space of stable n-pointed curves of genus g has been computed from S_n'-equivariant Euler characteristic of the moduli spaces of smooth n'-pointed curves of genus g', with 3g'-3+n' \leq 3g-3+n, using (an implementation in maple by Carel Faber of) the formula (Theorem 8.13) in: 
"E. Getzler and M. M. Kapranov, Modular operads, Compos. Math. 110 (1998), no. 1, 65–126".

...All Euler characteristics that only contain L can also be taken with values in the Grothendieck group of mixed Hodge structures... 

The package SF for maple by John Stembridge was used for computations with symmetric polynomials. 

### Genus 0

This was computed using results from  "E. Getzler, Operads and moduli spaces of genus 0 Riemann surfaces, in: The moduli space of curves(Texel Island, 1994), pp. 199–230, Progr. Math., vol. 129, Birkhäuser Boston, Boston, MA, 1995".

-The file "M0n.txt" contains the S_n-equivariant Euler characteristics of the moduli space of smooth n-pointed curves of genus 0 with n up to 17.

-The file "Mbar0n.txt" contains the S_n-equivariant Euler characteristics of the moduli space of stable n-pointed curves of genus 0 with n up to 17.

### Genus 1 

This data was computed using results from "E. Getzler, Resolving mixed Hodge modules on configuration spaces, Duke Math. J. 96 (1999), no. 1, 175–203", together with results of Section 4.5 in "J. Bergström and C. Faber, Cohomology of moduli spaces via a result of Chenevier and Lannes, Épijournal Géom. Algébrique 7(2023), Art. 20". 

-The file "M1n.txt" contains the S_n-equivariant Euler characteristics of the moduli space of smooth n-pointed curves of genus 1 with n up to 15.

-The file "Mbar1n.txt" contains the S_n-equivariant Euler characteristics of the moduli space of stable n-pointed curves of genus 1 with n up to 15.

### Genus 2

This data was computed using results from "D. Petersen, Cohomology of local systems on loci of d-elliptic abelian surfaces, Michigan Math. J. 62 (2013), no. 4, 705–720.", together with results of Section 4.5 in "J. Bergström and C. Faber, Cohomology of moduli spaces via a result of Chenevier and Lannes, Épijournal Géom. Algébrique 7(2023), Art. 20". 

-The file "M2n.txt" contains the S_n-equivariant Euler characteristics of the moduli space of smooth n-pointed curves of genus 2 with n up to 13.

-The file "Mbar2n.txt" contains the S_n-equivariant Euler characteristics of the moduli space of stable n-pointed curves of genus 2 with n up to 13.

### Genus 3

The computation of this data was based on Theorem 7.3 (assuming Conjecture 3.2) in "J. Bergström and C. Faber, Cohomology of moduli spaces via a result of Chenevier and Lannes, Épijournal Géom. Algébrique 7(2023), Art. 20". From Remark 7.4 of loc cit it follows that this result is unconditional for n up to 8. Theorem 1.9 in " Samir Canning, Hannah Larson, Sam Payne, Extensions of tautological rings and motivic structures in the cohomology of Mbar_{g,n},  arXiv:2307.08830" states that Theorem 7.3 is unconditional also for n=9, 10 and 11. 

-The file "M3n.txt" contains the S_n-equivariant Euler characteristics of the moduli space of smooth n-pointed curves of genus 3 with n up to 11.

-The file "Mbar3n.txt" contains the S_n-equivariant Euler characteristics of the moduli space of stable n-pointed curves of genus 3 with n up to 11.

### Genus 4

Forthcoming. 

### Genus 5

Forthcoming. 

### Genus 6

Forthcoming. 

### Genus 7

Forthcoming. 

