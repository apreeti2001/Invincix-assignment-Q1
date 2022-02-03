# Invincix-assignment-Q1

1. A pharmaceutical company is trying to create a drug for a deadly virus. It turns out the RNA
complex of the virus is such that any drug that has a chemical composition that reads the
same from front and back is effective. However these compounds are hard to mine out of
large chemically complex compounds. Over time they realise that the largest sub compound
in a complex compound that satisfies the above condition is the best choice to treat the
disease caused by the virus.
For example:
If the complex chemical compound is** ‘DGAABBAAKGHV’** the best drug would be **‘AABBAA’**
Explanation:
In the given complex chemical compound ‘DGAABBAAKGHV’ the following strings satisfy the
condition of being read the same from front and back
AA
BB
ABBA
AABBAA
However, AABBAA being the largest of them all, that would be the correct solution.
Ask
Based on the above requirement write a program for the above scenario that can help
scientists of this company to mine the perfect drug.
Input
1. Complex compound as a string
Output
1. Best drug that can be taken out from the given complex compound.
