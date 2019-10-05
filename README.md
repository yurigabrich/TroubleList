# TroubleList

Track changes of troubled texts left behind.

## How to use

1. Insert the [trouble.tex](https://github.com/yurigabrich/TroubleList/blob/master/trouble.tex) file into your LaTeX workspace.
2. Load the aforementioned file in the preamble (you may use `\input{trouble}`).
3. <details>
     <summary>Tag a piece of text using <code>\trouble[optional argument]{Enter your highlight troubled text here}</code>.</summary>
     <p>Check the trouble as finished passing the optional argument value of <code>x</code>.</p>
   </details>
4. To get a list of troubles use `\listoftroubles`.

### Example of use

```latex
\documentclass{article}
\input{trouble.tex}

\begin{document}

\section{Example of use}

Although this fancy workaround solves the problem, it is expensive \trouble{(looking for seed funding)}. % pending trouble

However the team is fantastic! \trouble[x]{(a human-centered business strategist is still missing)} % trouble solved

\section{List of troubles}

\listoftroubles

\end{document}
```

<table><tr><td>
  <a href="https://www.overleaf.com/docs?snip_uri[]=https://github.com/yurigabrich/TroubleList/blob/master/example.zip?raw=true">Open the MWE in Overleaf</a>
</td></tr></table>


## To-Do

- [ ] Update the way dependency packages are defined.
- [ ] Include options to customize colors.
- [ ] Include dependency package of colors to allow custom colors.

## REFs

- https://tex.stackexchange.com/questions/168832/using-hypertarget-caption-in-hyperlink-caption
- https://tex.stackexchange.com/questions/244694/writing-to-aux-you-cant-use-a-prefix-with-the-character
- https://tex.stackexchange.com/questions/8351/what-do-makeatletter-and-makeatother-do
- https://tex.stackexchange.com/questions/54854/reference-plain-text
- https://tex.stackexchange.com/questions/9874/edef-containing-utf8-umlaut-characters
