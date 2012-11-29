js-universe
===========

A place to map the observable JavaScript hackers working today and yesterday.

Building/Contributing
---------------------

You'll need to install GraphViz to re-generate the PDF/PNG files from the dot file. On a Mac, try:

```
$ brew install graphviz
```

To regenerate the output, run:

```
$ dot -Tpng js-universe.dot -o js-universe.png
$ dot -Tpdf js-universe.dot -o js-universe.pdf
```
