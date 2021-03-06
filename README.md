# **`language-eu4mod`**

[![APM](https://img.shields.io/apm/v/language-eu4mod?color=%23147dce&logo=atom&logoColor=%2380f2a6)](https://atom.io/packages/language-eu4mod) [![Travis (.com)](https://img.shields.io/travis/com/Coyote-31/language-eu4mod?label=Atom%20CI&logo=Travis)](https://travis-ci.com/github/Coyote-31/language-eu4mod) [![GitHub](https://img.shields.io/github/license/Coyote-31/language-eu4mod?color=%230f1014)](https://github.com/Coyote-31/language-eu4mod/blob/master/LICENSE)

📦 [**`language-eu4mod`**](https://atom.io/packages/language-eu4mod) is a global **[tree-sitter](http://tree-sitter.github.io/tree-sitter/)** grammar for **Europa Universalis IV**.

## 📄 Description

This package is a **global EU4 grammar** powered by **[tree-sitter](http://tree-sitter.github.io/tree-sitter/)** and developed for the **[⚛️Atom](https://atom.io)** text editor.  
It supports the various languages, from extensions listed below, found in EU4 files. As this grammar is focused on developers working on EU4 mods it provides a *syntax-tree* with *scope mappings* able to handle any language used in files inside EU4 directory. Mainly for modding purposes.

### How to install :

To install [`language-eu4mod`](https://atom.io/packages/language-eu4mod) it's like any other [Atom's package](https://flight-manual.atom.io/using-atom/sections/atom-packages/) :
- Simply in the Atom's settings : `settings > install`.
- From [atom.io](https://atom.io/packages/) registry : [`language-eu4mod`](https://atom.io/packages/language-eu4mod)
- via CLI  :

        apm install language-eu4mod


### Which EU4 file extension is managed :

Extension | Supported
:---:    |   :---:
.mod    |    ✅
.gfx    |    ✅
.gui    |    ✅
.yml    |    ✅


## 📚 Documentation

### How it works :

This package enable Atom's themes with syntax highlighting to catch syntax nodes by specifying scope mappings in a grammar definition file.  
In Atom syntax highlighting is define with `css` class. And this package map the syntax nodes to theses class fallowing grammar `.cson` files directives. But the structure of theses tree-syntax nodes is define in the parser which is in the dependency package : **[`tree-sitter-eu4mod`](https://github.com/Coyote-31/tree-sitter-eu4mod#readme)**

### Repository & Releases :

Link | Info
:---:     |   :---:
**[GitHub repository](https://github.com/Coyote-31/language-eu4mod)** | [![GitHub commits](https://badgen.net/github/commits/Coyote-31/language-eu4mod?icon=git&label=total%20commits)](https://github.com/Coyote-31/language-eu4mod/commits/master)
**[Last release](https://github.com/Coyote-31/language-eu4mod/releases/latest)** | [![GitHub tag (latest by date)](https://badgen.net/github/tag/Coyote-31/language-eu4mod?icon=atom&label=last%20release)](https://github.com/Coyote-31/language-eu4mod/releases/latest)
**[All releases](https://github.com/Coyote-31/language-eu4mod/releases)** | [![total releases](https://badgen.net/github/tags/Coyote-31/language-eu4mod?icon=npm&label=total%20releases)](https://github.com/Coyote-31/language-eu4mod/releases)


## 🐛 Issues or bugs

If you have any issue or find a bug please :

**[Open an issue on GitHub](https://github.com/Coyote-31/language-eu4mod/issues)** | [![GitHub issues](https://img.shields.io/github/issues/Coyote-31/language-eu4mod?logo=github)](https://github.com/Coyote-31/language-eu4mod/issues)
:---:     |   :---:


## 🔍 See also

> - **[Creating a grammar](https://flight-manual.atom.io/hacking-atom/sections/creating-a-grammar/)** (Atom flight manual)
> - **[Tree Sitter](https://tree-sitter.github.io/tree-sitter/)** (Docs)
> - **[`tree-sitter-eu4mod`](https://github.com/Coyote-31/tree-sitter-eu4mod#readme)**  (Parser)
- **EU4 definition** :
  - **[GUI/GFX Xyloz](https://eu4.paradoxwikis.com/User:Xyloz/sandbox)** (eu4.paradoxwikis)
  - **[Interface modding](https://eu4.paradoxwikis.com/Interface_modding)**  (eu4.paradoxwikis)
  - **[Graphical asset modding](https://eu4.paradoxwikis.com/Graphical_asset_modding)**  (eu4.paradoxwikis)


## ©️ License

> **[The MIT License (MIT)](https://github.com/Coyote-31/language-eu4mod/blob/master/LICENSE)**
