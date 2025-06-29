# project2pdf

A command-line tool to convert your project files into a single PDF document. It supports various file types including:

- Python files (.py)
- Jupyter notebooks (.ipynb)
- Markdown files (.md)
- Various code files (.js, .ts, .java, .cpp, .c, .go, .rs, .rb, .php, .cs, .scala, .kt, .swift, .r, .sql, .sh)
- Existing PDF files

## Installation

You can install project2pdf using pip:

```bash
pip install project2pdf
```

## Usage

After installation, you can use the `project2pdf` command from anywhere in your terminal:

```bash
# Convert files in current directory
project2pdf

# Specify a different directory
project2pdf -d /path/to/your/project

# Specify output file name
project2pdf -o output.pdf

# Get help
project2pdf --help
```

## Features

- Converts various file types to PDF with syntax highlighting
- Maintains original formatting and structure
- Supports recursive directory scanning
- Merges multiple PDFs into a single document
- Preserves code syntax highlighting
- Handles Jupyter notebooks with output cells
- Supports markdown rendering

## Requirements

- Python 3.7 or higher
- Required dependencies will be automatically installed

## License

This project is licensed under the MIT License - see the LICENSE file for details.

## Contributing

Contributions are welcome! Please feel free to submit a Pull Request.
