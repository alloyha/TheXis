TheXis
=======

LaTeX class for textual documents at Polytechnic School of USP.

TheXis (pronounce: `tɛʧiz`) follows the ABNT thesis class adapted from: 

1. Prof. Paulo Barreto: on at-the-time standards, available on [link](https://www.ime.usp.br/~leofl/tex/));
2. Luiz Chamon: on 2013-standards, available on [link](https://github.com/lfochamon/poliTeX)). 

Features
--------

The current class presents considerable changes on class implementation and features. 

Remarkable changes are:

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
 
__Remark__: Feature 6 has no lock on provided and recommended versions. It means, the user may assign e.g. `\folhaderosto{pineapple pie}` without warning or error log message. 
  
Backlog
--------
    
1. Internacionalization: supports `english`. "Other languages" is the next step;
2. Switch languages automatically on:
    - Preamble;
    - Default titles;

# Bibliography

[1] USP standards: https://www.livrosabertos.sibi.usp.br/portaldelivrosUSP/catalog/book/459

