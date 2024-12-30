# Uncommon Assembly Code Errors
This repository demonstrates uncommon errors that can occur in x86 assembly code, specifically focusing on access violations and segmentation faults.  The code examples highlight scenarios where incorrect memory access leads to program crashes. Solutions are provided to illustrate how to mitigate these issues.

## Errors

* **Access Violation:** Attempting to read from or write to a memory location that the program doesn't have permission to access.
* **Segmentation Fault:**  Similar to an access violation, often caused by dereferencing a null pointer or accessing memory outside the allocated space.

## Solutions

The provided solution demonstrates how to properly validate memory addresses and ensure that memory operations are performed within safe boundaries.