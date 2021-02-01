# Purpose

This project hopes to document the knowledge needed for incoming Masters of Information Systems students.

The intent is to provide self-paced learning which relies primarily on outside resources. In other words, this site is a _curation_ of existing resources rather than being a primary resource itself.

When building out content, don't simply link to outside resources, provide context and commentary. Connect resources together. Highlight the strengths of a particular resource.

# Modules
This site is (will be) organized into modules. Each module should conclude with a set of project exercises learners could complete to demonstrate content mastery.

# Installing and building mkdocs
Building and testing the site requires Python 3 and [mkdocs][mkdocs]. You may also need to install (via `pip3`) specific markdown extensions.

[mkdocs]:https://www.mkdocs.org/user-guide/writing-your-docs/#writing-with-markdown

<!-- TODO: complete installation guide -->
_This portion of the guide—installation for authors—needs to be fleshed out further._

## Install the Material theme
We use the ["Material" theme][m-theme] as a basis for site. This may change in the future. The theme docs pages have some great info on using mkdocs.

[m-theme]:https://squidfunk.github.io/mkdocs-material/getting-started/

```bash
pip3 install mkdocs-material
```

## Installing Python Markdown markdown extensions

See the documentation for more information on the installed Markdown extensions:
* [Python Markdown extensions](https://python-markdown.github.io/extensions/)
* [PymDown extensions](https://facelessuser.github.io/pymdown-extensions/)

```bash
pip3 install pymdown-extensions
pip3 install mdx_breakless_lists
```

If we need additional extensions ([full list](https://github.com/Python-Markdown/markdown/wiki/Third-Party-Extensions)), please discuss with the development team.

## Test
To locally build and test the site, run the following from the command line:

```bash
mkdocs serve
```

If that doesn't work (mkdocs isn't in the Path, which happens sometimes on Windows), try this:
```bash
python -m mkdocs build
```
