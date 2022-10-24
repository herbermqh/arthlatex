# Paquetes incluidos
1. `xcolor` con opciones `x11names,table,svgnames,usenames,dvipsnames`
2. `amsmath`
3. `amsfonts`
4. `amssymb`
5. `latexsym`
6. `cancel`
7. `xparse`
8. `enumerate`
9. `enumitem` con la opción `shortlabels`
10. `babel` con la opción `spanish,es-tabla,es-noshorthands`
11. `pdfpages`
12. `marginfix`
13. `framed`
14. `titletoc`
15. `etoolbox`
16. `probsoln`
17. `empheq`
18. `expl3`
19. `systeme`
20. `polynom`
21. `xstring`
22. `microtype`
23. `lipsum`
24. `pdftexcmds`
25. `catchfile`
26. `ifluatex`
27. `ifplatform`
28. `mhchem`
29. `chemfig`
30. `ulem`
31. `modiagram`
32. `stackengine` con la opción `usestackEOL`
33. `anyfontsize`
34. `inputenc` con la opción `utf8`
45. `fontenc` con la opción `T1`
46. `mathptmx`
47. `tgtermes`
48. `setspaces` con la opción `onehalfspacing`
49. `hyperref`
50. `bookmark`
51. `titlesec`
52. `epigraph`
53. `sidenotes`
54. `multicol`
55. `longtable`
56. `multirow`
57. `booktabs`
58. `tabularx`
59. `array`
60. `float`
61. `mathtools`
62. `caption`
63. `scalerel`
64. `animate`
65. `tikz`
66. `pgfplots`
67. `pgfmath`
68. `wrapfig`
69. `floatflt` con la opción `rflt`
70. `pgf`
71. `pgffor`
72. `pgfkeys`
73. `graphicx`
74. `subfigure`
75. `tkz-fct`
76. `tkz-euclide`
77. `tikz-3dplot`
78. `makeidx`
79. `natbib`
80. `asymptote`
81. `geometry`
82. `layout`
83. `tikzpagenodes`
84. `tcolorbox`
85. `varwidth`
86. `thmtools`
87. `changepage`
88. `mdframed`
89. `environ`
# Comandos de seccionizado
1. `\fosection` se debe utilizar dentro del archivo `FORMULARIO-*`.
# Herramietas básicos de formateado.
## Notas en el margen y problemas resueltos o propuestos
1. El comando `\note{<text>}` añade notas (texto) en el margen cuando este comando se invoca en el parte téorica o en el archivo `TEORIA-*`
2. El comando '\note{}' añade notas en problemas resueltos o propuestos.
## Listas
1. Lista de axiomas:
```tex
\begin{listaxiom}[<label (default A)>]
  \item[<name axiom (default empty)>]
\end{listaxiom}
```
2. Proposiciones:
```tex
\begin{listproposition}
  \item[<name proposition (default empty)>]
\end{listpropostion}
```
3. Premisas:
```tex
\begin{listpremise}[<label (p)>]
  \item
\end{listpremise}
```
4. Lista con descripciones:
```tex
\begin{listdescription}
  \item[<description>]
\end{listdescription}
```
5. Lista enumerado con descripciones (se utiliza para las formas de resolución de problemas):
```tex
\begin{listdescription}[<description>]
  \item
\end{listdescription}
```
6. Lista de incisos de una pregunta (para ejemplo, problemas resueltos y propuestos)
```tex
\begin{listquestion}
  \item
\end{listquestion}
```
# Tablas
## Nuevos tipos de columna.
Columnas de tipo matemático `C` (center), `L` (left) y `R` (right).
## Entornos
1. Ereda todas las funciones de entorno `tabular`
```tex 
\begin{tabularmargin}[]{}{}
  
\end{tabularmargin}
```
2.
```tex 
\begin{tabularbody}[]{}{}
  
\end{tabularbody}
```
3.
```tex 
\begin{tabularfullwidth}[]{}{}
  
\end{tabularfullwidth}
```
# Figuras
## Comandos
1. `\imagemargin[]{}`
2. `\imagebody[]{}[]`
3. `imagequestion{}[]`
4. `\subimage[]{}[]`
5. `\subgraph[]{}{}`
## Entornos
1. 
```tex 
\begin{imagemarginseveral}[]{}
  
\end{imagemarginseveral}
```
2. 
```tex 
\begin{imagebodyseveral}[]{}
  
\end{imagebodyseveral}
```
3. 
```tex 
\begin{imagefullwidthseveral}[]{}
  
\end{imagefullwidthseveral}
```
4. 
```tex 
\begin{graphbody}[]{}
  
\end{graphbody}
```
5. 
```tex 
\begin{graphmargin}[]{}
  
\end{graphmargin}
```
6. 
```tex 
\begin{graphfullwidth}[]{}
  
\end{graphfullwidth}
```
7. 
```tex 
\begin{scaletikzpicturewidth}[]
  
\end{scaletikzpicturewidth}
```
# Modo matemático
## Entornos
1. Entorno para crear una caja de respuesta de un ejericio.
```tex
\begin{answer}
  <matematical expresion>
\end{answer}
```
2. Entorno para crear una caja de formula.
```tex
\begin{formula}
  <matematical expresion>
\end{formula}
```
3. 
```tex
\begin{hmatrix}{}
  
\end{hmatrix}
```
4. 
```tex
\begin{systemeq}
  
\end{systemeq}
```
## Comandos
1. `\overarc{<math expresion>}` Crea un arco encima del expresión matemática.
2. `\pushright{<math expresion>}` 
3. `\pushleft{<math expresion>}`
4. `\pg` expande `P.G.:` (progresión geométrica)
5. `\pa` expande `P.A.:` (progresión aritmética)
6. `\cs` expande `C.S.` (conjunto solución)
7. `\ga` expande `GA` (grado absoluto)
8. `\gr` expande `GR` (grado relativo)
9. `\angstrom` se obtiene simbolo de angstrom
10. `\vec{<math expresion>}` se obtiene vector.
11. `\colog` operador matemático.
12. `\sech` operador matemático.
13. `\sgn` operador matemático.
14. `\mcd` operador matemático.
15. `\cis` operador matemático.
16. `\arccot` operador matemático.
17. `\arcsec` operador matemático.
18. `\arccsc` operador matemático.
19. `\deth` operador matemático.
20. `\traz` operador matemático.
21. `\adj` operador matemático.
22. `\proy` operador matemático.
23. `\mol` operador matemático.
23. `\parrow{}`
24. `\darrow{}`
24. `\aarrow{}`
24. `\marrow{}`
25. `\amatrix{}`

# Referencias cruzadas
## Tablas
`\reftbl{<value>}`
## Figuras
`\reffig{<value>}`

# Otros comandos y entornos
## Comandos
1. `\usarproblema{}{}{}`
2. `\chapterfile[]{}`
3. `\loadbbook{}{}`
4. `\loadbpractice{}`
5. `\loadbexam`
6. `\organic[<name>]{<code>}`
## Entornos
1. 
```tex 
\begin{exampleillustrative}[]
  
\end{exampleillustrative}
```
2. 
```tex 
\begin{demostration}[]
  
\end{demostration}
```
3. 
```tex 
\begin{postulate}[]
  
\end{postulate}
```
4. 
```tex 
\begin{definition}[]
  
\end{definition}
```
5. 
```tex 
\begin{theorem}[]
  
\end{theorem}
```
6. 
```tex 
\begin{corolario}[]
  
\end{corolario}
```
7. 
```tex 
\begin{lema}[]
  
\end{lema}
```
8. 
```tex 
\begin{example}[]
  
\end{example}
```
9. 
```tex 
\begin{strategy}[]
  
\end{strategy}
```
10. 
```tex 
\begin{tabox}[<title>]
  
\end{tabox}
```
