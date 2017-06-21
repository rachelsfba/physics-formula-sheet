# AP Physics I & II Formula and General Information Sheet
A document created by colleagues and myself to help understand high school
physics. A secondary purpose was for us to teach ourselves LaTeX, which is why
you will undoubtedly notice many formatting warnings, style quirks, and bad
habits (for one, notice all the "Overfull \hbox" warnings!). Feel free to
contribute (see [Contributors](#Contributors) section).

**PLEASE NOTE:** We make no guarantee of accuracy whatsoever about the content of
this document. Though we have done our best to keep verify things, the
information in this document was gathered from many sources (our textbook, class
lectures, online resources, etc.), and it is therefore pretty hard to keep
things consistent, well-sourced, and accurate. This document was made by high
schoolers after all!

# Compiling
There is currently no Makefile or similar build automation file. I just compile
the document using at least 3 passes with `pdflatex`:

    $ pdflatex main.tex

You probably would be better off just visiting the
[Releases](https://github.com/omattei/PhysFormulaSheet/releases) section,
though!

# Authors
This document was originally created by Charles German, Richard Shaw, and David
Robie. We will probably not continue to maintain this project, as it has largely
outlived its original purpose---helping us pass Physics in high school and
college. 

# <a name="Contributors"></a> Contributors
That said, if you would like to fork this project and have your work credited,
be our guest. You can add your name to [CONTRIBUTORS](CONTRIBUTORS) if you would
like. Pull requests that do not deviate too far from the spirit of the document
will be accepted as soon as I get around to it.

# License
This work is licensed under the Revised BSD License, with the *huge exception* of
some sections of the document where the original content is not ours. I will do
my best to properly attribute/remove such content as requested. To this end, I
have replaced as many copyrighted graphics as possible with custom-made TikZ
ones.  

See [LICENSE](LICENSE) for more information. 
