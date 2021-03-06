# tikzmagic

A Jupyter extension for compiling and displaying images described by the [TikZ](http://www.texample.net/tikz/) language.

## Requirements

- IPython/Jupyter
- LaTeX (`xelatex`) 
	- package `standalone`
- ImageMagick

## Installation

```pip install git+git://github.com/robjstan/tikzmagic.git```

## Usage

In an iPython notebook cell: `import tikzmagic` or `%load_ext tikzmagic`.

## Optional arguments

- `-p` or `--latex_packages`
- `-x` or `--latex_preamble`
- `-l` or `--tikz_libraries`
- `-i` or `--input_file`
- `-s` or `--scale`, default=1 (corresponding to 300dpi)
- `-b` or `--border`, default=4

## Example

[Example iPython notebook](example.ipynb)
