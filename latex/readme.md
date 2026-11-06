# \[Federal University of Technology — Paraná] UTFPR-Article

[![Open the PDF file](https://img.shields.io/badge/Open%20the%20PDF%20file-green)](./utfpr-article.pdf)

> This LaTeX template (unofficial) allows the production of articles of the [Federal University of Technology — Paraná (UTFPR)](https://www.utfpr.edu.br), including for events such as the Extension and Innovation Seminar (SEI) and the Scientific and Technological Initiation Seminar (SICITE), among others. It was developed using the (default) [article](https://www.ctan.org/pkg/article) LaTeX class. Also, several code snippets developed by users of the [TeX-LaTeX Stack Exchange](https://tex.stackexchange.com/) were used.
>
> Status: added by Luiz E. M. Lima, maintenance on demand.\
> Last updated: October 15, 2026.\
> ![Version 2.1](https://img.shields.io/badge/Version-2.1-blue)

- - -

> Este modelo LaTeX (não oficial) permite a produção de artigos da [Universidade Tecnológica Federal do Paraná (UTFPR)](https://www.utfpr.edu.br), inclusive para eventos, como o Seminário de Extensão e Inovação (SEI) e o Seminário de Iniciação Científica e Tecnológica (SICITE), entre outros. Foi desenvolvido utilizando a classe LaTeX [artigo](https://www.ctan.org/pkg/article) (padrão). Além disso, diversos trechos de códigos desenvolvidos por usuários do [TeX-LaTeX Stack Exchange](https://tex.stackexchange.com/) foram utilizados.
>
> Estado: adicionado por Luiz E. M. Lima, manutenção sob demanda.\
> Última atualização: 15 de outubro de 2026.\
> ![Versão 2.1](https://img.shields.io/badge/Vers%C3%A3o-2.1-blue)

Este arquivo apresenta algumas informações a respeito do UTFPR-Article, modelo LaTeX para produção de artigos da UTFPR, e está dividido nas seguintes seções:

1. Arquivos Constituintes do Projeto.
2. Dicas de Uso.
3. Informações e Dicas sobre TeX-LaTeX.
4. Aplicativos e Ferramentas.
5. Aplicativos e Ferramentas Online.

## 1. Arquivos Constituintes do Projeto

Breve descrição dos arquivos que devem ser manipulados no modelo LaTeX:

- [./utfpr-article.tex](./utfpr-article.tex) (principal).
- [./utfpr-article.bib](./utfpr-article.bib) (referências — base de dados).
- [./Extras/pre-textual.tex](./Extras/pre-textual.tex) (elementos pré-textuais).
- [./Extras/post-textual.tex](./Extras/post-textual.tex) (elementos pós-textuais).

Breve descrição dos demais arquivos constituintes:

- [./readme.html](./readme.html) (descrição e informações).
- [./readme.txt](./readme.txt) (breve descrição).
- [./utfpr-article.pdf](./utfpr-article.pdf) (PDF resultante da compilação).
- [./utfpr-article.sty](./utfpr-article.sty) (pacote de estilos).

Outros arquivos nos diretórios (pastas) do projeto são ilustrações, carregadas no modelo em formatos suportados, assim como alguns arquivos-fontes para geração delas ou de elementos do documento. Não apagar o conteúdo dos diretórios:

- [./Extras/](./Extras/).
- [./Headers/](./Headers/).
- [./Illustrations/](./Illustrations/).
- [./Logos/](./Logos/).
- [./SDG-Stamps/](./SDG-Stamps/).

### 1.1. Compilação dos arquivos

No diretório do projeto, abra um *prompt* de comando (no Windows) ou um console/terminal (no Linux/Unix) e digite *make help* para obter informações a respeito dos comandos de compilação dos arquivos do modelo LaTeX:

- [./make.bat](./make.bat) (**batchfile** para compilar no *prompt* de comando do Windows).
- [./makefile](./makefile) (**makefile** para compilar no console/terminal do Linux/Unix).

## 2. Dicas de Uso

Sempre que for manipular e/ou substituir um dos arquivos constituintes do projeto, mantenha uma cópia do original em um local seguro e/ou renomeie a cópia do original para poder ser seguida como um exemplo no desenvolvimento do seu próprio arquivo.

O único formato de ilustrações que pode ser inserido ao compilar com **LaTeX** é o Encapsulated PostScript (EPS). Se for compilar com **PDFLaTeX**, para produzir um PDF diretamente, tem-se uma escolha mais ampla de formatos de ilustrações para inserir:

- JPG:
  - Amplamente utilizado na internet, em câmeras digitais, etc.
  - Melhor escolha para fotos.
- PNG:
  - Um formato sem perdas e muito comum (ainda que não tanto como JPG).
  - Melhor escolha para diagramas (se não for possível gerar uma versão vetorial) e capturas de tela.
- PDF:
  - Amplamente utilizado para documentos, mas pode ser utilizado para armazenar ilustrações também.
  - Suporta ilustrações vetoriais e mapa de bits, mas não é recomendado para o último, pois JPG ou PNG irá fornecer o mesmo resultado com menor espaço em disco.
- EPS:
  - Pode ser utilizado com a ajuda do pacote epstopdf, que precisa estar instalado, mas não é necessário utilizá-lo no documento.

## 3. Informações e Dicas sobre TeX-LaTeX

- [LaTeX Project](https://www.latex-project.org/).
- [Comprehensive TeX Archive Network (CTAN)](https://www.ctan.org/).
- [TeX Users Group (TUG)](https://www.tug.org/).
- [LaTeX — Wikibooks](https://en.wikibooks.org/wiki/LaTeX/).
- [TeX-LaTeX Stack Exchange](https://tex.stackexchange.com/).

## 4. Aplicativos e Ferramentas

- Compiladores e distribuições TeX-LaTeX:
  - [TeX Live](https://www.tug.org/texlive/) (Linux e Windows).
  - [MiKTeX](https://miktex.org/) (Linux, Mac e Windows).
  - [MacTeX](https://www.tug.org/mactex/) (Mac).
- Editores TeX-LaTeX:
  - [Texmaker](https://www.xm1math.net/texmaker/) (Linux, Mac e Windows).
  - [TeXstudio](https://texstudio.sourceforge.net/) (Linux, Mac e Windows).
  - [TeXworks](https://www.tug.org/texworks/) (Linux, Mac e Windows).
  - [TeXnicCenter](https://www.texniccenter.org/) (Windows).
  - [WinShell](https://www.winshell.de/) (Windows).
- Editores e gerenciadores BibTeX (referências):
  - [JabRef](https://jabref.sourceforge.net/) (Linux, Mac e Windows).
  - [Mendeley](https://www.mendeley.com/) (Linux, Mac e Windows).
  - [Zotero](https://www.zotero.org/) (Linux, Mac e Windows).
  - [Bibfilex](https://sites.google.com/site/bibfilex/) (Linux, Mac e Windows).
  - [Docear](https://www.docear.org/) (Linux, Mac e Windows).
- Editores de equações TeX-LaTeX:
  - [DragMath](https://sourceforge.net/projects/dragmath/) (Linux, Mac e Windows).
  - [EqualX](https://equalx.sourceforge.net/) (Linux, Mac e Windows).
- Editores de ilustrações:
  - [LaTeXDraw](https://latexdraw.sourceforge.net/) (Linux, Mac e Windows).
  - [Asymptote](https://asymptote.sourceforge.net/) (Linux, Mac e Windows).
  - [Inkscape](https://inkscape.org/) (Linux, Mac e Windows).
  - [GIMP](https://www.gimp.org/) (Linux, Mac e Windows).
  - [Dia Diagram Editor](http://dia-installer.de/) (Linux, Mac e Windows).
  - [draw.io](https://www.draw.io/) (Linux, Mac e Windows).
  - [gnuplot](https://gnuplot.sourceforge.net) (Linux, Mac e Windows).
  - [GeoGebra](https://www.geogebra.org/) (Linux, Mac e Windows).
  - [GraTeX](https://sourceforge.net/projects/gratex/) (Linux, Mac e Windows).
- Editores de tabelas TeX-LaTeX:
  - [Excel2LaTeX](https://ctan.org/pkg/excel2latex/) (Windows).
  - [Calc2LaTeX](https://calc2latex.sourceforge.net/) (Linux, Mac e Windows).
  - [LaTable](https://ctan.org/pkg/latable/) (Windows).
- Visualizadores de PDF:
  - [Sumatra PDF](https://www.sumatrapdfreader.org/free-pdf-reader.html) (Windows).
  - [Skim](https://skim-app.sourceforge.io/) (Mac).
  - [Evince](https://wiki.gnome.org/Apps/Evince/) (Linux).
  - [PDF Presenter](https://pdfpresenter.sourceforge.net/) (Linux, Mac e Windows).
  - [Impressive](https://impressive.sourceforge.net/) (Linux, Mac e Windows).
- Interpretadores de Postscript e PDF:
  - [Ghostscript](https://ghostscript.com/) (Linux e Windows).

## 5. Aplicativos e Ferramentas Online

- Compiladores e editores TeX-LaTeX:
  - [Overleaf-UTFPR](https://overleaf.utfpr.edu.br/) (uma instância de [Overleaf](https://www.overleaf.com/)).
  - [Prism](https://prism.openai.com/).
  - [TeXPage](https://www.texpage.com/).
  - [Online LaTeX Editor | Tutorialspoint](https://www.tutorialspoint.com/online_latex_editor.php).
- Editores e gerenciadores BibTeX (referências):
  - [ZoteroBib](https://zbib.org/).
  - [BibTeX Editor](https://truben.no/latex/bibtex/).
  - [BibTeX Tidy](https://flamingtempura.github.io/bibtex-tidy/).
  - [doi2bib](https://www.doi2bib.org/).
  - [Online ris2bib](https://www.bruot.org/ris2bib/).
- Editores de equações TeX-LaTeX:
  - [Formula Sheet](https://formulasheet.com/).
  - [LaTeX Equation Editor | Tutorialspoint](https://www.tutorialspoint.com/latex_equation_editor.htm).
  - [Equation Editor for online mathematics](https://editor.codecogs.com/).
  - [Online LaTeX Equation Editor](https://www.latex4technics.com/).
  - [mathURL](https://mathurl.com/).
  - [Mathcha](https://www.mathcha.io/).
- Editores de ilustrações:
  - [Online Image Editor | Tutorialspoint](https://www.tutorialspoint.com/online_image_editor.htm).
  - [Free Online Whiteboard | Tutorialspoint](https://www.tutorialspoint.com/whiteboard.htm).
  - [Lucidchart](https://www.lucidchart.com/).
  - [draw.io](https://www.draw.io/).
  - [GeoGebra](https://www.geogebra.org/).
  - [Plotly](https://plot.ly/).
  - [tikzcd-editor](https://tikzcd.yichuanshen.de/).
  - [Mathcha](https://www.mathcha.io/).
- Editores de tabelas TeX-LaTeX:
  - [Tables Generator](https://www.tablesgenerator.com/).
  - [LaTeX Tables Editor](https://www.latex-tables.com/).
  - [Table Editor](https://truben.no/table/).
  - [Mathcha](https://www.mathcha.io/).

- - -

Copyright © 2016–2026 [Luiz E. M. Lima](mailto:luizeduardomlima@gmail.com).
