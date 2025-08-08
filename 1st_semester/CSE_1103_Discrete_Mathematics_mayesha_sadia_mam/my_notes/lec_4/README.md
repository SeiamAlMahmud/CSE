## 1. Venn Diagrams: The Big Picture

* **Universal set $U$**: Drawn as a rectangle, it contains every element under discussion.
* **Individual sets $A,B,C,\dots$**: Each is a circle (or oval) inside $U$.
* **Regions**:

  * **2 sets** ($A,B$) produce **4 regions**:

    1. Only-$A$
    2. Only-$B$
    3. $A\cap B$
    4. Neither (outside both circles)
  * **3 sets** ($A,B,C$) produce **8 regions**: each element of $U$ falls into exactly one of these.

Visually partitioning $U$ in this way is what lets us turn a word problem into simple algebra.

---

## 2. Generic “Recipe” for Any Venn-Diagram Problem

1. **Draw the Diagram**

   * Two sets: draw two overlapping circles in a rectangle.
   * Three sets: draw three overlapping circles so that every pair and the triple overlap is visible.

2. **Label Each Region with a Variable**

   * **Two sets**: let

     * $x =$ number in only-$A$
     * $y =$ number in only-$B$
     * $z =$ number in $A\cap B$
     * (optionally $w =$ neither, if you need it)
   * **Three sets**: let

     * $x,\,y,\,z =$ only-$A$, only-$B$, only-$C$
     * $u,\,v,\,w =$ $A\cap B$ only, $B\cap C$ only, $C\cap A$ only
     * $t =$ $A\cap B\cap C$
     * (optionally $r =$ none of the three)

3. **Write Equations from the Given Data**

   * For each set’s total:

     * Two sets:

       $$
         n(A)=x+z,\qquad n(B)=y+z.
       $$
     * Three sets:

       $$
       \begin{cases}
         n(A)=x+u+w+t,\\
         n(B)=y+u+v+t,\\
         n(C)=z+v+w+t.
       \end{cases}
       $$
   * For each pairwise overlap:

     * Two sets: $n(A\cap B)=z$.
     * Three sets:

       $$
         n(A\cap B)=u+t,\quad n(B\cap C)=v+t,\quad n(C\cap A)=w+t.
       $$
   * For the triple overlap (only in three-set problems): $n(A\cap B\cap C)=t$.
   * If you know the grand total in $U$, form

     $$
       n(U) \;=\; (\text{sum of all regions}) = x+y+z+u+v+w+t \;(\,+\,r\,).
     $$

4. **Solve, Step by Step**

   1. **Triple-overlap** $t$ is usually given or deduced first.
   2. **Pair-only** ($u,v,w$) by subtracting $t$ from each $n(A\cap B)$, etc.
   3. **Only-regions** ($x,y,z$) by subtracting overlaps from each $n(A)$, etc.
   4. **Neither-region** $r$ (if asked) by subtracting the sum of all drawn regions from $n(U)$.

5. **Answer the Question**

   * “How many play at least one?” → sum all regions except $r$.
   * “How many play exactly one?” → $x+y+z$ (in the three-set case).
   * “How many play neither?” → $r$.
   * And so on.

---

## 3. Worked Example 1: Two Sets (“Football vs. Hockey”)

> **Problem:** In a club of 100 members, 65 play football, 45 play hockey, and 20 play both.
>
> 1. How many play **at least one** of the two sports?
> 2. How many play **neither**?

**Step A. Draw & Label**

```
       [ only F ]    [  F∩H ]    [ only H ]    [ neither ]
          x             z           y            r
```

**Step B. Equations**

$$
\begin{cases}
x + z = n(F) = 65,\\
y + z = n(H) = 45,\\
z = n(F\cap H) = 20,\\
x + y + z + r = n(U) = 100.
\end{cases}
$$

**Step C. Solve**

1. $z=20.$
2. $x = 65 - 20 = 45.$
3. $y = 45 - 20 = 25.$
4. $r = 100 - (x+y+z) = 100 - (45+25+20) = 10.$

**Step D. Answer**

1. **At least one** = $x+z+y = 45+20+25 = 90.$
2. **Neither** = $r = 10.$

---

## 4. Worked Example 2: Three Sets (“Football, Hockey, Cricket”)

> **Problem:** Among 100 students:
>
> * 65 play football, 45 hockey, 42 cricket
> * 20 play football & hockey, 25 football & cricket, 15 hockey & cricket
> * 8 play all three
>
> (a) How many play at least one game?
> (b) How many play exactly one game?

**Step A. Draw & Label**

```
 only-F  only-H  only-C   F∩H only  H∩C only   C∩F only   F∩H∩C
    x       y       z        u          v           w        t
```

**Step B. Equations**

$$
\begin{cases}
x + u + w + t = 65,\\
y + u + v + t = 45,\\
z + v + w + t = 42,\\
u + t = 20,\quad v + t = 25,\quad w + t = 15,\\
t = 8.
\end{cases}
$$

**Step C. Solve**

1. $t=8.$
2. $u = 20-8=12,\;v=25-8=17,\;w=15-8=7.$
3. $x=65-(u+w+t)=65-(12+7+8)=38,$
   sorry—recompute: $65-27=38$.
4. $y=45-(u+v+t)=45-(12+17+8)=8,$
   sorry—recompute: $45-37=8$.
5. $z=42-(v+w+t)=42-(17+7+8)=10.$

**Step D. Check Total**
Sum of regions = $x+y+z+u+v+w+t = 38+8+10+12+17+7+8 = 100.$

**Step E. Answers**
(a) **At least one** = sum of all seven positive regions = 100 (so nobody plays none).
(b) **Exactly one** = $x + y + z = 38 + 8 + 10 = 56.$

---

## 5. Why This Works

* **Visual bookkeeping** of every possible “place” an element can sit in $U$.
* **No double-counting**: each region is disjoint by construction.
* **Equations** simply match the story’s counts to sums of region-variables.
* Once you’ve practiced this method a few times, you’ll solve any of the 50 questions in 3–5 minutes.

---


Below is a chapter-by-chapter deep dive into the key **properties and laws** of set operations—each grounded in Venn-diagram intuition and the handout—followed by **50 practice questions and answers** covering every topic.


<br />
<br />

---
---
---

<br />
<br />

# I. Commutative Laws

> **Definition:**
>
> * $A\cup B = B\cup A$  (union)
> * $A\cap B = B\cap A$  (intersection)&#x20;

**Venn-Diagram Insight:**
Swapping the labels of the two circles does not change the shaded region for either union or intersection—hence order doesn’t matter.

---

# II. Associative Laws

> **Definition:**
>
> * $A\cup (B\cup C) = (A\cup B)\cup C$
> * $A\cap (B\cap C) = (A\cap B)\cap C$&#x20;

**Venn-Diagram Insight:**
Grouping of three circles—whether you combine $B$ and $C$ first or $A$ and $B$ first—yields the same overall shaded area for union (all three) or intersection (common to all three).

---

# III. Distributive Laws

> **Definition:**
>
> * $A\cap (B\cup C) = (A\cap B)\cup (A\cap C)$
> * $A\cup (B\cap C) = (A\cup B)\cap (A\cup C)$&#x20;

**Venn-Diagram Insight:**
To find $A\cap(B\cup C)$, shade the parts of $A$ that overlap with either $B$ or $C$; equivalently, shade the union of $A\cap B$ and $A\cap C$.  The second law follows by duality.

---

# IV. De Morgan’s Laws for Set Difference

> **Definition (any sets $A,B,C$):**
>
> 1. $A\setminus(B\cup C) = (A\setminus B)\;\cap\;(A\setminus C)$
> 2. $A\setminus(B\cap C) = (A\setminus B)\;\cup\;(A\setminus C)$&#x20;

**Venn-Diagram Insight:**

* Removing everything in $B\cup C$ from $A$ leaves only those bits of $A$ outside both $B$ and $C$, i.e. the intersection of “outside $B$” and “outside $C$.”
* Removing everything in $B\cap C$ from $A$ leaves bits of $A$ that avoid at least one of $B$ or $C$, hence the union.

---

# V. De Morgan’s Laws for Complementation

> **Definition (universal set $U$):**
>
> * $(A\cup B)' = A'\cap B'$
> * $(A\cap B)' = A'\cup B'$&#x20;

**Venn-Diagram Insight:**
The complement of the union is the part of $U$ outside both circles (intersection of the outsides); dually, the complement of the intersection is the part of $U$ that lies outside at least one circle (union of the outsides).

---

# 50 Practice Questions & Answers

### A. Commutative & Associative (Q1–10)

1. State the union-commutative law.
   **A:** $A\cup B=B\cup A$.

2. State the intersection-commutative law.
   **A:** $A\cap B=B\cap A$.

3. Explain why union is commutative using a Venn diagram.
   **A:** Swapping circle labels leaves combined area unchanged.

4. State the union-associative law.
   **A:** $A\cup(B\cup C)=(A\cup B)\cup C$.

5. State the intersection-associative law.
   **A:** $A\cap(B\cap C)=(A\cap B)\cap C$.

6. Why does grouping not matter for intersections of three sets?
   **A:** The common region among all three circles is the same regardless of pairing.

7. Give a roster-notation example verifying $A\cup(B\cup C)=(A\cup B)\cup C$.
   **A:** Let $A=\{1\},B=\{2\},C=\{3\}$, both sides = $\{1,2,3\}$.

8. Is $(A\cup B)\cup C=\;A\cup(B\cup C)$ always true if sets are infinite?
   **A:** Yes—associativity holds for all sets.

9. Provide a counterexample if someone claimed $A\cup B\neq B\cup A$.
   **A:** No counterexample exists; it's always true.

10. In context of functions, why is associativity of union important?
    **A:** We can group domains arbitrarily when combining relations.

### B. Distributive Laws (Q11–20)

11. State $A\cap(B\cup C)$ distributive law.
    **A:** $= (A\cap B)\cup(A\cap C)$.

12. State $A\cup(B\cap C)$ distributive law.
    **A:** $= (A\cup B)\cap(A\cup C)$.

13. Verify $A\cap(B\cup C)=(A\cap B)\cup(A\cap C)$ for $A=\{1,2\},B=\{2\},C=\{3\}$.
    **A:** LHS={2}, RHS={2}.

14. Does distributivity hold when one of the sets is empty?
    **A:** Yes: e.g. $A\cap(\varnothing\cup C)=A\cap C$.

15. Show via Venn that $A\cup(B\cap C)$ shading = $(A\cup B)\cap(A\cup C)$.
    **A:** Shade regions in either A or the overlap of B and C.

16. Give an example where $B\cap(C\cup D)\neq(B\cap C)\cup D$.
    **A:** Invalid: by law, these are equal only if parentheses change membership.

17. Is $(A\cap B)\cup C = A\cap(B\cup C)$? True or false?
    **A:** False in general.

18. Prove $(A\cup B)\cap C = (A\cap C)\cup(B\cap C)$.
    **A:** Distribute $\cap$ over $\cup$; symmetric to Q11.

19. In logic terms, what does distributivity correspond to?
    **A:** $P\land(Q\lor R)\equiv(P\land Q)\lor(P\land R)$.

20. Why is distributivity crucial for simplifying complex set expressions?
    **A:** Allows factoring or expanding parts to simpler unions/intersections.

### C. De Morgan’s Laws for Difference (Q21–30)

21. State $A\setminus(B\cup C)$.
    **A:** $(A\setminus B)\cap(A\setminus C)$.

22. State $A\setminus(B\cap C)$.
    **A:** $(A\setminus B)\cup(A\setminus C)$.

23. For $A=\{1,2,3\},B=\{2\},C=\{3\}$, compute $A\setminus(B\cup C)$.
    **A:** $\{1\}$.

24. Compute $(A\setminus B)\cap(A\setminus C)$ with same sets.
    **A:** $\{1\}$.

25. Compute $A\setminus(B\cap C)$ with $B,C$ disjoint.
    **A:** $A\setminus\varnothing = A.$

26. Show via Venn that difference-De Morgan holds graphically.
    **A:** Shade only parts of A outside any overlap with B or C.

27. If $B\subseteq C$, simplify $A\setminus(B\cup C)$.
    **A:** $A\setminus C.$

28. If $C\subseteq B$, what is $A\setminus(B\cap C)$?
    **A:** $A\setminus B.$

29. Provide a real-world analogy for $A\setminus(B\cup C)$.
    **A:** “Students who passed Math **but neither** Physics nor Chemistry.”

30. How does difference interact with infinite sets?
    **A:** Same laws hold; remove all elements in union/intersection.

### D. De Morgan’s Laws for Complement (Q31–40)

31. State $(A\cup B)' = A'\cap B'$.
    **A:** Everything outside both A and B.

32. State $(A\cap B)' = A'\cup B'$.
    **A:** Everything outside at least one of A or B.

33. In a universe of people, let $A=$ “likes tea”, $B=$ “likes coffee.”  Interpret $(A\cup B)'$.
    **A:** People who like neither tea nor coffee.

34. Interpret $(A\cap B)'$ in same context.
    **A:** People who dislike either tea or coffee (or both).

35. Verify $(A\cup B)' = A'\cap B'$ roster-wise for $U=\{1,2,3\},A=\{1\},B=\{2\}$.
    **A:** LHS $=\{3\}$, RHS $=\{3\}$.

36. Why is complement-De Morgan essential in logical circuit design?
    **A:** For implementing NOT(OR) as AND of NOTs, etc.

37. Show using Venn that complement-De Morgan flips shading inside→outside.
    **A:** Shade outside each circle and take intersection/union accordingly.

38. If $U=\{1,2,3,4\},A=\{1,2\},B=\{2,3\}$, list $(A\cap B)'$.
    **A:** $\{1,4\}\cup\{? \}$ actually $\{1,4\}\cup\{3,4\}=\{1,3,4\}$.

39. Compute $(A\cup B)'$ for same $U,A,B$.
    **A:** $\{4\}$.

40. Does complement-De Morgan require finiteness?
    **A:** No—holds in all Boolean algebras.

### E. Mixed & Proof-by-Venn (Q41–50)

41. Prove commutativity of union by listing elements in roster form.
    **A:** Show both lists sorted match.

42. Prove associativity of intersection by double application of commutativity.
    **A:** Rearrange groupings stepwise.

43. Use a Venn diagram to prove distributivity of $\cap$ over $\cup$.
    **A:** Shade A inside B∪C equals union of A∩B and A∩C.

44. Show that $(A\setminus B)\cup(B\setminus A)=A\triangle B$.
    **A:** Definition of symmetric difference.

45. How many distinct regions are there in a 3-set Venn?
    **A:** $2^3=8.$

46. Label all 8 regions in terms of set operations (e.g. only-A, A∩B∩C, etc.).
    **A:** $\varnothing;\,A\setminus(B\cup C);\dots;A\cap B\cap C.$

47. For four sets, how many regions?
    **A:** $2^4=16.$

48. Use Venn to derive the two-set inclusion–exclusion formula.
    **A:** Count A+B minus overlap.

49. Use Venn to derive the three-set inclusion–exclusion formula.
    **A:** Sum singles, subtract pairs, add triple.

50. Summarize in one sentence why Venn diagrams are powerful for set laws.
    **A:** They translate algebraic identities into visual region-counting, making proofs intuitive.

---

Feel free to request worked-out diagrams or deeper walkthroughs for any specific question!
