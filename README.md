
# Documents

Latex driven documents for personal use.

```shell
# Build
pdflatex --include-directory lib --output-directory build src/hello-latex
pdflatex --include-directory lib --output-directory build src/sem-assignment

# Install
xcopy /y build\*.pdf install
```

# Links

* [MiKTeX](https://miktex.org/) - Modern Tex distribution 
* [Fuzz](https://github.com/Spivoxity/fuzz) - Z language type checker
