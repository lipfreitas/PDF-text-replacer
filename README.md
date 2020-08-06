# PDF-text-replacer
Código PHP para Replace em Trechos de Texto via Parâmetro GET, server-side, com dependência do https://tcpdf.org/

## Installation
`git-clone https://github.com/lipfreitas/PDF-text-replacer` on your server folder.

## Use
```
    server-root/?filename='filepath/filename.extension'&original='original-text'&new='new-text'
```
## Requirements
* `temp` folder with www-data ownership and write permissions
* Could not work in PHP 5.6 or less

## Parameters
* Server-root *(server folder where is system is deployed)*
* Filepath *(where is file allocated on server)*
* Filename and Extension *(PDF)*
* Original-text *(Text you want to replace)*
* New-text *(Text you want to replace with)*


____

## Special Thanks :
[tecnickcom's Github : tc-lib-pdf](https://github.com/tecnickcom/tc-lib-pdf "tc-lib-pf Github Page")
