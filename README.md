
Les planches sont composées en Markdown.

Puis converties en html avec pandoc:

```
$ TALK='~/2020-Eiffel/presentation'
$ pandoc -t slidy --mathjax $TALK.md -s -o $TALK.html
```