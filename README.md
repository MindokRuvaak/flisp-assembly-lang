
# flisp-assembly-lang README
FLISP Assembly language syntax highlighting

Regex:
https://regex101.com/r/6g5IBu/1
https://regex101.com/r/LhxtGB/1
https://regex101.com/r/sLuUOX/1
https://regex101.com/r/NpVupF/1


## Features

## Requirements

Not a strict requirement, but Digiflisp is need to convert 

## Known Issues

Nothing works yet

## Release Notes
### 0.0.2 
Actually started reading the *vsc-extension-quickstart.md* file. 
Added comment support, only ; as line comment start, block comment not supported.
No brackets are supported. 
TextMate is starting to click, the *tmLangiage.json* file now support: 
commetns - 100%
instructions - 100%
symbol - 100%
numeric - 100%
operand - still working on it, this has alot

operand types: 
immediate data - 100%
absolute adress - is  not detected, don't know why, figure out later
PC relative - 100%
indexed - TextMate patterns declared no matching yet, alot of variations here


Renamed language id and grammmar scope + TextMate file to FLISPAssembly

### 0.0.1
Language grammar started:
Symbol-definition and symbol name. 
Enforce all symbol definitions end with a comma (:) and capital letters not allowed in symbols (personal preference and don't know currently how to differenciate symbols from mnemonic otherwise) 
