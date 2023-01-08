TheXis
=======

LaTeX class for textual documents at Polytechnic School of USP.

TheXis (pronounce: `tɛʧiz`) follows the ABNT thesis class adapted from: 

1. Prof. Paulo Barreto: on at-the-time standards, available on [link](https://www.ime.usp.br/~leofl/tex/));
2. Luiz Chamon: on 2013-standards, available on [link](https://github.com/lfochamon/poliTeX)). 

## Table of contents

1. [Features](#features)
2. [Monolithic template](#monolithic-template)
3. [Backlog](#backlog)
4. [Bibliography](#bibliography)

## Features

The current class presents considerable changes on class implementation and features. 

The main remarkable changes are:

1. Unsupported non-based POLI-USP standards fixes: functions, headers, titles, table of contents, among others;
2. Code refactor: added comments to allow maintainability. The new class has half the previous class size;
3. Bad practices removal: undesirable ```fancyhdr``` e ```geometry```;
4. Pre-textual implementation changes;
5. New features: 
    - pre-textual and under chapter titles epigraph;
    - `\part`;
    - multiple authors;
    - Bachelor thesis;
6. "(Falsa) folha de rosto" recommended versions (Original|Corrigida). 
 
__Remark__: Feature 6 has no lock on provided and recommended versions. It means, the user may assign e.g. `\folhaderosto{pineapple}` without warning or error log message. 

## Monolithic template

You may edit available `tex` file and generate `pdf` file on: 

1. TeX editors e.g. `[kile, texstudio, texworks]`;
2. Combination of text editors and terminal command run `pdflatex template.tex` 

## Backlog
    
1. Internacionalization: support languages others than `[brazil, portuguese, english]`;
2. Switch languages automatically on:
    - Preamble;
    - Default titles;

## Bibliography

[1] USP standards: https://www.livrosabertos.sibi.usp.br/portaldelivrosUSP/catalog/book/459

