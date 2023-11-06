here you will find a number of files that are used to check results in the following paper: A classification of curious Galois groups as direct products

https://arxiv.org/abs/2310.19987

One should first load the code from the groups folder found here
https://github.com/AndrewVSutherland/ell-adic-galois-images

and the code from here
https://github.com/davidzywina/OpenImage/tree/master/main
in particular, GL2GroupTheory and ModularCurves

For the files genera of groups of (p,q) type where p and q are prime numbers with p < q, we take pairs of groups from the Sutherland--Zywina database,

https://arxiv.org/abs/1605.03988

take their direct products using the Chinese remainder theorem and then compute their genus. If the genus is less than 2, we make a record of the groups. Note that the genera of all direct products of pairs of groups from the Sutherland--Zywina database of (p,q) type with p > 3 is greater than 1

In the file, genera of groups of (2,13) type, we compute the genera of groups of level 16*13 and 8*13. We leave the rest of the groups of level 4*13 and 2*13 to be looked up in the LMFDB. There are five groups of level 8*13 of genus 1 to study and we use code from Zywina to compute the associated elliptic curves

In the file, genera of groups of (2,11) type, we compute the genera of groups of level 8*11, 4*11, and 2*11. All such groups have genus > 1

In the file, genera of groups of (2,7) type, we compute the genera of groups of level 2*7, 4*7, 8*7, and 16*11. All such groups have genus 0 and can be found in the LMFDB

In the file, genera of groups of (2,5) type, we compute the genera of groups of level 2*5, 4*5, 8*5, and 16*5, then groups of level 2*25, 4*25, and 8*25. The groups of interest of genus less than 2 can be found in the LMFDB

In the file, genera of groups of (2,3) type, we compute the genera of groups of level 2^M * 3^N where M is at most 4 and N is at most 3. Where it says /* elliptic curves of level 72 */, we compute the models of six groups of level 72 and genus 1 using code from Zywina.

Finally, we need to prove that the groups 8.6.0.1 x 9.12.0.1 and 8.6.0.6 x 9.12.0.1 are not curious by proving that they do not contain any proper, arithmetically admissible subgroups of genus less than 2
