# Compiler-Phase-Visualizer

## Overview

This project implements a simplified C compiler with a modular architecture, separating the user interface (UI) from the core compiler logic. The tool is designed to provide a smooth, interactive experience, helping users visualize the transformation of their C code through various compiler phases:

- Lexical Analysis  
- Syntax Analysis  
- Semantic Analysis  
- Intermediate Code Generation

Each phase is implemented as an independent backend module, outputting structured and readable results to aid learning and debugging.

---

## Features

- **Modular Compiler Backend**  
  Implemented in JS, each compiler phase works independently, producing detailed outputs.

- **User-Friendly Interface**   
  - **Web UI:** Built with HTML, CSS, and JavaScript for flexible deployment and modern styling

- **File Upload & Execution**  
  Users can upload `.c` source files, run them through the entire compiler pipeline, and view detailed phase-wise output.

- **Seamless Integration**  
  The frontend interfaces communicate with the backend compiler.

---

## Technologies Used

- **Frontend:**  
  - HTML, CSS, JavaScript (Web-based UI)

- **Backend:**  
  - JavaScript
