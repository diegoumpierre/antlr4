# ANTLR4 Playground

This is my personal repository for experimenting with [ANTLR4](https://www.antlr.org/), a powerful parser generator for reading, processing, executing, or translating structured text or binary files.

## 🚀 About

This repository contains grammar files (`*.g4`), example source files, and Java-based parser code for learning and testing ANTLR4. It's intended as a sandbox for building domain-specific languages (DSLs), exploring grammar design, and integrating parsing into Java projects.

<!--
## 📁 Structure

```
antlr4-playground/
├── grammars/           # .g4 files for grammars
├── examples/           # Sample input files to parse
├── src/                # Java source code using the generated parser
├── test/               # Unit and integration tests
├── docs/               # Notes and grammar explanations
├── .gitignore
├── pom.xml             # Maven config (if using Maven)
└── README.md
```

## 🔧 Requirements

- Java 11+ (Java 17 or 21 recommended)
- [ANTLR4 Tool](https://www.antlr.org/)
- [Maven](https://maven.apache.org/) or [Gradle](https://gradle.org/) (optional but useful)
- ANTLR4 Java runtime: `org.antlr:antlr4-runtime`

## 🧪 Run Example

```bash
# Generate parser and lexer (if using CLI)
antlr4 grammars/MyGrammar.g4 -o src/main/java -visitor -package my.grammar

# Compile and run Java files
javac -cp .:antlr-4.X-complete.jar src/my/grammar/*.java
java -cp .:antlr-4.X-complete.jar my.grammar.Main
```
-->
## 📚 Learning Resources

- [ANTLR4 Book: The Definitive Guide](https://pragprog.com/titles/tpantlr2/the-definitive-antlr-4-reference/)
- [ANTLR Mega Tutorial (GitHub)](https://github.com/antlr/grammars-v4)
- [ANTLR4 by Example](https://tomassetti.me/antlr-mega-tutorial/)

## 🧠 Goals

- ✅ Practice grammar design
- ✅ Build and test custom parsers
- ✅ Explore DSL design
- ✅ Integrate parsing logic in Java

## 👨‍💻 Author

**Diego Umpierre**  
[LinkedIn](https://www.linkedin.com/in/diego-umpierre/)  
Feel free to fork or open issues if you have suggestions!

## 📝 License

This repository is licensed under the MIT License.
