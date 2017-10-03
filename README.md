# AdruinoLatexListing
A project to enable Arduino IDE syntax highlighting in LaTeX

Place arduinoLangiage.tex file in your working directory (next to the latex file you're   
working on).  To add it to your project, place:                            
  \input{arduinoLanguage.tex}                                              
somewhere before \begin{document} in your latex file.                      
                                                                           
In your document, place your arduino code between:                         
  \begin{lstlisting}[language=Arduino]                                     
and:                                                                       
  \end{lstlisting}                                                         
                                                                           
Or create your own style to add non-built-in functions and variables.