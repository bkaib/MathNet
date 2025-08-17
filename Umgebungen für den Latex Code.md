	

## Definitionen

Du kreierst eine Definitionsbox mit dem Code unten.

Das `label=defi:name` labelt die Box. Dadurch kann man sie verlinken.

```Latex
\begin{defi}[label=defi:defi_label]{DefiName} \href{https://bkaib.github.io/MathNet/Path-to-Sample-Page}{\includegraphics[width=0.08\textwidth]{img/logo_white.png}}      
	Context
\end{defi}
```

## Sätze

```Latex
\begin{satz}[label=satz:satz_label]{SatzName}{\href{https://bkaib.github.io/MathNet/Path-to-Sample-Page}{\includegraphics[width=0.08\textwidth]{img/logo_white.png}}}
	Context
\end{satz}
```

## Link to a Box

You can link to a box by using the following `\hyperref[label]{Text}`.
For instance to link to the box in [Definitionen](#Definitionen) you can use 

```Latex
\hyperref[defi:defi_label]{Text}
```
