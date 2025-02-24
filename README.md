
# Documents

Personal home for documents generated with Latex for university and work.

```shell
# Build
pdflatex --include-directory lib --output-directory build src/basic-example
pdflatex --include-directory lib --output-directory build src/database-design
pdflatex --include-directory lib --output-directory build src/software-mathematics
pdflatex --include-directory lib --output-directory build src/state-based-modelling.tex

# Install
xcopy /y build\*.pdf install
```

# Links

* [MiKTeX](https://miktex.org/) - Modern Tex distribution 
* [Fuzz](https://github.com/Spivoxity/fuzz) - Z language type checker
