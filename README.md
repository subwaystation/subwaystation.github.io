# cv

```bash
asciidoctor-pdf index.adoc && asciidoctor -a docinfo=shared index.adoc && firefox index.html
```

How to replace spaces in file names

```bash
for f in *\ *; do mv "$f" "${f// /_}"; done
```