Writing some letters to my Congresspeople after this 2016 election.

I need an `address.tex` file for my address—it is shockingly easy to get one’s address in America, but still. This `address.tex` file contains, e.g.:

```tex
Firstname Lastname \\
21 Bridge Street \\
City, XX 98765
```

Then I run
```
$ pdflatex FILE.tex
```
and `pdflatex` creates a PDF, `FILE.pdf`.

On macOS, I installed `pdflatex` via [MacTeX](https://tug.org/mactex/).

`pdflatex` creates a bunch of temporary files. I remove them all with
```
$ ./clean.sh
```
