# UIC Research Thesis Template

Un-official Version of BNU-HKBU United International College Postgraduate(Research) Thesis Template: 


## LaTeX Template

Author: [@Terence Liu](https://blog.cklau.cc/about/)

A LaTeX template based on the Thesis Regulation provided by the BNU-HKBU UIC Graduate School.

### Files structure

1. [DIR] `fig`: a place for all asset materials like figures, codes, PDFs, etc. Files are not limited to stored there, just a pre-created folder to help you keep everything nice and clean.

2. [DIR] `main`: The folder includes `declaration.tex`, `abstract.tex`, `acknowledgements.tex`, `symbols.tex`, and the body part of the thesis.

3. [DIR] `material`: The only file in this folder is `titleMemo.tex`, you may need to submit the title to the Graduate School before you start your thesis writing. By compiling this `tex` file, it can provide you a beatiful letter that you can directly send it to the GS.

4. [DIR] `others`: This folder includes `bibliography.bib`, `cv.tex`, `pub.tex`

5. [FILE] `fypref.bib`: BibTeX-File which stored all your cited materials. For more about BibTeX file Format please check [BibTeX Format Description](http://www.bibtex.org/Format/) from bibtex.org.

    > The default bibliography style is `plain`, you can change it if you want.

    > BibTeX: This software together with LaTeX can help you easily cite and create a bibliography list.

6. [FILE] `thesistemplate.tex`: All Included Packages, settings. Create this separate file for project tidiness. Sure you will need to add extra packages sometime in the future, please remember the order of the package in this file matters. It also includes the font size, linespace, logo, and etc.. Please don't change the predefined commands or variables unless you need what you are doing.

7. [FILE] **`thesis.tex`**: The most important file, defining the author's name, supervisor's name, the degree, date, and etc. 

## Acknowledgements

* Dr.Li, [HKBU Thesis](https://github.com/lileipisces/HKBUthesis)
* Department of Mathematics, Hong Kong Baptist University, [Thesis Templates](https://www.math.hkbu.edu.hk/stuarea/RPG.html)

Feel free to create an issue if you have any problems.
