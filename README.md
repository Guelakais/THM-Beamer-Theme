# THM-Beamer-Theme
A theme designed for the Latex beamer class using the design guidelines of the THM
#Possible changes to the beamerthemeTHM.sty
This file allows you to add any additional image references.
```
%\logo{\vspace{0.3\paperheight}\includegraphics[angle=90,scale=0.05]{themeRessources/THM.png}}

%\titlegraphic{\includegraphics[scale=0.07]{themeRessources/exampleLogo.png}}
```
These are lines 8 - 10. The title image will be at the top centre of your frame. The logo will be on the sides.
```
%\logo{\ifplacelogo\vspace{0.3\paperheight}\includegraphics[angle=90,scale=0.05]{themeRessources/THM.png}\fi}
```
This is line 28. uncomment and insert your own side logo image that you want to show on the sides of the frame.
# Usage
Put beamerthemeTHM.sty into the same folder as your main .tex file and add the following:
```latex
\usetheme{THM}
```
All major environments are supported. For further information look at the example.tex and example.pdf.

Pull re:w!quest andimprovements are highly appreciated.
