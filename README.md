# Arthlatex
Plantilla LaTeX

# Comandos

# Entornos
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
