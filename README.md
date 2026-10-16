# Tokenization and Stemming

Java tokenization and stemming over the included Cranfield document collection.
The program reports document, token, stem, and frequency statistics to standard output.

## Run from the repository root

Install a JDK providing `javac` and `java`.
Compile into a separate output directory, then pass the corpus folder as the first argument:

```sh
mkdir -p out
javac -d out Stemmer.java tokenization.java
java -cp out tokenization Cranfield
```

Use a different nonempty document directory by replacing `Cranfield` with its path.
The entry-point class is lowercase `tokenization`; there is no `mainClass` class.
Do not point the program at the repository root, which also contains source and assignment documents.

[Question.pdf](Question.pdf) and [Program_Description.docx](Program_Description.docx) retain the original assignment context.
