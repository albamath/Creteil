
Les planches sont composées en Markdown.

Puis converties en html avec pandoc:

```
$ TALK='~/2020-Eiffel/presentation'
$ pandoc -t slidy --mathjax  --slide-level=2 $TALK.md -s -o $TALK.html
$ pandoc -t beamer --pdf-engine=xelatex --slide-level=2 $TALK.md -s -o $TALK.pdf
```