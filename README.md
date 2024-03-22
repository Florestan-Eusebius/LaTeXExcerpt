# LaTeXExcerpt

A LaTeXit-like tool for systems other than MacOS.

## Usage

- Copy the file `clip.ipynb` or just copy the code to your own python file or jupyter notebook. 
- Create a `maintext.txt` file in which you write your main text in the `.tex` file. Note that to type an equation in display style without numbering it, use `equation*` environment instead of `equation`. If you always use this tool to generate equations in display style, you can modify the code in a self-evident way. 
- Run the python script and `example_cropped.pdf` is what you need.

## Package dependence

The `pdfCropMargins` package is needed. You can install it via 

```shell
pip install pdfCropMargins
```

## Modifying the code

You can easily see how to modify the code to use more LaTeX packages or define new commands.

## Required features

- Automatically name the input and output file in a reasonable way.
- A clearer interface to change the margin size. (You can change it now if the code is apparent to you.)