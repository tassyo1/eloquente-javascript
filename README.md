# JavaScript Expressivo

> **Mantenedor:** [Joao Stein](https://github.com/joaostein)

Neste repositório você encontrará os recursos usados para construir
a segunda edição do JavaScript Expressivo (http://eloquentjavascript.net).

Comentários são bem vindos, na forma de issues e pull requests.

## Montando

    npm install --production
    apt-get install asciidoc inkscape
    make html

Para OSX, você pode usar port ou brew para instalar o pacote asciidoc.

Para montar o arquivo PDF:

    apt-get install texlive texlive-xetex texlive-fonts-extra
    make book.pdf

Para montar o livro em ePub:

    make book.epub
