
## Deep Explanation of Set Operations via Venn Diagrams

### 1. Two-Set Inclusion–Exclusion

For any two finite sets $A$ and $B$:

$$
n(A\cup B) \;=\; n(A) + n(B) - n(A\cap B)
$$

* **Derivation via Venn diagram**: you count all of $A$ and all of $B$, but elements in the overlap $A\cap B$ get counted twice, so subtract one copy .
* **Disjoint case**: if $A\cap B=\varnothing$, then $n(A\cup B)=n(A)+n(B)$ since there is no overlap .

An equivalent breakup is

$$
n(A\cup B) \;=\; n(A\setminus B) \;+\; n(B\setminus A)\;+\; n(A\cap B)
$$

where $A\setminus B$ is “only-$A$” and $B\setminus A$ is “only-$B$” .

### 2. Three-Set Inclusion–Exclusion

For three finite sets $A$, $B$, and $C$:

$$
\begin{aligned}
n(A\cup B\cup C)
&= n(A)+n(B)+n(C) \\
&\quad -\,n(A\cap B)-n(B\cap C)-n(C\cap A) \\
&\quad +\,n(A\cap B\cap C).
\end{aligned}
$$

* **Logic via Venn diagram**: start with all singletons, subtract each pairwise overlap (because each was added twice), then add back the triple overlap (because it was subtracted three times) .
* **Disjoint-all-three case**: if no two overlap then all pairwise and triple intersections vanish and $n(A\cup B\cup C)=n(A)+n(B)+n(C)$ .

### 3. Counting “Only” Regions

From the two-set Venn diagram:

$$
\begin{cases}
n(\text{only-}A) = n(A) - n(A\cap B),\\
n(\text{only-}B) = n(B) - n(A\cap B).
\end{cases}
$$

This isolates the non-overlap portions .

For three sets:

$$
n(\text{only-}A)
= n(A)\;-\;\bigl[n(A\cap B)+n(A\cap C)\bigr]\;+\;n(A\cap B\cap C),
$$

and similarly for only-$B$ and only-$C$ .  Pair-only counts (e.g. “$A$ and $B$ only”) are given by

$$
n(A\cap B) - n(A\cap B\cap C),
$$

and analogously for the other pairs .

---

## 50 Practice Questions & Answers

1. **What is $n(A\cup B)$ for two finite, not-necessarily-disjoint sets?**

   **Answer:** $n(A)+n(B)-n(A\cap B)$.

2. **If $A\cap B=\emptyset$, what simplifies in the above formula?**

   **Answer:** $n(A\cup B)=n(A)+n(B)$.

3. **Express $n(A\cup B)$ in terms of “only-A”, “only-B”, and “A∩B.”**

   **Answer:** $n(A\setminus B)+n(B\setminus A)+n(A\cap B)$.

4. **Define $A\setminus B$.**

   **Answer:** $\{x:x\in A\text{ and }x\notin B\}$.

5. **Compute “only-A” count: $n(A\setminus B)$.**

   **Answer:** $n(A)-n(A\cap B)$.

6. **What is $n(A\cap B)$ visually on a Venn diagram?**

   **Answer:** The shaded overlap of circles A and B.

7. **State the three-set inclusion–exclusion formula.**

   **Answer:** $n(A)+n(B)+n(C)-n(A∩B)-n(B∩C)-n(C∩A)+n(A∩B∩C)$.

8. **Why do we add back $n(A∩B∩C)$ in the three-set formula?**

   **Answer:** It was subtracted three times when removing pairwise overlaps.

9. **Compute $n(A∪B∪C)$ if all intersections vanish.**

   **Answer:** $n(A)+n(B)+n(C)$.

10. **Define the complement $A^c$ in universe $U$.**

    **Answer:** $U\setminus A=\{x\in U:x\notin A\}$.

11. **If $n(U)=100$ and $n(A)=30$, what is $n(A^c)$?**

    **Answer:** $100-30=70$.

12. **Give a roster-notation example of $A∪B$.**

    **Answer:** If $A=\{1,2\}$, $B=\{2,3\}$, then $A∪B=\{1,2,3\}$.

13. **Give a roster-notation example of $A∩B$.**

    **Answer:** With the same, $A∩B=\{2\}$.

14. **What is the cardinality of $\{a,b,c\}$?**

    **Answer:** 3.

15. **If $|A|=5,|B|=7,|A∩B|=2$, find $|A∪B|$.**

    **Answer:** $5+7-2=10$.

16. **Compute $|A∪B∪C|$ when $|A|=3,|B|=4,|C|=5$ and all pair/triple intersections are empty.**

    **Answer:** $3+4+5=12$.

17. **Let $|A|=10,|B|=8,|C|=6,|A∩B|=4,|B∩C|=2,|C∩A|=3,|A∩B∩C|=1$. Compute $|A∪B∪C|$.**

    **Answer:** $10+8+6 -4-2-3 +1 =16$.

18. **In two sets, show why $A\setminus B$ and $B\setminus A$ are disjoint.**

    **Answer:** By definition, they share no elements.

19. **True or false: $\varnothing\subseteq A$ for any A.**

    **Answer:** True (vacuously).

20. **True or false: $\{1\}\subset\{1\}$.**

    **Answer:** False; that’s equality, not a proper subset.

21. **Define symmetric difference $A\triangle B$.**

    **Answer:** $(A∪B)\setminus(A∩B)$.

22. **List elements of $\{1,2,3\}\triangle\{2,3,4\}$.**

    **Answer:** $\{1,4\}$.

23. **For sets $A=\{1,2,3\},B=\{2,3,4\},C=\{3,4,5\}$, find elements in exactly two sets.**

    **Answer:** Elements in pair-only:

    * A∩B only: $\{2,3\}\setminus C = \{2\}$
    * B∩C only: $\{3,4\}\setminus A = \{4\}$
    * A∩C only: $\{3\}\setminus B = ∅$.

24. **Compute “exactly one of A,B,C” in the previous.**

    **Answer:**

    * only-A: $\{1\}$
    * only-B: $\{4\}$ (since 2,3 are in overlaps)
    * only-C: $\{5\}$.

25. **Give the Venn-diagram shading for $A\cap(B∪C)$.**

    **Answer:** Shade the part of A that overlaps with either B or C.

26. **Prove $A\cap(B∪C)=(A∩B)\cup(A∩C)$.**

    **Answer:** Follows from distributivity; check membership both ways.

27. **Prove $A∪(B∩C)=(A∪B)\cap(A∪C)$.**

    **Answer:** Another distributive law; check via element-wise argument.

28. **What is a Cartesian product $A×B$?**

    **Answer:** All ordered pairs $(a,b)$ with $a∈A,b∈B$.

29. **If $A=\{1,2\},B=\{x,y\}$, list $A×B$.**

    **Answer:** $\{(1,x),(1,y),(2,x),(2,y)\}$.

30. **Define the power set $\mathcal P(A)$.**

    **Answer:** The set of *all* subsets of $A$.

31. **List $\mathcal P(\{a,b\})$.**

    **Answer:** $\{\emptyset,\{a\},\{b\},\{a,b\}\}$.

32. **What is $|\mathcal P(A)|$ if $|A|=n$?**

    **Answer:** $2^n$.

33. **Find $|\mathcal P(\{1,2,3\})|$.**

    **Answer:** $2^3=8$.

34. **Compute the complement of $\{1,2\}$ in $U=\{1,2,3,4\}$.**

    **Answer:** $\{3,4\}$.

35. **Given $n(A)=30,n(B)=40$, and $n(A\cap B)=10$, find $n(A\setminus B)$.**

    **Answer:** $30-10=20$.

36. **In a class of 50, 20 like math only, 15 like science only, and 10 like both. How many like at least one?**

    **Answer:** $20+15+10=45$.

37. **In that class, how many like neither?**

    **Answer:** $50-45=5$.

38. **Use inclusion–exclusion to count at least one in three sets: 20,25,30; overlaps 5,7,6; triple 2.**

    **Answer:**
    $20+25+30 -5-7-6 +2 =59$.

39. **A survey: 65 play football,45 hockey,20 both. Total students?**

    **Answer:** Insufficient: we need those who play neither.

40. **If 100 students surveyed, with those numbers above, how many play neither?**

    **Answer:** $100 - (65+45-20)=10$.

41. **In a three-course survey (64,94,58; overlaps 28,26,22; triple 14), total taking ≥1?**

    **Answer:**
    $64+94+58 -28-26-22 +14 =154$.

42. **In that survey, how many take exactly one course?**

    **Answer:**

    * only M: $64-(28+26-14)=24$
    * only C: $94-(26+22-14)=60$
    * only P: $58-(28+22-14)=22$
      Sum = 106.

43. **Explain why distributions of overlaps partition the universal set.**

    **Answer:** Each element falls into exactly one of the 2^n regions in an n-set Venn.

44. **How many regions in a 3-set Venn diagram?**

    **Answer:** $2^3=8$.

45. **Label all 8 regions symbolically for A, B, C.**

    **Answer:**
    $\emptyset;A\setminus(B∪C);\;B\setminus(A∪C);\;C\setminus(A∪B);\;(A∩B)\setminus C;\;(B∩C)\setminus A;\;(C∩A)\setminus B;\;A∩B∩C.$

46. **What is the region count for 4 sets?**

    **Answer:** $2^4=16$.

47. **True or false: $A\cup(A\cap B)=A$.**

    **Answer:** True (absorption law).

48. **True or false: $A\cap(A\cup B)=A$.**

    **Answer:** True.

49. **Describe how to use a Venn diagram to count elements satisfying “either A or B but not both.”**

    **Answer:** Shade the two non-overlap parts of A and B (the symmetric difference).

50. **Summarize the general recipe for deriving any n-set inclusion–exclusion.**

    **Answer:** Alternate sum of sizes of all k-wise intersections, $k=1$ to $n$, with signs $(−1)^{k-1}$.

---
