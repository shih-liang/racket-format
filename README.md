# racket-format
Format racket souce file (indentation only) using the default settings of DrRacket’s indentation. See [Racket docs](https://docs.racket-lang.org/style/Textual_Matters.html).

# Usage
Very Simple. Files goes to stdin, results get from stdout.

Like this:

if file ```file_to_be_indented.rkt``` contains

```racket
(+ 1
2
3
4
5)
```

```sh
racket indent.rkt < file_to_be_indented.rkt
```

You will get output like this:

```racket
(+ 1
   2
   3
   4
   5)
```
