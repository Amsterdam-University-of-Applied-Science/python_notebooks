# JupyterLite Python Fundamentals Tutorial

A browser-based Jupyter environment showcasing Python fundamentals (strings, lists, tuples), built with JupyterLite for Amsterdam University of Applied Sciences.

## 🚀 Live Demo

This JupyterLite application runs entirely in your browser - no server required!

- **File Browser Interface**: Clean, focused interface showing available notebooks
- **Python Kernel**: Full Python environment with numpy, pandas, and matplotlib
- **Interactive Learning**: Hands-on examples for Python fundamentals (strings, lists, tuples)

## 📚 Tutorial Content

This collection contains three Python fundamentals notebooks, part of the Python module from the minor **"Big Data and Computer Aided (Financial) Analysis"**:

### py1_strings.ipynb
Essential Python string operations:
- **Text Transformation**: `capitalize()`, `casefold()`, `center()`, `upper()`, `lower()`
- **Content Analysis**: `count()`, `find()`, `index()`, `endswith()`
- **Type Checking**: `isalnum()`, `isalpha()`, `isascii()`, `isdecimal()`, `isdigit()`, `islower()`, `isidentifier()`
- **Formatting**: `format()`, `encode()`

### py1_lists.ipynb
Python list methods and operations:
- List creation, manipulation, and iteration
- Common list methods and their applications
- Practical examples for data handling

### py1_tuples.ipynb
Python tuple fundamentals:
- Tuple creation and properties
- Tuple methods and use cases  
- When to use tuples vs lists

## 🎯 Educational Goals

This project serves as an educational resource for the minor **"Big Data and Computer Aided (Financial) Analysis"**:

- **Python Fundamentals**: Core data types (strings, lists, tuples) and their methods
- **Interactive Computing**: Jupyter notebook usage patterns for data analysis
- **Web-based Development**: Browser-native Python execution
- **Data Science Preparation**: Foundation skills for big data and financial analysis
- **Minor Prerequisites**: Essential Python knowledge for advanced data analysis topics

## 🏗️ Built With

- **JupyterLite**: Browser-based Jupyter environment
- **Pyodide**: Python in WebAssembly for browser execution
- **Python Packages**: numpy, pandas, matplotlib
- **Educational Focus**: Streamlined interface for learning

## 📖 Usage

1. **Access the Interface**: Open the deployed site in any modern browser
2. **Browse Files**: Use the file browser to navigate available notebooks
3. **Run Notebooks**: Click on notebooks to open them in the Python environment
4. **Learn Interactively**: Execute code cells to see string methods in action

## 🔧 Development

This repository contains the built static site. Source files and build configuration are maintained separately for development.

### Local Development

```bash
# Serve the built site locally
python -m http.server 8000 -d _output
# or
npx serve _output
```

## 🎓 For Educators

This JupyterLite deployment provides:

- **No Installation Required**: Students can access immediately via browser
- **Consistent Environment**: Same Python environment for all students
- **Focused Interface**: Minimal distractions, education-focused UI
- **Self-contained**: All dependencies bundled, works offline

## 📄 License

This educational project is open source and available for educational use.

## 🏫 Amsterdam University of Applied Sciences

Created for computer science education at Amsterdam University of Applied Sciences (HvA).
