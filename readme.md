# Awesome Pest. The Elegant Parser [![Awesome](https://awesome.re/badge.svg)](https://awesome.re)

[<img src="https://avatars.githubusercontent.com/u/26044607" align="right" width="100">](https://electronjs.org)

> A curated list of resources, projects, and tools using or for the pest parser generator in Rust

pest is a general purpose parser written in Rust with a focus on accessibility, correctness, and performance. It uses parsing expression grammars (or [PEG](https://en.wikipedia.org/wiki/Parsing_expression_grammar)) as input, which are similar in spirit to regular expressions, but which offer the enhanced expressivity needed to parse complex languages.

Contributions welcome! Read the [contribution guidelines](contributing.md) first.

## Contents

- [Resources](#resources)
- [Projects](#projects)
- [Tooling](#tooling)

## Resources

- [Book](https://pest.rs/book) - The recommended way to start parsing with pest is to read this official book.
- [API reference on docs.rs](https://docs.rs/pest)
- [fiddle editor on pest.rs](https://pest.rs/#editor) - Play with grammars and share them on the official website (and format them!).
- [Gitter](https://gitter.im/pest-parser/pest)
- [Discord](https://discord.gg/XEGACtWpT2)
- [GitHub Discussions](https://github.com/pest-parser/pest/discussions)

## Projects

Here are some example projects using pest:

- [pest_meta](https://github.com/pest-parser/pest/blob/master/meta/src/grammar.pest) (bootstrapped)
- [AshPaper](https://github.com/shnewto/ashpaper)
- [brain](https://github.com/brain-lang/brain)
- [cicada](https://github.com/mitnk/cicada)
- [comrak](https://github.com/kivikakk/comrak)
- [elastic-rs](https://github.com/cch123/elastic-rs)
- [graphql-parser](https://github.com/Keats/graphql-parser)
- [handlebars-rust](https://github.com/sunng87/handlebars-rust)
- [hexdino](https://github.com/Luz/hexdino)
- [Huia](https://gitlab.com/jimsy/huia/)
- [insta](https://github.com/mitsuhiko/insta)
- [jql](https://github.com/yamafaktory/jql)
- [json5-rs](https://github.com/callum-oakley/json5-rs)
- [mt940](https://github.com/svenstaro/mt940-rs)
- [Myoxine](https://github.com/d3bate/myoxine)
- [py_literal](https://github.com/jturner314/py_literal)
- [rouler](https://github.com/jarcane/rouler)
- [RuSh](https://github.com/lwandrebeck/RuSh)
- [rs_pbrt](https://github.com/wahn/rs_pbrt)
- [stache](https://github.com/dgraham/stache)
- [tera](https://github.com/Keats/tera)
- [ui_gen](https://github.com/emoon/ui_gen)
- [ukhasnet-parser](https://github.com/adamgreig/ukhasnet-parser)
- [ZoKrates](https://github.com/ZoKrates/ZoKrates)
- [Vector](https://github.com/timberio/vector)
- [AutoCorrect](https://github.com/huacnlee/autocorrect)
- [yaml-peg](https://github.com/aofdev/yaml-peg)
- [qubit](https://github.com/abhimanyu003/qubit)
- [caith](https://github.com/Geobert/caith) - A dice roller crate.
- [Melody](https://github.com/yoav-lavi/melody)

## Tooling

### IDE Support

- [pest IDE tools](https://github.com/pest-parser/pest-ide-tools) - A main repository with LSP server and VSCode extension.
- [VSCode Extension](https://marketplace.visualstudio.com/items?itemName=pest.pest-ide-tools)
- [IntelliJ IDEA Plugin](https://plugins.jetbrains.com/plugin/12046-pest)
- [pest.vim](https://github.com/pest-parser/pest.vim)
- [pest-fmt](https://github.com/pest-parser/pest-fmt) - It can help to format
pest grammars.
- [pest web debugger](https://github.com/tomtau/pest-web-debug) - Try it [online](https://tomtau.github.io/pest-web-debug/).

### Boilerplate reduction and testing

- [pest-ast](https://github.com/pest-parser/ast) - It can help to reduce boilerplate
when converting pest parse trees to abstract syntax trees.
- [pest_consume](https://crates.io/crates/pest_consume) - This crate can 
help with the parse tree traversing boilerplate.
- [pest-test](https://crates.io/crates/pest-test) - It is a testing framework for pest grammars.


### CLI Debugger

- [pest_debugger](https://docs.rs/pest_debugger/latest/pest_debugger/) - It is a crate for debugging pest grammars. It can be used as a CLI tool or as a library. [See instructions for using the CLI debugger](debugger.md).
