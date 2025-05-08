# Cursor-JupyterNotebook

This project provides a solution for working with Jupyter Notebooks (.ipynb files) in Cursor IDE, which currently doesn't have native support for .ipynb files.

## Quick Start

1. Clone this repository:
```bash
git clone https://github.com/Jieyuuuuu/Cursor-JupyterNotebook.git
```

2. Install requirements:
```bash
pip install -r requirements.txt
```

3. In Cursor's chat, tell it to read the rules and template:
```
Please read cursor_rules.txt and template.py first
```

## Project Structure

- `template.py`: A Python template that can generate .ipynb files
- `cursor_rules.txt`: Rules and prompts for Cursor to handle .ipynb related requests

## How It Works

1. When you need to create or edit a .ipynb file in Cursor:
   - The system will use the template.py to generate the .ipynb file
   - Any modifications will be made to the Python file first
   - The Python file will then be executed to generate the updated .ipynb file

## Usage

1. After setting up, you can directly tell Cursor what kind of notebook you want to create or edit
2. Use template.py as a base for creating new notebooks
3. Follow the instructions in cursor_rules.txt when working with .ipynb files

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
