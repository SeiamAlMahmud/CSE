Below is a deeper dive into the key concepts from the Set Notation lecture, followed by 50 practice questions with detailed answers.

---

## Deepened Explanation of Key Concepts

### 1. What Is a Set?

A **set** is a well-defined collection of distinct objects, called **elements**. For instance,

```
A = {1, 2, 3}  
```

denotes the set whose elements are 1, 2, and 3. Curly braces `{ }` are used in **roster notation** to list elements explicitly .

### 2. Membership: “∈” and “∉”

* $x \in A$ means “$x$ is an element of $A$.”
* $x \notin A$ means “$x$ is not an element of $A$.”
  E.g.
  $\,a \in \{a,b,c\}$ is true, whereas $\,d \notin \{a,b,c\}$ is also true .

### 3. The Empty Set

The **empty set**, denoted $\varnothing$ or `{}`, contains no elements.
E.g. in
$\,A = \{1, b, \{x,y,z\}, \varnothing\}$,
one of the elements is itself the empty set .

### 4. Set‐Builder Notation

Instead of listing elements, one may describe them by a property:

$$
A = \{\,x \in \mathbb{N}: \exists\,n\in\mathbb{N}\,(x = 2n)\}
$$

reads “$A$ is the set of all even natural numbers.” Equivalently,
(,A = {x: x\text{ is even}}\” .

### 5. Equality of Sets

Two sets are **equal** if they have exactly the same elements, regardless of order:
$\,\{1,2,3\} = \{2,1,3\}$ .

### 6. Subsets and Proper Subsets

* $A \subseteq B$ means every element of $A$ is in $B$.
* $A \subset B$ sometimes denotes a **proper subset**, i.e. $A\subseteq B$ but $A\neq B$.
  E.g. if $A=\{1,2,3\}$ and $B=\{1,2,3,4\}$, then $A\subset B$ .

### 7. Power Set

The **power set** $\mathcal{P}(A)$ is the set of *all* subsets of $A$.
E.g. if $A=\{1,2,3\}$, then
$\mathcal{P}(A)=\{\varnothing,\{1\},\{2\},\{3\},\{1,2\},\{1,3\},\{2,3\},\{1,2,3\}\}$ .

### 8. Cardinality

The **cardinality** $|A|$ of a set $A$ is the number of elements in $A$.
E.g. if $A=\{23,24,\dots,38\}$, $|A|=16$. For $B=\{1,\{2,3,4\},\varnothing\}$, $|B|=3$ .

### 9. Union and Intersection

* **Union**: $A\cup B=\{x : x\in A\lor x\in B\}$.
* **Intersection**: $A\cap B=\{x : x\in A\land x\in B\}$.
  E.g. $x\in A\cup B$ means “$x$ is in $A$ or in $B$” .

### 10. Set Difference and Complement

* **Set Difference**

  $$
    A \setminus B \;=\;\{\,x : x \in A \;\wedge\; x \notin B\}\,.
  $$

  In words: “the difference of $A$ and $B$” is the set of all elements that lie in $A$ but **not** in $B$.

  **Example.**
  Let $A=\{1,2,3,4\}$ and $B=\{3,4,5\}$.

  $$
    A\setminus B \;=\;\{1,2\}.
  $$

* **Complement** (relative to a universe $U$)

  $$
    A^c \;=\; U\setminus A \;=\;\{\,x \in U : x\notin A\}\,.  
  $$

  In other words, the complement of $A$ is everything in the universal set $U$ that is **not** in $A$.

  **Example.**
  If $U=\{1,2,3,4,5,6\}$ and $A=\{2,3,5\}$, then

  $$
    A^c \;=\;\{1,4,6\}\,.  
  $$

---

### 11. Cartesian Product

$$
  A \times B \;=\;\{\, (a,b) : a \in A,\; b \in B\}\,.
$$

This is the set of *ordered pairs* formed by taking each element of $A$ together with each element of $B$.  If $\lvert A\rvert = m$ and $\lvert B\rvert = n$, then $\lvert A\times B\rvert = m\times n$.

**Example.**
Let $A=\{1,2\}$ and $B=\{3,4,5\}$.

$$
  A \times B 
  = \{(1,3),(1,4),(1,5),(2,3),(2,4),(2,5)\},
$$

which has $2\times 3 = 6$ ordered pairs.

---

### 12. Venn Diagrams

A **Venn diagram** is a visual representation of sets and their relationships, drawn within a rectangle denoting the *universal set* $U$.  Each set is shown as a circle (or other simple shape) inside $U$, and overlaps between circles indicate intersections.

#### 12.1 Fundamental Rules

1. **Universal Set $(U)$**
   Draw a rectangle labeled $U$; it contains *all* elements under consideration.

2. **Individual Sets**
   Represent each set (e.g. $A$, $B$, $C$) by a distinct circle (or oval) inside the rectangle.  Label the circle with the set’s name.

3. **Overlap = Intersection**
   Where two circles overlap is precisely the region of their intersection, $A\cap B$.

4. **Disjoint Sets**
   If $A\cap B=\varnothing$, their circles do not overlap.

5. **Shading/Highlighting**
   To illustrate a particular operation (union, difference, complement, etc.), shade only the region(s) corresponding to that operation.

#### 12.2 Depicting Common Operations

| Operation                | Notation                | Venn-Diagram Shading                                      |
| ------------------------ | ----------------------- | --------------------------------------------------------- |
| **Union**                | $A \cup B$              | Shade all of $A$ **and** all of $B$.                      |
| **Intersection**         | $A \cap B$              | Shade only the overlapping region of $A$ and $B$.         |
| **Difference**           | $A \setminus B$         | Shade the part of $A$ *excluding* the overlap with $B$.   |
| **Complement**           | $A^c$ or $U\setminus A$ | Shade everything in $U$ *outside* the circle for $A$.     |
| **Symmetric Difference** | $A \triangle B$         | Shade the regions in $A$ or $B$, but *not* their overlap. |

#### 12.3 Practical Tips

* **Label Clearly**: Write each set’s name inside its circle, and label the rectangle with $U$.
* **Consistent Shapes**: Use circles (or ovals) of similar size for clarity.
* **Light Shading**: Apply a light fill or hatching to avoid obscuring boundaries and labels.
* **Multiple Sets**: For three or more sets, ensure every pairwise and triple overlap region is distinct and recognizable.
* **Annotations**: If helpful, write a small roster or set-builder notation beside the diagram to remind viewers of the exact contents of each region.

---

By combining these conventions and tips, Venn diagrams become a powerful way to **visualize** and **reason about** set-theoretic operations and relationships at a glance.


---

## 50 Practice Questions & Answers

1. **Define a set and give two examples.**

   **Answer:** A set is a collection of distinct elements. Examples: $\{a,b,c\}$, $\{1,2,3,4\}$.

2. **What is the empty set?**

   **Answer:** The set with no elements, denoted $\varnothing$ or `{}`.

3. **Translate $\{x \in \mathbb{Z}: x^2<9\}$ into roster form.**

   **Answer:** $\{-2,-1,0,1,2\}$.

4. **List the elements of $\mathcal{P}(\{a,b\})$.** 

   **Answer:** $\{\varnothing,\{a\},\{b\},\{a,b\}\}$.

5. **If $A=\{1,2,3\}$ and $B=\{2,3,4,5\}$, find $A\cup B$.**

   **Answer:** $\{1,2,3,4,5\}$.

6. **Find $A\cap B$ for the sets in Q5.**

   **Answer:** $\{2,3\}$.

7. **Compute $A\setminus B$ for the sets in Q5.**

   **Answer:** $\{1\}$.

8. **Compute $B\setminus A$ for the sets in Q5.**

   **Answer:** $\{4,5\}$.

9. **What does $\{x: x>0\}\subseteq\mathbb{Z}$ denote?**

   **Answer:** Every positive integer is an integer; so the statement is true.

10. **Are $\{1,2\}$ and $\{2,1\}$ equal sets?**

    **Answer:** Yes, order does not matter.

11. **Give an example where $A\subset B$ but $A\neq B$.**

    **Answer:** $A=\{1,2\}$, $B=\{1,2,3\}$.

12. **State the power set of $\{1,2,3\}$.**

    **Answer:** Eight subsets: $\varnothing,\{1\},\dots,\{1,2,3\}$.

13. **What is $|\{a,b,c,d\}|$?**

    **Answer:** 4.

14. **Find $\{x:\exists n\in\mathbb{N},x=3n\}$ in roster notation up to $15$.**

    **Answer:** $\{0,3,6,9,12,15\}$.

15. **Explain the difference between subset $(\subseteq)$ and proper subset $(\subset)$.**

    **Answer:** $\subseteq$ allows equality; $\subset$ excludes equality.

16. **If $U=\{1..10\}$ and $A=\{2,4,6\}$, what is $A^c$?**

    **Answer:** $\{1,3,5,7,8,9,10\}$.

17. **Compute $\{1,2,3\}\times\{a,b\}$.**

    **Answer:** $\{(1,a),(1,b),(2,a),(2,b),(3,a),(3,b)\}$.

18. **Prove $\varnothing\subseteq A$ for any set $A$.**

    **Answer:** Vacuously true since there is no element in $\varnothing$ to violate membership.

19. **Is $\{1\}\in\mathcal{P}(\{1,2\})$?**

    **Answer:** Yes, $\{1\}$ is one of its subsets.

20. **Is $\{1\}\subseteq\mathcal{P}(\{1,2\})$?**

    **Answer:** No, $\{1\}$ is not a set of subsets.

21. **Find $\mathcal{P}(\varnothing)$.**

    **Answer:** $\{\varnothing\}$.

22. **Calculate $|\mathcal{P}(\{a,b,c\})|$.**

    **Answer:** $2^3 = 8$.

23. **Express $\{2,4,6,\dots,20\}$ in set‐builder notation.**

    **Answer:** $\{x\in\mathbb{N}:x=2n,1\le n\le10\}$.

24. **If $A\cup B=U$ and $A\cap B=\varnothing$, describe $B$.**

    **Answer:** $B$ is the complement of $A$ in $U$.

25. **Show that $A\cap(A\cup B)=A$.**

    **Answer:** Use distributive laws or element‐wise argument.

26. **Are the sets $\{1,2\}$ and $\{1,2,\{1,2\}\}$ equal?**

    **Answer:** No, the latter has an extra element $\{1,2\}$.

27. **List all subsets of $\{a,b,c,d\}$ of cardinality 2.**

    **Answer:** $\{a,b\},\{a,c\},\{a,d\},\{b,c\},\{b,d\},\{c,d\}$.

28. **If $|A|=3$ and $|B|=4$ with $|A\cap B|=2$, find $|A\cup B|$.**

    **Answer:** $|A\cup B|=3+4-2=5$.

29. **What is the complement of the complement of $A$?**

    **Answer:** $(A^c)^c = A$.

30. **Describe $\{x:x\notin A\}$ in words.**

    **Answer:** The set of all elements not in $A$, i.e. the complement of $A$.

31. **Compute $\{1,2,3,4\}\setminus\{2,3\}$.**

    **Answer:** $\{1,4\}$.

32. **Verify $(A\cup B)^c = A^c\cap B^c$.**

    **Answer:** De Morgan’s law.

33. **Verify $(A\cap B)^c = A^c\cup B^c$.**

    **Answer:** De Morgan’s second law.

34. **Give an example of infinite set notation.**

    **Answer:** $\mathbb{N} = \{1,2,3,\dots\}$.

35. **What is $\{x: x^2=2\}$?**

    **Answer:** Empty set in $\mathbb{Z}$, $\{\sqrt2,-\sqrt2\}$ in $\mathbb{R}$.

36. **State whether $\mathcal{P}(A\cap B)=\mathcal{P}(A)\cap\mathcal{P}(B)$.**

    **Answer:** True, since subsets of $A\cap B$ are exactly those common to both.

37. **Are $\mathcal{P}(A)\cup\mathcal{P}(B)=\mathcal{P}(A\cup B)$?**

    **Answer:** Generally false (some subsets of $A\cup B$ use elements from both).

38. **Compute $\{x:2\le x\le5\}\cap\{x:x\text{ odd}\}$.**

    **Answer:** $\{3,5\}$.

39. **Draw a Venn diagram for $A\cup(B\cap C)$.**

    **Answer:** Shade entire $A$ plus the region where $B$ and $C$ overlap.

40. **If $A\subseteq B$, show $A\cup B=B$.**

    **Answer:** Because adding a subset to its superset yields the superset.

41. **If $A\subseteq B$, show $A\cap B=A$.**

    **Answer:** Intersection with a superset yields the smaller set.

42. **Example of two disjoint sets?**

    **Answer:** $\{1,2\}$ and $\{3,4\}$.

43. **Example of two non-disjoint sets?**

    **Answer:** $\{1,2\}$ and $\{2,3\}$.

44. **Compute $\{1,2,3\}\times\{4,5\}\times\{6\}$.**

    **Answer:** Six triples: $(1,4,6),(1,5,6),(2,4,6),(2,5,6),(3,4,6),(3,5,6)$.

45. **Define an ordered pair and contrast with unordered sets.**

    **Answer:** $(a,b)\neq(b,a)$ in general, unlike sets.

46. **If $A = \{1,3,5\}$, $B = \{2,3,4\}$, list $A\triangle B$.**

    **Answer:** Symmetric difference: $\{1,2,4,5\}$.

47. **Prove $A\triangle B = (A\cup B)\setminus(A\cap B)$.**

    **Answer:** Follows from definition of symmetric difference.

48. **Show $\varnothing\cup A = A$.**

    **Answer:** Union with empty set leaves $A$ unchanged.

49. **Show $\varnothing\cap A = \varnothing$.**

    **Answer:** No element can be in both $A$ and the empty set.

50. **List all subsets of $\{1,2,3,4\}$ that contain 2 and 3.**

    **Answer:** Any subset of $\{1,2,3,4\}$ that includes 2 and 3; namely
    $\{2,3\},\{1,2,3\},\{2,3,4\},\{1,2,3,4\}$.


---

Feel free to work through these questions, and let me know if you’d like hints or further clarification on any topic!
