# joda-timer. written as a tool to simplify common tasks in chemistry electronic notebook
This a simple app with the following goal:
1. generate and copy to clipboard the current date stamp (EST or ESD) 
2. calculate and copy to clipboard the difference between two dates 
3. calculate and copy to clipboard mass difference 
4. merge multiple pdfs - saved to Downloads
5. provide a number of frequently used text snippets to describe tasks such as HPLC, flash chromatography etc.
6. process 1D NMR spectral textual data -> H-count (available via clipboard)
7. convert chemical formula -> LCMS snippet (available via clipboard)
8. provde basic RDKit functionality such as SMILES -> formula

The program is written using clojure scittle and js.  Written to replace old python (TKinter) script.
This combination allows for a very simple function without any external dependencies and servers so that it can be used  on any computer with no setup.


