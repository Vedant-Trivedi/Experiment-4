# Experiment-4

## LAB REPORT: STUDY OF PYTHON SETS

**Student Name:** Vedant Trivedi

**PRN:** 25070123121

**Experiment No:** 4


---

### 1. AIM:

To explore the properties and applications of **Sets** in Python, including their unordered nature, uniqueness of elements, mathematical operations (Union, Intersection, Difference), and the use of **Frozensets**.

---

### 2. THEORY:

A **Set** in Python is an unordered collection of items where every element is unique (no duplicates) and must be immutable. Key characteristics include:

* **Unordered & Unindexed:** Sets do not record element position; hence, they do not support indexing or slicing. Attempting to access `set[0]` results in a `TypeError`.
* **Uniqueness:** Sets automatically filter out duplicate values. In Python, `True` and `1` (as well as `False` and `0`) are treated as the same value within a set.
* **Mathematical Operations:** Python sets support standard mathematical set theory operations like Union (), Intersection (), Difference (), and Symmetric Difference ().
* **Frozenset:** An immutable version of a set. Once created, elements cannot be added or removed.

---

### 3. LOGIC:

The experiment is structured to demonstrate the practical utility of sets through several scenarios:

* **Data Cleaning:** Converting a list to a set to automatically remove duplicate registrations.
* **Membership Testing:** Using the `in` keyword to efficiently check for the presence of an element.
* **Relational Analysis:** Comparing groups (e.g., Sports Clubs or Student Subjects) using operators like `&` (Intersection) to find commonalities and `^` (Symmetric Difference) to find unique members.
* **Immutability:** Implementing a `frozenset` to ensure data integrity where modification is not permitted.

---

### 4. ALGORITHM (Set Operations & Problem Solving):

**Step 1:** Start.

**Step 2:** Define two sets, `A` and `B`, with overlapping integer values.

**Step 3:** Perform and display **Union** (all elements) and **Intersection** (common elements) using both methods (`.union()`) and operators (`|`, `&`).

**Step 4:** Calculate **Difference** () to find elements unique to the first set.

**Step 5:** Use **Symmetric Difference** to identify elements present in either set, but not both.

**Step 6:** Solve real-world problems (e.g., finding absent students by subtracting `PresentStudents` from `AllStudents`).

**Step 7:** End.

---

### 5. CONCLUSION:

In this experiment, I successfully analyzed the behavior of Python Sets. I observed that while sets lack the indexing capabilities of lists, they are far superior for tasks involving **uniqueness** and **membership testing**. The mathematical operators provide a concise and powerful way to handle complex data comparisons, such as finding common participants across multiple groups or identifying missing entries. Finally, the distinction between `set` and `frozenset` highlighted the importance of mutability control in programming.

================================================================================
