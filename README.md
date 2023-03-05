# VU_Master_Thesis_Latex_Template
A simple but effective Latex template for VU students that are about to write their master thesis/master research project 

## Description
This Latex template is based on the VU Standard Thesis template for MSc Computer Science that is available on Overleaf (vu-cs-standard-thesis). I have adapted it to make it simpler and more suitable for use in health studies (e.g. Human Movement Science, Technical Medicine, Biomedical Sciences,  Biomedical Technology, etc.).
The template complies to main rules for a MSc thesis report and furthermore applies best practices for report design. Feel free to adapt to suit your specific needs.

## Components and how to use
The template consists out of the following components:

* Main tex file: thesis.tex --> compile this in your editor to get the complete report
* Sub tex files: introduction.tex, methods.tex, abstract.tex, etc. --> edit your sections here
* Class file: PhDthesisPSnPDF.cls --> style file describing the template style and layout. You don't usualy need to edit this
* Macro file: MacroFile1.tex --> defining some frequently used Latex commands such as \figure

Introduction.tex provides examples of references, tables and figures. Figures should be placed in the ./figures folder. Title page logo's in the ./frontmatter. You can create additional sections by copying existing ones from the ./sections folder. However, in general it is better to stick the standard 5 sections structure. Including more frontmatter can be done by uncommenting lines in the main document. There are templates available in ./frontmatter for acknowledgements, dedications and glossary. Note that [arara tex automation tool](https://github.com/islandoftex/arara) is required for glossary.

Built and tested using Miktex. For questions feel free to reach out to me on Github.

## Change log
* Original version CUEDthesis v1 by Harish Bhanderi, 2002
* Iteration PhDthesis version 2 style file by Jakob Suckale, 2007
* Current VU Master Thesis template v1 by G.J. van der Gun, 2023
