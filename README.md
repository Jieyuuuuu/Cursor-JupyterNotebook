# Cursor-JupyterNotebook

This project provides a solution for working with Jupyter Notebooks (.ipynb files) in Cursor IDE, which currently doesn't have native support for .ipynb files.

## Project Structure

- `template.py`: A Python template that can generate .ipynb files
- `cursor_rules.txt`: Rules and prompts for Cursor to handle .ipynb related requests

## How It Works

1. When you need to create or edit a .ipynb file in Cursor:
   - The system will use the template.py to generate the .ipynb file
   - Any modifications will be made to the Python file first
   - The Python file will then be executed to generate the updated .ipynb file

## Usage

1. Clone this repository
2. Follow the instructions in cursor_rules.txt when working with .ipynb files
3. Use template.py as a base for creating new notebooks

## Requirements

- Python 3.x
- nbformat
- jupyter

## Installation

```bash
pip install nbformat jupyter
```

## License

MIT License # Cursor-JupyterNotebook
