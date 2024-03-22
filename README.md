# LaTeXExcerpt

A LaTeXit-like tool for systems other than MacOS.

## Usage

- Copy the file `clip.ipynb` or just copy the codes to your own python file or jupyter notebook. 
- Create a `maintext.txt` file in which you write your main text in the `.tex` file. Note that to type an equation in display style without numbering it, use `equation*` environment instead of `equation`. If you always use this tool to generate equations in display style, you can modify the codes in a self-evident way. 
- Run the python script. You may need to install some packages. See the next section.

## Package dependence

The `pdfCropMargins` package is needed. You can install it via 

```bash
pip install pdfCropMargins
```

## Modifying the codes 

You can easily see how to modify the codes to use more LaTeX packages or define new commands.