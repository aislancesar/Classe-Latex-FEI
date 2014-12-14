#Classe Latex da FEI
Este repositório contém a classe LaTeX do Centro Universitário da FEI para formatação de trabalhos acadêmicos (monografia, dissertação ou tese), baseada no manual de 2007 da biblioteca. A classe possibilita a criação de um trabalho acadêmico completo, com inserção de elementos pré-textuais (capa, folha de rosto, ficha catalográfica, epígrafe, dedicatória, sumário e listas de figuras, tabelas, algoritmos, siglas e símbolos), passando pelo corpo do texto e elementos pós-textuais (índice remissivo, referências bibliográficas, apêndices e anexos).

No manual, os usuários encontrarão informações detalhadas sobre a utilização da classe, seus comandos e algumas boas práticas para que o trabalho fique no formato desejado pela biblioteca.

##Arquivos no repositório
- **fei.cls**: a classe em si, que deve ser adicionada ao diretório do seu projeto. Se você deseja *utilizar* a classe,é esse o arquivo que te interessa;
- **fei.dtx**: o arquivo documentado do classe, utilizado para instalação através de repositórios de terceiros;
- **fei.pdf**: manual da classe, gerado utilizando a classe, com uma explicação detalhada de como utilizar a classe;
- **Makefile**: o arquivo que descompacta o `dtx` nos demais arquivos (manual, classe e README);
- **modelo.tex**: exemplo básico de documento para ser utilizado como ponto de partida para a escrita de um trabalho;
- **minted.sty**: classe utilizada no processo de desenvolvimento para que os exemplos de códigos fiquem coloridos
- **referencias.bib**: arquivo de referências usado nos exemplos.
- **README**: o arquivo "leiame" da classe, quegerado pelo Makefile e que deve ser enviado para os repositórios internacionais;
- **README.md**: o arquivo "leiame" do repositório, que você está lendo agora.

##Licença
Released under the LaTeX Project Public License v1.3c or later
See http://www.latex-project.org/lppl.txt

##Controle de versão
Para saber as mudanças entre essa versão e as anteriores, [clique aqui](https://github.com/OpenFEI/Classe-Latex-FEI/commits/master).