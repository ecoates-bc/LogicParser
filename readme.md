### LogicParser
To use, call `python3 LogicParser.py "expression"` e.g:

`python3 LogicParser.py "p V (~p -> q)"`

#### Syntax:
Expressions are recursive and follow an 'expression connective expression' structure

Use parentheses to call another expression as a part of an expression



Entity: lower case letter

Negation: `~`

And: `^`

Or: `V`

Implication: `->`
