# Writing Interpreter in GO

## Lexical Parser

INPUT:

```
"let x = 5 + 5;"
```

OUTPUT:

```
[
  LET,
  IDENTIFIER("x"),
  EQUAL_SIGN,
  INTEGER(5),
  PLUS_SIGN,
  INTEGER(5),
  SEMICOLON
]
```
