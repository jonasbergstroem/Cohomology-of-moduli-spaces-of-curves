# Cohomology-of-moduli-spaces-of-curves

A compilation of results on the cohomology of moduli spaces of smooth and stable curves based on research from several different sources. 

## Description of data

All Euler characteristics will be taken in compactly supported ell-adic étale cohomology and have values in the Grothendieck group of ell-adic absolute Galois representations. The S_n-equivariant Euler characteristics also keep track of the action of the symmetric group S_n, whose irreducible representations will be indexed in the usual fashion by Schur polynomials s[mu] with mu a partition of $n$. 

We denote the cyclotomic character of Deligne weight 2 by L and by S[k], the Galois representation (of dimension 2*dim S_k) corresponding to the space S_k of elliptic cusp forms of weight k and level 1. 

All Euler characteristics can also be considered in compactly supported singular cohomology with rational coefficients together with its mixed Hodge structure. Let then L denote the Tate-Hodge structure of type (1,1) and S[k] the pure Hodge structure of type (k-1,0) and (0,k-1), both of dimension dim S_k. 

The S_n-equivariant Euler characteristic of the moduli space of n-pointed stable curves of genus g has been computed from S_n'-equivariant Euler characteristic of the moduli spaces of smooth n'-pointed curves of genus g', with 3g'-3+n' \leq 3g-3+n, using (an implementation in maple by Carel Faber of) the formula (Theorem 8.13) in: 
"E. Getzler and M. M. Kapranov, Modular operads, Compos. Math. 110 (1998), no. 1, 65–126".

Note that (by purity of a smooth and proper DM-stack), a contribution to the S_n-equivariant Euler characteristic of the moduli space of n-pointed stable curves of genus g of Deligne weight i will appear in the semi-simplification of its ith cohomology group.  

The package SF for maple by John Stembridge was used for computations with symmetric polynomials. 

### Genus 0

This data was computed using results from  "E. Getzler, Operads and moduli spaces of genus 0 Riemann surfaces, in: The moduli space of curves (Texel Island, 1994), pp. 199–230, Progr. Math., vol. 129, Birkhäuser Boston, Boston, MA, 1995". The results hold both in ell-adic and singular cohomology. 

-The file "eM0n.txt" contains the S_n-equivariant Euler characteristics of the moduli space of smooth n-pointed curves of genus 0 with n up to 17.

-The file "eMbar0n.txt" contains the S_n-equivariant Euler characteristics of the moduli space of stable n-pointed curves of genus 0 with n up to 17.

### Genus 1 

This data was computed using results from "E. Getzler, Resolving mixed Hodge modules on configuration spaces, Duke Math. J. 96 (1999), no. 1, 175–203", together with results of Section 4.5 in "J. Bergström and C. Faber, Cohomology of moduli spaces via a result of Chenevier and Lannes, Épijournal Géom. Algébrique 7(2023), Art. 20". The results hold both in ell-adic and singular cohomology. 

-The file "eM1n.txt" contains the S_n-equivariant Euler characteristics of the moduli space of smooth n-pointed curves of genus 1 with n up to 15.

-The file "eMbar1n.txt" contains the S_n-equivariant Euler characteristics of the moduli space of stable n-pointed curves of genus 1 with n up to 15.

### Genus 2

This data was computed using results from "D. Petersen, Cohomology of local systems on loci of d-elliptic abelian surfaces, Michigan Math. J. 62 (2013), no. 4, 705–720", together with results of Section 4.5 in "J. Bergström and C. Faber, Cohomology of moduli spaces via a result of Chenevier and Lannes, Épijournal Géom. Algébrique 7(2023), Art. 20". By Theorem 1.1 of "S. Canning, H. Larson and S. Payne, Extensions of tautological rings and motivic structures in the cohomology of Mbar_{g,n}, arXiv:2307.08830" these results hold (for n up to 13) also in singular cohomology.  

-The file "eM2n.txt" contains the S_n-equivariant Euler characteristics of the moduli space of smooth n-pointed curves of genus 2 with n up to 13.

-The file "eMbar2n.txt" contains the S_n-equivariant Euler characteristics of the moduli space of stable n-pointed curves of genus 2 with n up to 13.

### Genus 3

The computation of this data was based on Theorem 7.3 (assuming Conjecture 3.2) in "J. Bergström and C. Faber, Cohomology of moduli spaces via a result of Chenevier and Lannes, Épijournal Géom. Algébrique 7(2023), Art. 20". From Remark 7.4 of loc cit it follows that this result is unconditional for n up to 8. Theorem 1.9 in "S. Canning, H. Larson and S. Payne, Extensions of tautological rings and motivic structures in the cohomology of Mbar_{g,n}, arXiv:2307.08830" states that Theorem 7.3 is unconditional also for n=9, 10 and 11. By Theorem 1.1 in loc. cit. these results hold (for n up to 11) also in singular cohomology.  

-The file "eM3n.txt" contains the S_n-equivariant Euler characteristics of the moduli space of smooth n-pointed curves of genus 3 with n up to 11.

-The file "eMbar3n.txt" contains the S_n-equivariant Euler characteristics of the moduli space of stable n-pointed curves of genus 3 with n up to 11.

Here is a [link](https://github.com/jonasbergstroem/M3A3interp) to a github page in connection with the article *Cohomology of moduli spaces via a result of Chenevier and Lannes* with more (albeit conjectural) results in genus 3. 

### Genus 4

These results for n up to 3 are found in Theorem 1.5 and Theorem 11.1 of "J. Bergström, C. Faber and S. Payne, Polynomial point counts and odd cohomology vanishing on moduli spaces of stable curves, Annals of Mathematics, 199 (3), (2024), 1323-1365." and hold also in singular cohomology. The result for n=0 was earlier proven for singular cohomology in "O. Tommasi, Rational cohomology of the moduli space of genus 4 curves, Compos. Math. 141 no. 2 (2005), 359–384" and "J. Bergström and O. Tommasi, The rational cohomology of Mbar_4, Math. Ann. 338 no. 1 (2007), 207–239".

-The file "eM4n.txt" contains the S_n-equivariant Euler characteristics of the moduli space of smooth n-pointed curves of genus 4 with n up to 3.

-The file "eMbar4n.txt" contains the S_n-equivariant Euler characteristics of the moduli space of stable n-pointed curves of genus 4 with n up to 3.


