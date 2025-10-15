# Repository Summary

## Overview

This repository is a comprehensive **C/C++ Technical Interview Preparation Guide** (面向C/C++技术方向的基础知识总结). It serves as a knowledge base for C/C++ developers preparing for technical interviews, covering fundamental concepts, algorithms, data structures, system design, and practical interview questions.

**Repository Name:** RENYU-ZHANG/interview  
**Primary Language:** C++  
**License:** CC BY-NC-SA 4.0 (Attribution-NonCommercial-ShareAlike)  
**Target Audience:** C/C++ developers, job seekers, students, and beginners

## Key Features

### 📚 Documentation Formats
- **GitHub Repository**: Direct browsing on GitHub
- **Docsify Documentation**: Interactive web documentation at [interview.huihut.com](https://interview.huihut.com)
- **PDF Support**: Can be saved as PDF for offline reading
- **Bilingual Support**: Chinese (primary) and English versions available

## Main Content Areas

### 1. **C/C++ Language Fundamentals** (➕ C/C++)
Comprehensive coverage of C++ language features including:
- Keywords and operators (`const`, `static`, `inline`, `volatile`, `extern "C"`)
- Pointers, references, and memory management
- Object-oriented programming (OOP): encapsulation, inheritance, polymorphism
- Virtual functions, virtual tables, and virtual inheritance
- Templates and generic programming
- Smart pointers (`shared_ptr`, `unique_ptr`, `weak_ptr`)
- Type casting operators
- RTTI (Run-Time Type Information)

### 2. **STL (Standard Template Library)** (📦)
- Container classes (vector, list, map, set, etc.)
- Iterators and algorithms
- Function objects and lambdas
- STL implementation details

### 3. **Data Structures** (〽️)
Practical implementations in C++ including:
- **Linear Structures**:
  - Sequential Lists (`SqList.cpp`)
  - Linked Lists (`LinkList.cpp`, `LinkList_with_head.cpp`)
  - Stacks (`SqStack.cpp`)
- **Tree Structures**:
  - Binary Trees (`BinaryTree.cpp`)
  - Red-Black Trees (`RedBlackTree.cpp`)
- **Hash Tables** (`HashTable.cpp`)

### 4. **Algorithms** (⚡️)
Multiple sorting and searching algorithm implementations:
- **Sorting Algorithms**:
  - Bubble Sort, Selection Sort, Insertion Sort
  - Quick Sort, Merge Sort, Heap Sort
  - Shell Sort, Bucket Sort, Radix Sort, Count Sort
- **Searching Algorithms**:
  - Sequential Search, Binary Search
  - BST Search, Fibonacci Search, Insertion Search

### 5. **Design Patterns** (📏)
Classic design pattern implementations with examples:
- Singleton Pattern
- Abstract Factory Pattern
- Adapter Pattern
- Bridge Pattern
- Observer Pattern
- Design principles (SOLID, etc.)

### 6. **Problem Solving** (❓)
Classic algorithm problems with solutions:
- Chessboard Coverage Problem
- Knapsack Problem
- Neumann Neighbor Problem (with recursive and formula solutions)
- Round Robin Problem
- Tubing Problem

### 7. **Operating Systems** (💻)
- Process and thread management
- Memory management
- File systems
- Deadlock handling
- Linux/Unix system programming

### 8. **Computer Networks** (☁️)
- Network protocols (TCP/IP, UDP, HTTP, FTP, DNS)
- OSI and TCP/IP models
- Socket programming
- Network security basics

### 9. **Network Programming** (🌩)
- Socket programming in C/C++
- TCP three-way handshake and four-way termination
- Client-server communication
- I/O multiplexing

### 10. **Database Systems** (💾)
- Relational database concepts
- SQL operations
- Indexing strategies
- Transactions and ACID properties
- Concurrency control
- Database normalization (1NF, 2NF, 3NF, BCNF)

### 11. **Linking, Loading, and Libraries** (⚙️)
- Memory layout (stack, heap, segments)
- Compilation and linking process
- Static and dynamic libraries
- Shared libraries (.so on Linux, .dll on Windows)
- Symbol resolution and relocation

## Repository Structure

```
interview/
├── README.md                   # Main documentation (Chinese)
├── README_en.md               # English version
├── SUMMARY.md                 # This summary document
├── Algorithm/                 # Sorting and searching algorithms
│   ├── BubbleSort.h
│   ├── QuickSort.h
│   ├── MergeSort.h
│   └── ...
├── DataStructure/            # Data structure implementations
│   ├── BinaryTree.cpp
│   ├── LinkList.cpp
│   ├── HashTable.cpp
│   └── ...
├── DesignPattern/            # Design pattern examples
│   ├── SingletonPattern/
│   ├── AbstractFactoryPattern/
│   ├── ObserverPattern/
│   └── ...
├── Problems/                 # Classic algorithm problems
│   ├── KnapsackProblem/
│   ├── ChessboardCoverageProblem/
│   └── ...
├── STL/                      # STL documentation
│   ├── README.md
│   └── STL.md
├── docs/                     # Docsify documentation files
└── images/                   # Diagrams and illustrations
```

## Target Users and Use Cases

### 1. **Job Seekers**
- Preparing for technical interviews at tech companies
- Reviewing fundamental CS concepts
- Practicing coding problems
- Understanding system design principles

### 2. **Students**
- Learning C/C++ programming
- Understanding data structures and algorithms
- Studying operating systems and networks
- Academic reference material

### 3. **Beginners**
- Starting their journey in C/C++ development
- Building strong foundations
- Learning best practices
- Understanding core CS concepts

### 4. **Experienced Developers**
- Refreshing knowledge before interviews
- Quick reference for specific topics
- Teaching and mentoring others
- Contributing to the community

## How to Use This Repository

### 1. **Browse on GitHub**
- Navigate through directories to find specific topics
- Read markdown files for theoretical knowledge
- Review C++ source code for implementation details
- Use TOC navigation extensions for better experience

### 2. **Interactive Documentation**
- Visit [interview.huihut.com](https://interview.huihut.com) for Docsify version
- Use sidebar navigation for easy topic access
- Search functionality for quick lookups
- Mobile-friendly interface

### 3. **Offline Reading**
- Save as PDF from the Docsify site (Chrome: Print > Save as PDF)
- Clone repository for local access:
  ```bash
  git clone https://github.com/RENYU-ZHANG/interview.git
  ```

### 4. **Code Practice**
- Compile and run algorithm implementations
- Modify code to understand behavior
- Use as templates for interview practice
- Experiment with design patterns

## Additional Resources

### 📚 Recommended Books
- **Language**: C++ Primer, Effective C++, More Effective C++, STL Source Code Analysis
- **Algorithms**: Cracking the Coding Interview (剑指Offer), Programming Pearls
- **Systems**: Computer Systems: A Programmer's Perspective, Windows Core Programming
- **Networks**: Unix Network Programming, TCP/IP Illustrated

### 💯 Practice Websites
- [LeetCode](https://leetcode.com/) / [LeetCode-CN](https://leetcode-cn.com/)
- [LintCode](https://www.lintcode.com/)
- [牛客网 (NowCoder)](https://www.nowcoder.com/)

### 📝 Interview Experience
The repository includes links to:
- Real interview questions from major tech companies
- Interview experiences and tips
- Campus recruitment information
- Technical direction guidance

## Career Development Paths

The repository covers various C/C++ career directions:
- **Backend/Server Development**: Distributed systems, high-performance servers
- **Desktop Client Development**: Windows/Linux applications
- **Game Development**: Game engines, graphics programming
- **Embedded Systems**: IoT, firmware development
- **Computer Vision/ML**: Image processing, AI applications
- **Network Security**: Reverse engineering, security tools
- **Audio/Video**: Codec development, streaming media
- **Test Development**: Automation, performance testing

## Contributing

This repository welcomes contributions:
- Report errors or improvements via GitHub Issues
- Submit pull requests for corrections or enhancements
- Share interview experiences
- Suggest new topics or resources

**Discussion**: Use [Issue #12](https://github.com/huihut/interview/issues/12) for general discussions

## License

**CC BY-NC-SA 4.0** (Attribution-NonCommercial-ShareAlike)
- ✅ Share and adapt the content
- ✅ Provide attribution
- ⚠️ Non-commercial use only
- ⚠️ Share under same license

## Statistics and Impact

This repository serves as a comprehensive reference for:
- C/C++ interview preparation
- Computer science fundamentals
- Practical coding skills
- System design knowledge

It consolidates knowledge from multiple authoritative sources including textbooks, technical blogs, and real interview experiences, making it an invaluable resource for the C/C++ developer community.

---

**Note**: Content is primarily in Chinese with some English translations available. The repository is actively maintained and contributions from the community are encouraged.

**Original Repository**: Based on [huihut/interview](https://github.com/huihut/interview)

Last Updated: 2025
