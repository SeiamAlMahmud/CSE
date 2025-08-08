### 1. **Sets – Definition and Importance**

A **set** is a well-defined collection of distinct objects, considered as an object in its own right. A set can contain anything—numbers, letters, objects, or even other sets. The key characteristics of a set are:

* **Well-defined**: The elements must be clearly specified, so it's easy to determine whether something belongs to the set or not.
* **Distinct**: No repetitions of elements in a set. For example, the set of vowels in the English alphabet, A = {a, e, i, o, u}, does not repeat any letter.

#### Example:

* The set of odd numbers less than 10: A = {1, 3, 5, 7, 9}.
* The set of even numbers greater than 0 and less than 10: B = {2, 4, 6, 8}.

#### Important Notes:

* A set can be represented using **Roster/Tabular Form** or **Set Builder Notation**.
* **Roster/Tabular Form** lists all elements of the set explicitly.
* **Set Builder Notation** defines a set by a rule or property.

---

### 2. **Types of Sets**

* **Finite Set**: A set with a definite number of elements.

  * Example: A = {1, 2, 3, 4}.

* **Infinite Set**: A set with an infinite number of elements.

  * Example: N = {1, 2, 3, 4, 5, ...} (the set of natural numbers).

* **Equal Sets**: Two sets are equal if they contain exactly the same elements.

  * Example: A = {1, 2, 3} and B = {1, 2, 3} are equal.

* **Subset**: A set A is a subset of B if every element of A is also an element of B.

  * Example: If A = {1, 2}, and B = {1, 2, 3}, then A ⊆ B.

* **Proper Subset**: A set A is a proper subset of B if every element of A is in B, but B has at least one element not in A.

  * Example: A = {1, 2}, B = {1, 2, 3}, then A ⊂ B.

* **Universal Set**: The set of all possible elements, usually denoted as **U**.

  * Example: If you are working with integers, the universal set U might be the set of all integers.

* **Empty Set (Null Set)**: A set with no elements, denoted as **{}** or **Ø**.

  * Example: The set of natural numbers less than 1: Ø = {}.

---

### 3. **Set Operations**

#### 1. **Union (A ∪ B)**:

The **union** of two sets is the set of all elements that are in A, or in B, or in both.

* Example: If A = {1, 2, 3} and B = {3, 4, 5}, then A ∪ B = {1, 2, 3, 4, 5}.

#### 2. **Intersection (A ∩ B)**:

The **intersection** of two sets is the set of all elements that are in both A and B.

* Example: If A = {1, 2, 3} and B = {3, 4, 5}, then A ∩ B = {3}.

#### 3. **Difference (A - B)**:

The **difference** of two sets is the set of elements that are in A but not in B.

* Example: If A = {1, 2, 3} and B = {3, 4, 5}, then A - B = {1, 2}.

#### 4. **Complement (Aᶜ)**:

The **complement** of a set A contains all the elements in the universal set that are not in A.

* Example: If U = {1, 2, 3, 4, 5} and A = {1, 2}, then Aᶜ = {3, 4, 5}.

#### 5. **Symmetric Difference (A ∆ B)**:

The **symmetric difference** of two sets contains the elements that are in either A or B but not in both.

* Example: If A = {1, 2, 3} and B = {3, 4, 5}, then A ∆ B = {1, 2, 4, 5}.

---

### 4. **Set Cardinality**

The **cardinality** of a set refers to the number of elements in the set.

* **Finite Sets**: The cardinality is simply the count of elements.

  * Example: A = {1, 2, 3}, then |A| = 3.
* **Infinite Sets**: The cardinality is infinite.

  * Example: N = {1, 2, 3, 4, 5, ...}, then |N| = ∞.

To calculate the cardinality of a set with a known pattern (like an arithmetic progression), we use the formula:

$$
\text{Cardinality} = \frac{(\text{last element} - \text{first element})}{\text{common difference}} + 1
$$

#### Example:

* For A = {1, 4, 7, ..., 49}, the common difference is 3. Using the formula, you can calculate the cardinality easily.

---

### 5. **Set Theory Symbols**

These symbols are essential for writing set expressions and performing operations:

| Symbol | Meaning          | Example                                    |
| ------ | ---------------- | ------------------------------------------ |
| ∈      | Element of a set | 3 ∈ A means 3 is in set A                  |
| ⊆      | Subset           | A ⊆ B means A is a subset of B             |
| ∪      | Union            | A ∪ B means the union of sets A and B      |
| ∩      | Intersection     | A ∩ B means the intersection of A and B    |
| -      | Set Difference   | A - B means the difference of sets A and B |

---

### **Practice Questions**:

#### 1. Define a set and explain with examples. How are sets represented in set theory?

#### 2. Given sets:

* A = {1, 2, 3}
* B = {3, 4, 5}

Perform the following operations:

* Find A ∪ B
* Find A ∩ B
* Find A - B
* Find A ∆ B

#### 3. What is the cardinality of the set A = {2, 4, 6, ..., 50}? Show the steps.

#### 4. If A = {a, b, c}, find the power set of A.

#### 5. If A = {1, 2, 3} and B = {2, 3, 4}, prove that A ⊆ A ∪ B and A ∩ B ⊆ A.

#### 6. Explain the difference between **proper subset** and **subset** with examples.

---

### Short Tricks for Exam:

1. **Set Operations**: Always remember the properties of union, intersection, and difference. For example, the intersection of a set with itself is the set itself: A ∩ A = A.

2. **Cardinality Calculation**: For arithmetic sets, use the formula to avoid manually counting the elements.

3. **Use of Venn Diagrams**: Visualize union, intersection, and difference with Venn diagrams for better understanding.

---

### 1. **Define a set and explain with examples. How are sets represented in set theory?**

A **set** is a well-defined collection of distinct objects, considered as a single entity. The objects within a set are called **elements** or **members**. A set can contain numbers, letters, or other sets.

#### Example 1:

* A = {1, 2, 3, 4} is a set containing the integers 1, 2, 3, and 4.

#### Example 2:

* B = {a, b, c} is a set containing the letters 'a', 'b', and 'c'.

#### Representation of sets in set theory:

1. **Roster or Tabular Form**: All the elements of the set are listed explicitly.

   * Example: A = {1, 2, 3}
2. **Set Builder Notation**: The set is described by a property that its elements must satisfy.

   * Example: A = {x | x is an even number between 1 and 10}, which represents A = {2, 4, 6, 8}.

---

### 2. **Given sets:**

A = {1, 2, 3}
B = {3, 4, 5}

#### Find A ∪ B:

The **union** of two sets A and B is the set of all elements that are in A, or in B, or in both.

$$
A \cup B = \{1, 2, 3, 4, 5\}
$$

#### Find A ∩ B:

The **intersection** of two sets A and B is the set of elements that are in both A and B.

$$
A \cap B = \{3\}
$$

#### Find A - B:

The **difference** of two sets A and B (A - B) is the set of elements that are in A but not in B.

$$
A - B = \{1, 2\}
$$

#### Find A ∆ B:

The **symmetric difference** of two sets A and B is the set of elements that are in either A or B, but not in both.

$$
A \Delta B = \{1, 2, 4, 5\}
$$

---

### 3. **What is the cardinality of the set A = {2, 4, 6, ..., 50}? Show the steps.**

The set A = {2, 4, 6, ..., 50} consists of all even numbers from 2 to 50. This is an **arithmetic progression** with:

* First term = 2
* Common difference = 2
* Last term = 50

The formula for the cardinality (number of terms) of an arithmetic sequence is:

$$
\text{Cardinality} = \frac{\text{last term} - \text{first term}}{\text{common difference}} + 1
$$

Substituting the values:

$$
\text{Cardinality} = \frac{50 - 2}{2} + 1 = \frac{48}{2} + 1 = 24 + 1 = 25
$$

Thus, the cardinality of the set A is **25**.

---

### 4. **If A = {a, b, c}, find the power set of A.**

The **power set** of a set is the set of all subsets of the original set, including the empty set and the set itself.

For A = {a, b, c}, the power set P(A) is:

$$
P(A) = \{ \emptyset, \{a\}, \{b\}, \{c\}, \{a, b\}, \{a, c\}, \{b, c\}, \{a, b, c\} \}
$$

Thus, P(A) contains 8 subsets (2^3 = 8 because A has 3 elements).

---

### 5. **If A = {1, 2, 3} and B = {2, 3, 4}, prove that A ⊆ A ∪ B and A ∩ B ⊆ A.**

#### Prove that A ⊆ A ∪ B:

The **union** of A and B (A ∪ B) includes all elements of both sets A and B. Therefore, every element of A will also be in A ∪ B. Hence, A is a **subset** of A ∪ B.

$$
A = \{1, 2, 3\}, A \cup B = \{1, 2, 3, 4\}
$$

Clearly, A ⊆ A ∪ B, because all elements of A are present in A ∪ B.

#### Prove that A ∩ B ⊆ A:

The **intersection** of A and B (A ∩ B) includes only the elements that are common to both A and B. Therefore, every element of A ∩ B must also be an element of A. Hence, A ∩ B is a **subset** of A.

$$
A = \{1, 2, 3\}, B = \{2, 3, 4\}, A \cap B = \{2, 3\}
$$

Clearly, A ∩ B = {2, 3} ⊆ A = {1, 2, 3}.

---

### 6. **Explain the difference between proper subset and subset with examples.**

* A **subset** is a set where every element of the subset is also an element of the original set. A set is a subset of another set, but it could be the same set as well.

  **Example**: If A = {1, 2}, then A ⊆ B = {1, 2, 3}. A is a subset of B because all elements of A are also in B.

* A **proper subset** is a set where every element of the proper subset is in the original set, but the original set has at least one element that is not in the proper subset. A proper subset is always smaller than the original set.

  **Example**: If A = {1, 2}, then A ⊂ B = {1, 2, 3}. A is a **proper subset** of B because it has fewer elements than B and all elements of A are in B.

---

These answers should help clarify key concepts and operations related to **Set Theory**. Let me know if you'd like further details on any topic!

---
Here are 50 practice questions based on the **Set Theory** concepts from your lecture, along with their answers:

---

### **Set Theory Questions and Answers**

#### 1. **Question**: Define a set and provide examples.

**Answer**:
A **set** is a well-defined collection of distinct objects. Sets are unordered and contain unique elements.
Examples:

* A = {1, 2, 3, 4} (Set of integers).
* B = {a, b, c} (Set of letters).

---

#### 2. **Question**: What is the cardinality of the set A = {5, 10, 15, 20}?

**Answer**:
The cardinality of set A is the number of distinct elements in it.
|A| = 4.

---

#### 3. **Question**: Perform the operation A ∪ B if A = {1, 2, 3} and B = {3, 4, 5}.

**Answer**:
A ∪ B = {1, 2, 3, 4, 5} (Union of A and B).

---

#### 4. **Question**: What is the complement of set A = {1, 2, 3} in the universal set U = {1, 2, 3, 4, 5}?

**Answer**:
Aᶜ = {4, 5} (Complement of A in U).

---

#### 5. **Question**: Given A = {2, 4, 6}, B = {1, 3, 5}, find A ∩ B.

**Answer**:
A ∩ B = Ø (Empty set, as there are no common elements).

---

#### 6. **Question**: What is the power set of A = {1, 2}?

**Answer**:
The power set of A, P(A) = { Ø, {1}, {2}, {1, 2} }.

---

#### 7. **Question**: If A = {a, b, c} and B = {a, b}, is A a subset of B?

**Answer**:
No, A is **not** a subset of B because A has an element (c) that B does not contain.

---

#### 8. **Question**: If A = {1, 2, 3}, B = {2, 3, 4}, and C = {3, 4, 5}, find (A ∩ B) ∪ C.

**Answer**:
A ∩ B = {2, 3}, so (A ∩ B) ∪ C = {2, 3} ∪ {3, 4, 5} = {2, 3, 4, 5}.

---

#### 9. **Question**: Show that A ∪ (A ∩ B) = A for any sets A and B.

**Answer**:
A ∪ (A ∩ B) = A because the intersection part (A ∩ B) is already included in A. Hence, adding it to A does not change the result.

---

#### 10. **Question**: If A = {1, 3, 5}, B = {2, 3, 6}, and C = {1, 2, 7}, find A ∪ B ∪ C.

**Answer**:
A ∪ B ∪ C = {1, 2, 3, 5, 6, 7}.

---

#### 11. **Question**: Define proper subset and provide an example.

**Answer**:
A **proper subset** of a set A is a set that contains some but not all elements of A.
Example: If A = {1, 2, 3}, then {1, 2} is a proper subset of A.

---

#### 12. **Question**: What is the symmetric difference of A = {1, 2, 3} and B = {3, 4, 5}?

**Answer**:
A ∆ B = {1, 2, 4, 5} (Elements in A or B, but not in both).

---

#### 13. **Question**: Find the cardinality of A = {x ∈ Z : -3 ≤ x ≤ 3}.

**Answer**:
A = {-3, -2, -1, 0, 1, 2, 3}, so |A| = 7.

---

#### 14. **Question**: If U = {1, 2, 3, 4, 5, 6}, and A = {2, 4}, B = {4, 6}, find A ∩ B.

**Answer**:
A ∩ B = {4} (Intersection of A and B).

---

#### 15. **Question**: What is the difference between a subset and a proper subset?

**Answer**:

* **Subset**: Set A is a subset of B if all elements of A are in B (A ⊆ B).
* **Proper Subset**: Set A is a proper subset of B if A contains some but not all elements of B (A ⊂ B).

---

#### 16. **Question**: If A = {1, 2}, B = {2, 3}, and C = {1, 3}, find (A ∪ B) ∩ C.

**Answer**:
A ∪ B = {1, 2, 3}, so (A ∪ B) ∩ C = {1, 3}.

---

#### 17. **Question**: What is the power set of B = {1, 2, 3}?

**Answer**:
P(B) = { Ø, {1}, {2}, {3}, {1, 2}, {1, 3}, {2, 3}, {1, 2, 3} }.

---

#### 18. **Question**: Find A - B if A = {1, 2, 3, 4, 5} and B = {2, 4}.

**Answer**:
A - B = {1, 3, 5} (Elements in A but not in B).

---

#### 19. **Question**: Prove that A ∩ (A ∪ B) = A for any sets A and B.

**Answer**:
A ∩ (A ∪ B) = A because the intersection of A with the union of A and B will only include elements that are in A (as every element of A is in A ∪ B).

---

#### 20. **Question**: If A = {1, 2, 3, 4} and B = {3, 4, 5, 6}, what is the result of A ∩ (B - A)?

**Answer**:
B - A = {5, 6}, so A ∩ (B - A) = Ø (Empty set, as there are no common elements).


#### 21. **Question**: Define a universal set and provide an example.

**Answer**:
The **universal set** is the set that contains all the elements relevant to a particular discussion or problem.
Example: If we are discussing natural numbers, U = {1, 2, 3, 4, 5, ...} is the universal set for natural numbers.

---

#### 22. **Question**: Find the difference between sets A = {2, 4, 6} and B = {1, 2, 3}.

**Answer**:
A - B = {4, 6} (Elements in A but not in B).

---

#### 23. **Question**: Find the symmetric difference between A = {1, 3, 5} and B = {3, 5, 7}.

**Answer**:
A ∆ B = {1, 7} (Elements in A or B but not in both).

---

#### 24. **Question**: Show that the intersection of a set with the universal set is the set itself.

**Answer**:
A ∩ U = A for any set A. The intersection of A with the universal set U will always return A, as all elements of A are contained in U.

---

#### 25. **Question**: If A = {a, b, c}, B = {c, d, e}, and C = {a, b, e}, find (A ∪ B) ∩ C.

**Answer**:
A ∪ B = {a, b, c, d, e}, so (A ∪ B) ∩ C = {a, b, e}.

---

#### 26. **Question**: Prove that the power set of a set A with n elements has 2^n elements.

**Answer**:
If A has n elements, its power set P(A) contains all subsets of A. The number of subsets of a set with n elements is 2^n. This includes the empty set and the set itself.

---

#### 27. **Question**: Find the union of the following sets: A = {1, 2, 3}, B = {2, 3, 4}, and C = {3, 4, 5}.

**Answer**:
A ∪ B ∪ C = {1, 2, 3, 4, 5}.

---

#### 28. **Question**: If A = {1, 2}, B = {2, 3}, and C = {1, 3}, find (A ∩ B) ∪ (A ∩ C).

**Answer**:
A ∩ B = {2}, A ∩ C = {1}, so (A ∩ B) ∪ (A ∩ C) = {1, 2}.

---

#### 29. **Question**: What is the intersection of the set of even numbers and the set of odd numbers?

**Answer**:
The intersection of the set of even numbers and the set of odd numbers is the **empty set** (Ø), as there are no numbers that are both even and odd.

---

#### 30. **Question**: Find the set A - (A ∩ B) where A = {1, 2, 3, 4} and B = {3, 4, 5, 6}.

**Answer**:
A - (A ∩ B) = A - {3, 4} = {1, 2}.

---

#### 31. **Question**: What is the power set of A = {1}?

**Answer**:
P(A) = { Ø, {1} } (The power set of a set with one element has two subsets: the empty set and the set itself).

---

#### 32. **Question**: Prove that A ∩ (A - B) = Ø for any sets A and B.

**Answer**:
A ∩ (A - B) = Ø because the set (A - B) contains elements in A that are not in B, so there are no elements common to both A and (A - B).

---

#### 33. **Question**: If A = {1, 2, 3, 4}, find the number of subsets of A.

**Answer**:
The number of subsets of a set with n elements is 2^n.
For A with 4 elements, the number of subsets is 2^4 = 16.

---

#### 34. **Question**: Find the intersection of A = {1, 2, 3, 4} and B = {3, 4, 5, 6}.

**Answer**:
A ∩ B = {3, 4}.

---

#### 35. **Question**: What is the result of the operation A ∪ (A - B) for A = {1, 2, 3} and B = {2, 3, 4}?

**Answer**:
A - B = {1}, so A ∪ (A - B) = {1, 2, 3}.

---

#### 36. **Question**: Prove that the union of a set with the empty set is the set itself.

**Answer**:
A ∪ Ø = A for any set A. The union of A with the empty set will always return A, as the empty set contributes no elements.

---

#### 37. **Question**: Find the symmetric difference between A = {1, 2, 3} and B = {3, 4, 5}.

**Answer**:
A ∆ B = {1, 2, 4, 5}.

---

#### 38. **Question**: If A = {x | x is an integer and 1 ≤ x ≤ 5}, find the complement of A in the universal set U = {1, 2, 3, 4, 5, 6, 7}.

**Answer**:
A = {1, 2, 3, 4, 5}, so Aᶜ = {6, 7}.

---

#### 39. **Question**: Find the union of the following sets: A = {1, 2, 3}, B = {2, 4}, and C = {1, 3, 5}.

**Answer**:
A ∪ B ∪ C = {1, 2, 3, 4, 5}.

---

#### 40. **Question**: If A = {2, 4, 6}, B = {1, 2, 3}, and C = {4, 5, 6}, find (A ∩ C) ∪ (B - A).

**Answer**:
A ∩ C = {4, 6}, B - A = {1, 3}, so (A ∩ C) ∪ (B - A) = {1, 3, 4, 6}.

---

#### 41. **Question**: What is the symmetric difference of A = {1, 2} and B = {2, 3}?

**Answer**:
A ∆ B = {1, 3}.

---

#### 42. **Question**: If A = {a, b, c}, B = {c, d, e}, and C = {a, b}, find (A - B) ∩ (C ∪ B).

**Answer**:
A - B = {a, b}, C ∪ B = {a, b, c, d, e}, so (A - B) ∩ (C ∪ B) = {a, b}.

---

#### 43. **Question**: Find the complement of A = {1, 3, 5} in the universal set U = {1, 2, 3, 4, 5, 6}.

**Answer**:
Aᶜ = {2, 4, 6}.

---

#### 44. **Question**: What is the power set of B = {x, y, z}?

**Answer**:
P(B) = { Ø, {x}, {y}, {z}, {x, y}, {x, z}, {y, z}, {x, y, z} }.

---

#### 45. **Question**: What is the result of A ∩ (B ∪ C) for A = {1, 2}, B = {2, 3}, and C = {3, 4}?

**Answer**:
B ∪ C = {2, 3, 4}, so A ∩ (B ∪ C) = {2}.

---

#### 46. **Question**: Find the union of the following sets: A = {3, 6, 9}, B = {6, 12}, and C = {3, 9, 15}.

**Answer**:
A ∪ B ∪ C = {3, 6, 9, 12, 15}.

---

#### 47. **Question**: If A = {2, 4, 6}, B = {1, 2, 3}, and C = {4, 5, 6}, find A ∩ (B ∪ C).

**Answer**:
B ∪ C = {1, 2, 3, 4, 5, 6}, so A ∩ (B ∪ C) = {2, 4, 6}.

---

#### 48. **Question**: Find the cardinality of the set A = {2, 4, 6, 8, 10}.

**Answer**:
|A| = 5 (There are 5 elements in the set A).

---

#### 49. **Question**: What is the result of A ∪ (B - C) where A = {1, 2, 3}, B = {2, 3, 4}, and C = {1, 4}?

**Answer**:
B - C = {2, 3}, so A ∪ (B - C) = {1, 2, 3, 4}.

---

#### 50. **Question**: Prove that A ∩ (A ∆ B) = A - B for any sets A and B.

**Answer**:
A ∩ (A ∆ B) = (A ∩ (A - B)) = A - B. This is because the symmetric difference A ∆ B contains elements that are in A or B but not in both, so the intersection with A gives elements only in A but not in B.

---

