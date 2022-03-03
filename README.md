# uclanotes
[![Build status](https://ci.appveyor.com/api/projects/status/pjxh5g91jpbh7t84?svg=true)](https://github.com/tingfengx/uoftnotes)
[![made-with-latex](https://img.shields.io/badge/Made%20with-LaTeX-1f425f.svg)](https://www.latex-project.org/)
[![License: CC BY-NC-SA 4.0](https://img.shields.io/badge/License-CC%20BY--NC--SA%204.0-lightgrey.svg)](https://creativecommons.org/licenses/by-nc-sa/4.0/)
<!-- [![HitCount](http://hits.dwyl.io/tingfengx/uoftnotes.svg)](http://hits.dwyl.io/tingfengx/uoftnotes) -->

## &#x1F4DA; Notes for some of my courses at University of California Los Angeles  
... a continuation to [tingfengx/uoftnotes](https://tingfengx.com/uoftnotes/)
  
### **Notes in progress:**  
#### &#128210; 2022 Winter Quarter
- [**CS262a**](./2022W/CS262a/bayesian.pdf/). Bayesian Networks. The focus of this course is on the theory and practice of knowledge representation and reasoning under uncertainty within the framework of probabilistic graphical models---with a major emphasis on Bayesian belief networks.
  
   
## &#x1F4BB; Typesetting in \LaTeX
Most of these notes were written with a software called TeXpad. Unfortunatelly, this brilliant application is only available on MacOS right now. But if you are using a Mac, I would highly recommend you try it out. (I was not paid by TeXpad in anyway lol. )
<details>
  <summary><b>(Legacy) Compiling with Makefile</b></summary>
  
- Compiled using ```pdflatex```:
``````
$ pdflatex --version
pdfTeX 3.14159265-2.6-1.40.20 (TeX Live 2019)
kpathsea version 6.3.1
Copyright 2019 Han The Thanh (pdfTeX) et al.   
``````  
  
- Compilation automated with ```latexmk```:
``````
$ latexmk -version
Latexmk, John Collins, 26 Dec. 2019. Version 4.67
``````  
This is particularly useful to automate the multiple runs of ```pdflatex``` needed for some documents.  
- Please note that some of these notes used the LaTeX package `minted`. To compile the documents containing `minted` using ```latexmk```, you need to use the shell escape flag. Please (create if not exist) add the following to your `~/.latexmkrc`.
``````
$latex = 'latex -interaction=nonstopmode -shell-escape';
$pdflatex = 'pdflatex -interaction=nonstopmode -shell-escape';
``````  
- [Make](https://www.gnu.org/software/make/) is a build automation tool that automatically builds executable programs and libraries from source code by reading files called Makefiles which specify how to derive the target program. In the project, we are using it to automate the compilation of the pdf documents from the LaTeX source codes using ```pdflatex``` as well as clean up all the not needed auxilary log files. 
</details>

## Template
Check out my commands and templates at https://tingfengx.com/tex/. 

## License 
[![licensebuttons by-nc-sa](https://licensebuttons.net/l/by-nc-sa/3.0/88x31.png)](https://creativecommons.org/licenses/by-nc-sa/4.0)    
Unless otherwise stated, all files in this repo are licensed under [Attribution-NonCommercial-ShareAlike 4.0 International](https://creativecommons.org/licenses/by-nc-sa/4.0/). You can find the full legal code as well as its translations [here](https://creativecommons.org/licenses/by-nc-sa/4.0/legalcode). By the license, in human readable words, you are free to
- Share — copy and redistribute the material in any medium or format
- Adapt — remix, transform, and build upon the material

under the following terms:

- Attribution — You must give [appropriate credit](https://wiki.creativecommons.org/wiki/License_Versions#Detailed_attribution_comparison_chart), provide a link to the license, and [indicate if changes were made](https://wiki.creativecommons.org/wiki/License_Versions#Modifications_and_adaptations_must_be_marked_as_such). You may do so in any reasonable manner, but not in any way that suggests the licensor endorses you or your use.
- NonCommercial — You may not use the material for [commercial purposes](https://creativecommons.org/faq/#Does_my_use_violate_the_NonCommercial_clause_of_the_licenses.3F).
- ShareAlike — If you remix, transform, or build upon the material, you must distribute your contributions under the [same license](https://creativecommons.org/share-your-work/licensing-considerations/compatible-licenses) as the original.
- No additional restrictions — You may not apply legal terms or [technological measures](https://wiki.creativecommons.org/wiki/License_Versions#Application_of_effective_technological_measures_by_users_of_CC-licensed_works_prohibited) that legally restrict others from doing anything the license permits.

Note:

- You do not have to comply with the license for elements of the material in the public domain or where your use is permitted by an applicable [exception or limitation](https://creativecommons.org/faq/#Do_Creative_Commons_licenses_affect_exceptions_and_limitations_to_copyright.2C_such_as_fair_dealing_and_fair_use.3F). I.e., The rights of users under exceptions and limitations, such as fair use and fair dealing, are not affected by the CC Licenses.
- No warranties are given. The license may not give you all of the permissions necessary for your intended use. For example, other rights such as [publicity, privacy, or moral rights](https://wiki.creativecommons.org/wiki/Considerations_for_licensors_and_licensees) may limit how you use the material.

## Credits 
- The markdown version of the license is from https://github.com/idleberg/Creative-Commons-Markdown by @idleberg
- CC License badges are from https://gist.github.com/lukas-h/40df8fcbac877be380591787e4af996c by @lukas-h
- Open Source badge from https://github.com/ellerbrock/open-source-badges/ by @ellerbrock
- View count badge from https://github.com/dwyl/repo-badges by @dwyl
