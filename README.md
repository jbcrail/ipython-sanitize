ipython-sanitize
================

Easily display and/or verify items in Jupyter notebooks.

## Usage

To show all images in the given notebooks:

    ./ipython-sanitize images *.ipynb

To show all Python modules in the given notebooks:

    ./ipython-sanitize modules *.ipynb

To show all Python modules in the given notebooks (including the standard library):

    ./ipython-sanitize modules --stdlib *.ipynb

To show all URLs in the given notebooks:

    ./ipython-sanitize urls *.ipynb
