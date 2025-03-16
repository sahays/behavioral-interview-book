# Acing Behavioural Interviews

.docx export

```
# Step 1: Convert AsciiDoc to DocBook
asciidoctor -b docbook behavioral-interview-book.adoc -o ./dist/behavioral-interview-book.xml
# Step 2: convert to docx
pandoc -f docbook -t docx ./dist/behavioral-interview-book.xml -o ./dist/behavioral-interview-book.docx
```

.epub export

```
# convert to epub
asciidoctor-epub3 behavioral-interview-book.adoc -o ./dist/behavioral-interview-book.epub
```

.pdf export

```
asciidoctor-pdf behavioral-interview-book.adoc -o ./dist/behavioral-interview-book.pdf
```
