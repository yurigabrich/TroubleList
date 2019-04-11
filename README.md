# TroubleList

Track changes of troubled texts left behind.

# How to use

1. Copy the [trouble.tex](https://github.com/yurigabrich/TroubleList/blob/master/trouble.tex) file into your LaTeX workspace.
2. Load the aforementioned file in the preamble (you may use `\input{trouble}`).
3. Tag a piece of text using `\trouble[optional argument]{Enter your highlight troubled text here}`. Check the trouble as finished passing the optional argument value of `x`.
4. To get a list of troubles use `\listoftroubles`.

# REFs

- https://tex.stackexchange.com/questions/168832/using-hypertarget-caption-in-hyperlink-caption
- https://tex.stackexchange.com/questions/244694/writing-to-aux-you-cant-use-a-prefix-with-the-character
- https://tex.stackexchange.com/questions/8351/what-do-makeatletter-and-makeatother-do
- https://tex.stackexchange.com/questions/54854/reference-plain-text
- https://tex.stackexchange.com/questions/9874/edef-containing-utf8-umlaut-characters
