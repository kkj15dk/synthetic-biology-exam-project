# synthetic-biology-exam-project

Our synthetic biology project using teemi to generate a combinatorial library
Using in vivo assembly for construction of A. nidulans mutants.
To create mutants capable of degrading and using polycyclic aromatic hydrocarbons (PAHs)

There is a first library in the file 'first library', but this is very minimal, and should be ignored.
The real fun is in 'DESIGN_of_Combinatorial_library'.
Using two integration site, IS1 and IS2 in *A. nidulans* and bidirectional histone promoters, we integrate different version of CYP450s, Laccases, Manganese peroxidases, and lignin peroxidases.
Having four different places to insert the genes gives a lot of different combinations, but there could have been even more.
For instance, we did not change the terminators, but kept them constant so that the same promoter always went with the same teminator.

Also, in some mutant the same gene is inserted multiple times in different sites. This could create genetic instability, however, as bidirectional promoters are used, recombination would only cause the promoter to be flipped, no loop-out of the genome.