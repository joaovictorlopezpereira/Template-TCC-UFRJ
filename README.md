# Template-TCC-UFRJ

## Overview

This repository provides an independent revision of the LaTeX undergraduate thesis template provided by the [Institute of Computing at the Federal University of Rio de Janeiro (IC/UFRJ)](https://ic.ufrj.br/info/tcc-bcc/).

The original template contained compilation issues, outdated commands, and inconsistencies in formatting and source-code organization. This repository aims to address these problems while preserving the template's original purpose. **This is not an official IC/UFRJ release.**

## Modifications

All documented changes are listed in [modifications.md](modifications.md), including corrections, replacements of deprecated commands, and source-code cleanup. The repository's complete commit history is also available for anyone who wishes to inspect the changes made to the original template.

## Compatibility

This code was tested on Windows with **MiKTeX** and on Linux with **TeX Live**. We recommend using an updated LaTeX distribution (as well as packages). Older package versions, particularly `datatool-base` versions prior to 3.0 (released in 2025), may not recognize options used by this template and can cause compilation errors.

## Sources and Contributors

- **Original template:** [IC/UFRJ undergraduate thesis page](https://ic.ufrj.br/info/tcc-bcc/).
- **AbnTeX2 source files:** [abnTeX2 repository](https://github.com/abntex/abntex2), vendored with local corrections (detailed in the commit history).
- **Contributors:** João Victor Lopez Pereira and William Victor Quintela Paixão.
