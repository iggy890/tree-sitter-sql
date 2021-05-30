[![Node.js CI](https://github.com/m-novikov/tree-sitter-sql/actions/workflows/node.js.yml/badge.svg)](https://github.com/m-novikov/tree-sitter-sql/actions/workflows/node.js.yml)

# SQL syntax for tree-sitter

This project initially focuses on PostgreSQL flavor of SQL

## Development

File describing grammar is [grammar.js](./grammar.js)

Every time the grammar file changes code generation needs to be run by invoking `npm run gen`

`npm test` command automatically performs code generation

Tests files are located in [test/corpus](./test/corpus)

[Here](https://tree-sitter.github.io/tree-sitter/creating-parsers#command-test) is the documentation on test file syntax

### Running tests

```
npm install --also=dev
npm test
```
