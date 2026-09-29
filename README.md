# OOP with C++ — Unit 4: Files and Streams

## Student Information

* **Student Name:** Dhyeya Chothe
* **PRN:** 125UAD1261
* **Class/Division:** S.Y. B.Tech Artificial Intelligence and Data Science
* **Course Name:** Object-Oriented Programming with C++
* **Course Code:** ADPC303
* **Semester:** III
* **Unit:** Unit 4 — Files and Streams
* **Language:** C++17 or later

---

## About This Repository

This repository contains practical C++ programs based on **Unit 4: Files and Streams**.

The programs demonstrate file handling concepts such as creating, reading, writing, appending, searching, updating, binary file operations, file pointers, error handling, and file-based applications.

The practical programs are organized from basic file operations to mini-projects.

---

## Learning Objectives

After completing these programs, the student will be able to:

* Create, open and close files.
* Read and write data using C++ file streams.
* Append data to existing files.
* Use `ifstream`, `ofstream`, and `fstream`.
* Process files line by line and word by word.
* Search and process text stored in files.
* Store and retrieve structured records.
* Use `seekg()`, `seekp()`, `tellg()` and `tellp()`.
* Work with binary files using `read()` and `write()`.
* Handle file errors using stream-state functions.
* Develop basic file-based applications.

---

## Programs / Experiments

| No. | Program                              | Main Concept                               |
| --- | ------------------------------------ | ------------------------------------------ |
| 01  | Write Text to a File                 | `ofstream`, `open()`, `close()`            |
| 02  | Read a File Line by Line             | `ifstream`, `getline()`                    |
| 03  | Append Data to a File                | `ios::app`                                 |
| 04  | Copy One Text File into Another      | File Reading and Writing                   |
| 05  | Count Lines, Words and Characters    | File Processing                            |
| 06  | Search for a Word in a File          | Text Search                                |
| 07  | Store Student Records in a Text File | Structured Text Records                    |
| 08  | Read and Search Student Records      | File Parsing                               |
| 09  | Update a Student Record              | Temporary File                             |
| 10  | File Pointer Navigation              | `seekg()`, `seekp()`, `tellg()`, `tellp()` |
| 11  | Binary File Writing and Reading      | `write()`, `read()`                        |
| 12  | Random Access in a Binary File       | Record Navigation                          |
| 13  | File Error Handling                  | `good()`, `eof()`, `fail()`, `bad()`       |
| 14  | File Statistics Mini-Project         | Text Analysis                              |
| 15  | Student Record Manager               | File-Based CRUD                            |
| 16  | Library Record Mini-Project          | OOP + File Storage                         |

The experiment list and concepts follow the uploaded Unit 4 code book.

---

## Repository Structure

```text
OOP_with_CPP_Unit_4/
│
├── README.md
│
├── Program_01_Write_Text/
│   └── program01.cpp
│
├── Program_02_Read_File/
│   └── program02.cpp
│
├── Program_03_Append_File/
│   └── program03.cpp
│
├── Program_04_Copy_File/
│   └── program04.cpp
│
├── Program_05_File_Statistics/
│   └── program05.cpp
│
├── Program_06_Search_Word/
│   └── program06.cpp
│
├── Program_07_Student_Records/
│   └── program07.cpp
│
├── Program_08_Search_Student/
│   └── program08.cpp
│
├── Program_09_Update_Record/
│   └── program09.cpp
│
├── Program_10_File_Pointers/
│   └── program10.cpp
│
├── Program_11_Binary_File/
│   └── program11.cpp
│
├── Program_12_Random_Access/
│   └── program12.cpp
│
├── Program_13_Error_Handling/
│   └── program13.cpp
│
├── Program_14_File_Statistics_Project/
│   └── program14.cpp
│
├── Program_15_Student_Record_Manager/
│   └── program15.cpp
│
└── Program_16_Library_Record/
    └── program16.cpp
```

---

## File Stream Classes

| Class      | Header      | Purpose                              |
| ---------- | ----------- | ------------------------------------ |
| `ifstream` | `<fstream>` | Read from a file                     |
| `ofstream` | `<fstream>` | Write to a file                      |
| `fstream`  | `<fstream>` | Read and write using the same stream |

---

## Common File Modes

| Mode          | Purpose                   |
| ------------- | ------------------------- |
| `ios::in`     | Open file for reading     |
| `ios::out`    | Open file for writing     |
| `ios::app`    | Add data at the end       |
| `ios::ate`    | Initially move to the end |
| `ios::trunc`  | Discard existing content  |
| `ios::binary` | Open in binary mode       |

---

## Important Functions

### File Operations

```cpp
ofstream
ifstream
fstream
open()
close()
getline()
```

### File Pointer Operations

```cpp
tellg()
tellp()
seekg()
seekp()
```

### Binary File Operations

```cpp
read()
write()
```

### Error Handling

```cpp
good()
eof()
fail()
bad()
```

---

## Compilation

### Windows — MinGW

```bash
g++ -std=c++17 program01.cpp -o program01.exe
program01.exe
```

### Linux / macOS

```bash
g++ -std=c++17 program01.cpp -o program01
./program01
```

The code book specifies C++17 or later and provides these compilation approaches.

---

## Key Concepts Covered

### 1. Text File Handling

Programs demonstrate:

* Creating files
* Writing data
* Reading data
* Appending data
* Copying files
* Searching text

### 2. Student Records

Student records are stored using a delimiter-based format:

```text
rollNumber|name|marks
```

Example:

```text
101|Amit Patil|85.5
```

### 3. File Pointers

The repository demonstrates:

```cpp
tellg()
tellp()
seekg()
seekp()
```

These functions are used to find and change positions in files.

### 4. Binary Files

Binary file programs demonstrate:

```cpp
write()
read()
```

using fixed-size records.

### 5. File-Based Applications

The final programs demonstrate:

* Student Record Manager
* Library Record System
* Add records
* Display records
* Search records
* Update records

The Student Record Manager includes add, display, search and update operations.

---

## Expected Learning Outcome

By completing this repository, the student gains practical understanding of **C++ file handling and streams** and can develop basic applications that store and retrieve data using files.

---

## Tools Used

* C++
* C++17
* VS Code
* MinGW / G++
* Git
* GitHub

---

## Author

**Dhyeya Chothe**

S.Y. B.Tech
Artificial Intelligence and Data Science

---

## Acknowledgement

This repository is prepared as part of the practical study of **Object-Oriented Programming with C++ — Unit 4: Files and Streams**.
