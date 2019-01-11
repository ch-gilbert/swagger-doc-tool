# swagger-doc-tool

Convert swagger doc(yaml) to AsciiDoctor-based HTML

Based on the [template](https://github.com/ch-gilbert/swagger2markup-maven-project-template).

##  Dependency

- [swagger2markup](https://github.com/Swagger2Markup/swagger2markup)
- [asciidoctorj](https://github.com/asciidoctor/asciidoctorj)
- [asciidoctorj-pdf](https://github.com/asciidoctor/asciidoctorj-pdf)

## How to run

`$ mvn process-resources`

output:
```
target/
└── asciidoc
    ├── definitions.adoc
    ├── html
    │   └── index.html
    ├── overview.adoc
    ├── paths.adoc
    ├── pdf
    │   └── index.pdf
    └── security.adoc
```
