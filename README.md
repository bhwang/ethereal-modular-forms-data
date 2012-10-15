# Ethereal Modular Forms Data

This repository contains data about *ethereal* modular forms, which are mod p modular forms that do not lift to characteristic zero, which exhibit a number of special phenomena. 

Such modular forms are necessarily of weight 1, have F_p-bar Galois representations that are unramified at p, and their (projective) Galois representations are seen to have "large image," i.e. are not cyclic, dihedral, tetrahedral, octahedral, or icosahedral. From the cohomological perspective, ethereal modular forms represent nontrivial p-torsion in
H^1(X_1(N), \omega(-cusps)).

Spaces of ethereal modular forms can't be computed using the standard methods (like modular symbols) for computing form as those methods necessarily assume weight at least 2. The necessity of this distinction is made clearest from the representation theory perspective: automorphic representations associated to weight one forms have archimedean components that are *limits of discrete series* instead of lying in the discrete series itself. Instead, a different approach must be adopted.

This data has been computed using the [Hecke Stability Method](https://escholarship.org/uc/item/07n8235q) developed by Schaeffer, who I thank for both cogent explanations and inspiring discussions. 

Included here are data (as Sage objects) corresponding to ethereal forms up to Level <= 1000, omitting levels  201, 213, 257, 281, 291, 293, 311, 331, 419, 431, 487, 545, 555, 565, 653, 723, 745, 869, 941, 965. 

The entire dataset is about *2.3 GB*. However, it took around 36 hours to generate on a (consumer-grade) machine, so if you don't have access to a powerful computing cluster yourself, just grabbing this data might be faster than generating it.
