# 🌳 Self-Balancing Tree Data Structures in C

A lab record repository containing programs and documentation on **Self-Balancing Tree Data Structures** implemented in **C**, submitted as part of the Data Structures Laboratory coursework.

---

## 📁 Repository Contents

| File | Description |
|------|-------------|
| `2303811710421107_Data_Structures_lab_record_2024_11_22.pdf` | Complete lab record submitted on 22 November 2024, covering self-balancing tree implementations and experiments |

---

## 🧠 Topics Covered

This lab record covers the following self-balancing tree data structures implemented in C:

### 🔁 AVL Tree (Adelson-Velsky and Landis Tree)
- Node insertion with balance factor tracking
- Left Rotation, Right Rotation, Left-Right Rotation, Right-Left Rotation
- Automatic rebalancing after insertion/deletion
- In-order, pre-order, and post-order traversals

### 🔴⚫ Red-Black Tree
- Properties: root is black, red nodes have black children, equal black-height paths
- Insertion with color flipping and rotations
- Deletion with double-black fixup
- Maintaining logarithmic height guarantee

### 🌲 B-Tree / B+ Tree *(if covered)*
- Multi-way balanced tree for disk-based storage
- Node splitting and merging
- Efficient range queries

---

## 🛠️ Technologies Used

| Category | Details |
|----------|---------|
| Language | C (C99/C11) |
| Compiler | GCC (GNU Compiler Collection) |
| Platform | Linux / Windows (MinGW) |
| IDE / Editor | VS Code / Turbo C / Code::Blocks |

---

## 🚀 How to Compile and Run

### Prerequisites
- GCC compiler installed (`gcc --version` to verify)

### Steps

```bash
# Clone the repository
git clone https://github.com/niran-123/self_balancing_tree_datastructure_C.git
cd self_balancing_tree_datastructure_C

# Compile a program (example: AVL Tree)
gcc avl_tree.c -o avl_tree

# Run the executable
./avl_tree
```

> **Note:** Refer to the lab record PDF for the complete source code of each program.

---

## 📊 Sample Operations

### AVL Tree Insert Example

```
Insert: 10, 20, 30, 40, 50, 25

After balancing:
        30
       /  \
     20    40
    /  \     \
  10   25    50

Height balanced ✅ | All balance factors ∈ {-1, 0, 1} ✅
```

---

## 📚 Key Concepts

| Concept | AVL Tree | Red-Black Tree |
|---------|----------|----------------|
| Height guarantee | ≤ 1.44 log₂(n) | ≤ 2 log₂(n+1) |
| Rotations on insert | Up to 2 | Up to 2 |
| Rotations on delete | O(log n) | At most 3 |
| Best use case | Frequent lookups | Frequent insertions/deletions |
| Balance criterion | Balance factor | Node color (Red/Black) |

---

## 🎓 Academic Information

| Field | Details |
|-------|---------|
| Student ID | 2303811710421107 |
| Subject | Data Structures Laboratory |
| Submission Date | 22 November 2024 |
| Department | Artificial Intelligence and Data Science |
| Institution | K. Ramakrishnan College of Technology |

---

## 📖 References

- *Introduction to Algorithms* – Cormen, Leiserson, Rivest, Stein (CLRS), 3rd Edition
- *Data Structures and Algorithm Analysis in C* – Mark Allen Weiss
- [GeeksforGeeks – AVL Tree](https://www.geeksforgeeks.org/avl-tree-set-1-insertion/)
- [GeeksforGeeks – Red-Black Tree](https://www.geeksforgeeks.org/red-black-tree-set-1-introduction-2/)

---

## 📝 License

This repository is for **academic and educational purposes only**.  
All programs are original implementations submitted as part of coursework.

---

> *"A well-balanced tree is the foundation of efficient computing."*
