# tree-sitterNG

Tree-sitter is a parser generator tool and an incremental parsing library. It can build a concrete syntax tree for a source file and efficiently update the syntax tree as the source file is edited. Tree-sitter aims to be:

- **General** enough to parse any programming language
- **Fast** enough to parse on every keystroke in a text editor
- **Robust** enough to provide useful results even in the presence of syntax errors
- **Dependency-free** so that the runtime library (which is written in pure C) can be embedded in any application

This is the NG (Next Generatio) fork of tree-sitter.
We're closely tracking the changes made in the original tree-sitter github repository, however, the big diffeernce is unnecessary dependencies have been stripped out.
Rust code has been rewritten in Modern Object Pascal, for easier mainentance and compile times.
NPM dependencies removed as the CLI client has been rewritten in Modern Object Pascal as well.

TODO:
- Rewrite the highlighter library in Modern Object Pascal.
- Rewrite the CLI parser generator tool and extend it with missing features.
- Remove all traces of Rust and NPM.
- Add Modern Object Pascal bindings for the tree-sitter runtime library and highlighter.

## Links

- [Documentation](https://tree-sitter.github.io)
- [Rust binding](lib/binding_rust/README.md)
- [WASM binding](lib/binding_web/README.md)
- [Command-line interface](cli/README.md)
