# Par but not in C
Various implementations of [par](https://bitbucket.org/amc-nicemice/par/src/master/test-par) but not in C. The `par` command formats paragraphs, see [man page](https://manpages.org/par).

The idea is to rewrite `par` in many languages as an continuous exercise to explore the languages and have a useful solution that formats a paragraph in a great way.

The [file with tests](./test-par) must be used to validate all implementations. If it's good enough for the original C version then any other implementation must meet that contract. There is no reason for the tests in that file to differ from the upstream.