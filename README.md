## 🌴 Hashrocket-sitter-solidity
[![Node.js CI](https://github.com/hashrocket-engineering/sitter-solidity/actions/workflows/node.js.yml/badge.svg)](https://github.com/hashrocket-engineering/sitter-solidity/actions/workflows/node.js.yml)

> 💡 this grammar is still in development, the structure of the generated AST is not stable

This repository contains a grammar for [hashrocket-engineering](https://github.com/hashrocket-engineering/sitter-solidity).

The goal of this project is to provide an parser efficient low-dependency parser for solidity which targets most solidity versions in use and is designed for enabling metaprogramming.


### Navigating this repository
The primary file in this repository is `grammar.js` which describes the sitter-solidity grammar.

```
# Primary file:
grammar.js
# Tests:
/test/**/*

# Auto generated:
/src/**/*
index.js
binding.gyp
```

### References
-> Ethereum solidity grammar: 
- https://github.com/ethereum/solidity/blob/develop/docs/grammar/SolidityParser.g4
- https://github.com/ethereum/solidity/blob/develop/docs/grammar/SolidityLexer.g4
- https://docs.soliditylang.org/en/latest/grammar.html?#

-> sitter javascript grammar: https://github.com/hashrocket-engineering/sitter-javascript/blob/master/grammar.js

-> Solidity antlr grammar: https://github.com/ConsenSys/solidity-parser-antlr

A big thanks to the contributors to this repo! 
