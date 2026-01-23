# 12 - Data Structures Level 1 🏗️

**"Reinventing the wheel to learn how it rolls."**

This directory contains a custom **Generic Data Structures Library** built from scratch using C++ Templates. Instead of relying on the Standard Template Library (STL), I implemented these structures manually to master memory management, pointers, and algorithmic efficiency.

## 🚀 Key Implementations
I built a generic library (`clsDblLinkedList.h`, `clsStack.h`, `clsQueue.h`, etc.) supporting any data type:
- **Doubly Linked List:** Full implementation (Insert, Delete, Reverse, Find, GetItem).
- **Stack:** LIFO (Last-In, First-Out) structure derived from the Linked List.
- **Queue:** FIFO (First-In, First-Out) structure.
- **Dynamic Array:** A custom vector-like structure managing dynamic memory.

## 🧠 Advanced Concepts
- **C++ Templates (Generics):** Writing code that works for `int`, `string`, or custom Objects (`clsClient`) without code duplication.
- **Node Management:** Manual handling of `Next` and `Prev` pointers to maintain list integrity.
- **Memory Leaks:** Ensuring proper destructors to clean up nodes when structures are destroyed.

## 📂 Performance Analysis
- Compared the time complexity (Big O) of operations like **Insertion** and **Deletion** between Arrays (O(N)) and Linked Lists (O(1)).
- Implemented **Undo/Redo** functionality using Stacks as a practical application.

## 🛠️ Stack
- **Language:** C++ (Templates)
- **Focus:** Low-level Data Structure Implementation.

---
## 🎓 Verification
[📄 **View Certificate of Completion (PDF)**](../../Certificates/12-certificate-of-completion-for-12-data-structures-level1.pdf)