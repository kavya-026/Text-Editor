📝 Console Text Editor in C
    A console-based text editor developed in **C**, demonstrating practical implementation of doubly linked lists, dynamic memory allocation, stacks, file handling, string manipulation.

🚀 Features
📄 File Operations

   Open existing files
   Save files
   Close files
   Track file modification status

✍️ Text Editing

    Insert text
    Delete characters
    Delete current line
    Cursor-based text editing

🔎 Search & Replace

    Search for text
    Display matching line and column
    Replace text occurrences

📋 Clipboard

    Copy text
    Cut text
    Paste text

↩️ Undo / Redo

    Multi-level undo
    Multi-level redo
    Operation history using dynamic stacks
    
🖥️ Cursor Navigation

   Move Up / Down
   Move Left / Right
   Jump to start/end of line
   Jump to start/end of file
   Track cursor line and column

🧠 Data Structures

Data Structure Purpose

   Doubly Linked List -> Stores text line by line 
   Dynamic Array Stack -> Manages undo/redo history 
   Dynamic Memory -> Manages text, clipboard and actions 
   
📁 Project Structure

TextEditor/
│
├── text_editor.c
├── text_editor.h
│
├── text_ops.c
├── text_ops.h
│
├── curser_navigations.c
├── curser_navigations.h
│
├── file_ops.c
├── file_ops.h
│
├── display_search.c
├── display_search.h
│
├── redo_undo.c
├── redo_undo.h
│
├── Makefile
└── README.md


📚 Concepts Demonstrated

    C Programming
    Pointers
    Structures
    Dynamic Memory Allocation
    Doubly Linked Lists
    Stack Implementation
    Dynamic Arrays
    File Handling
    String Manipulation
    Modular Programming
    Undo/Redo Algorithms
    Command-Line Interface

💡 Future Improvements

    Syntax highlighting
    Case-insensitive search
    Advanced text selection
    Improved command parsing
    Extended undo/redo support
    Line merging and splitting

👩‍💻 Author

Kavyashree

Bachelor of Engineering (Electronics & Communication)

Interested in: - Embedded Systems - Embedded C - STM32 - ESP32 - VLSI - Firmware Development

⭐ If you found this project useful
Please consider giving the repository a ⭐ on GitHub!
