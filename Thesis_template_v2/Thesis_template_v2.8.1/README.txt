v 2.8 (2013-05-23) by Matthias Keller

* Fixed header line bug, where wrong headerline was displayed for *chapter (see kapitel9.tex) for an example 
* Example for including figures from matlabfrag was included in the images section (kapitel4.tex)

v 2.7 (2013-01-21) by Martin W. Krueger

* year on titlepage is now automatically updated
* added conditions for studnet thesis / PhD thesis / PhD thesis for book print
* Changed title page to KIT layout (test)
* Added flags for selecting language and citation style

v 2.6 (2012-10-17) by Martin W. Krueger

* IEEE style references are now sorted and compressed
* Changed linespacing to some nice looking spacing between single and onehalf spacing
* Packages added: include Matlab code in LaTeX, enable strike-out command
* added hyphenation to define hyphenation for certain words
* added example how to cite books with pages and / or chapters
* cleaned up LaTeX code: moved LaTeX definitions to own file, moved style files to subfolder
* APA style referencing: Removed listin of DOI/URL/URN in reference section.

v 2.5 (2012-06-21) by Matthias Keller

* changed name used for figures in figure captions from "fig." to "figure" and from "Abb." to Abbildung
* moved list of tables and list of figures to the end of the document

v 2.4 (2012-05-25) by Matthias Keller

*added "novbox" option to pdfsync package to fix issues in editing tabular

v 2.3 (2012-03-7) by Matthias Keller

*Updated "Eidesstattliche Erklaerung" according to the new examination regulations for Bachelor and Master

v 2.2 (2012-01-17) by Eike WŸlfers and Matthias Keller

* Makefile was updated
* .aux and ._-files removed from template
* refbase.bib added to bibtex

v 2.1 (2011-12-20) by Matthias Keller

* Workaround for two line headings was replaced by a change in the svmono class. From now on all two line titles should be hanging when using the normal \chapter, \section... commands
* A German version for the bibstyle dipl.bst was included- using diplGerman.bst instead of "and" "&" will be used. Plus: Capital letters will not be changed.
* A modified version of natbib.bst (natbibIBT.bst) was included. In this file Christopher replaced "und andere" with "et. al." and "und" with "&" (Thank you very much!)

v 2.0 (2011-11-16) by Matthias Keller

* Added workaround for two line headings
* Modified bibstile for Ph.D. theses: publisher is now displayed correctly

v1.9 (2011-05-17) by Martin W. Krueger

 * Added colored table support
 * Added example for color tables
 * Added underscore-hack, but left it uncommented.

v1.8 (2011-05-03) by Frank M. Weber

 * Changed font size to 11pt (see commands in dipl.sty)
 * Included commands for 13 pt font size in dipl.sty (uncomment for dissertations)
 * Included title page for diss
 * Added warning in main document not to use underscores in labels and file names
 
v1.7 (2011-02-24) by Martin W. Krueger

* Added option for APA-style references


v1.6 (2010-10-12) by Frank M. Weber

* Fixed compilation issues
* Fixed bibtex compilation
* Included some add-ons proposed by Sebastian Seitz (e.g. shortcuts like \Div, \rot, etc., see end of dipl.sty for all commands)

v1.5 (2010-04-29) by Frank M. Weber

* Fixed Umlaut problems when English figure captions were activated

v1.4 (2010-01-14) by Frank M. Weber

* Added KIT logo


v1.3 (2009-06-25) by Marc Aubreville and Frank M. Weber

* Reference titles are not converted to small letters by default

v1.2 (2009-05-14) by Frank M. Weber

 * enabled clickable links for references, chapters and formulars (package hyperref)

v1.1 (2008-09-30) by Dmytro Farina and Frank M. Weber

* Only supposed to work with pdflatex now (because we only use this)
* Fixed inlucsion of pictures - use pdf or bitmap pictures
* Publication file is now refbase.bib and points to correct file on bordeaux
* Should be MikTex compatible now (for use on Windows systems)
* Page margins extended
* Added option to switch to english captions etc. (uncomment line in main file)
* Minor cosmetic changes

Note that when using make, only "make pdf" makes sense

v1.0 never existed officially

