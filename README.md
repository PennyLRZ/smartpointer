# Smart pointer in C++  
## Description 
This project implements a template class for smart pointers that is of important use for the purpose of garbage collection in many large-scale projects based on C++ such as class *sp* for android and class *auto_ptr* in C++ STL . A smartpointer distinguishes from raw pointers in two ways: 1) it releases memory automatically to prevent memory leak 2) it release memory only when it's safe to do so.

## Design
In this project, we make use of 1) Constructive functions 2) Virtual functions 3) Reference counting


