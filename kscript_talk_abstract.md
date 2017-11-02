## Title

kscript - Scripting enhancements for Kotlin


## Abstract


Kotlin has some support for scripting already but it is not yet feature-rich enough to be a viable alternative in the shell. Over the last year we have evolved a small utility called kscript which complements the existing scripting support provided by kotlinc
with several new features. First, it caches compiled scripts and tracks changes by using md5 checksums. Second, it allows to declare dependencies with gradle-style resource locators and resolves those with maven. Third, it allows for different modes to provide the scripts including URLs, reading from stdin, local files,  direct script arguments, or by using it as interpreter in the shebang line of a script. Finally, kscript is complemented by a support library to ease the writing of Kotlin scriptlets. The latter includes solutions to common use-cases like argument parsing, data streaming, IO utilities, and various iterators to streamline the development of kscript applications.

Taken all these features together, kscript provides an easy-to-use, very flexible, and almost zero-overhead solution to write self-contained mini-applications with Kotlin. To ensure long-term stability, kscript is developed against a continuously integrated suite of tests. Over the course of the last year it has grown a yet small but active community, and is documented well with an extensive reference manual including many examples and recipes.


## About me

Holger Brandl works as a data scientist at the Max Planck Institute of Molecular Cell Biology and Genetics (Dresden, Germany). He holds a PhD degree in machine learning, and has developed new concepts in the field of computational linguistics. More recently he has co-authored publications in high-ranking journals such as Nature and Science. He is a foo.main developer of the "R Language Integration" for Intellij IDEA, which is increasingly written in Kotlin, and has published several Kotlin artifacts for bioinformatics, high-performance computing and data mining.



#### snippets

**TODO**  backport 1-4 to readme

Scientfic data analysis is often prototypical, but still should be as reproducible as possible. By using kotlin to embed single-file or even inlined mini-programs with depedepende
His most notable contributions to the community are the "R Language Integration" for Intellij IDEA, the high performance computing job manager joblist, and

