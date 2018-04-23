# Effect-algebras

This repository contains lists of **generalized pseudoeffect algebras** (GPE-algebras). A GPE-algebra is
a cancellative conjugative partial monoid.

**cancellative**: x+y=x+z -> y=z  and  x+z=y+z -> x=y

**conjugative**:  ∃z (x+z=y) <-> ∃z (z+x=y)

**partial monoid**: (x+y)+z=x+(y+z)  and  x+0=x=0+x  where either both sides are defined and equal or both are undefined.

The file "gpe-algebras1-9.txt" contains a list of all GPE-algebras with 1 through 9 elements up to isomorphism.
There are a total of 12996 gpe-algebras with cardinality from 1 to 9.

The file "gpe-algebras10.txt" contains a list of all GPE-algebras with 10 elements up to isomorphism.
There are a total of 322918 gpe-algebras with cardinality 10. A gzipped version is also available.

The algebras of each cardinality are numbered from 1 to n. Algebras are stored as n-by-n tables (lists of lists),
followed by their number and a 3-character string indicating if the algebra satisfies orthogonality (O),
commutativity (C), and/or consistency (c). In the table the value 0 is used to denote "undefined" for all
entries except 0+0=0 (where it denotes the additive identity element).

A GPE-algebra is **orthogonal** if its natural order has a top element, it is **commutative** if x+y = y+x, and it
is **consistent** if x != 0 implies x+x is undefined (=0 in these files).

**Effect algebras** are orthogonal commutative GPE-algebras.

**Generalized effect algebras** are commutative GPE-algebras.

**Pseudoeffect algebras** are orthogonal GPE-algebras.

**Orthoalgebras** are orthogonal commutative consistent GPE-algebras.

**Generalized orthoalgebras** are commutative consistent GPE-algebras.

**Pseudo-orthoalgebras** are orthogonal consistent GPE-algebras.
