# Banco de questões para o pacote EDM

<p align="center">
  <a href="https://github.com/ivanalaman/questionbankEDM">English</a>
</p>

- [Introdução](https://github.com/ivanalaman/questionbankEDM/blob/master/lang/portuguese_br#Introdução)
- [Padronização do nome dos diretórios do banco de questões](https://github.com/ivanalaman/questionbankEDM/blob/master/lang/portuguese_br#Padronização-do-nome-dos-diretórios-do-banco-de-questões)
- [Padronizando o nome dos arquivos](https://github.com/ivanalaman/questionbankEDM/blob/master/lang/portuguese_br#Padronizando-o-nome-dos-arquivos)
- [Formando o banco de questões](https://github.com/ivanalaman/questionbankEDM/blob/master/lang/portuguese_br#Formando-o-banco-de-questões)
  - [Fluxo de trabalho](https://github.com/ivanalaman/questionbankEDM/blob/master/lang/portuguese_br#Fluxo-de-trabalho)

## Introdução
Este repositório é um anexo do pacote [EDM](https://github.com/ivanalaman/EDM) do sofware [R](https://www.r-project.org/). O objetivo é um local de armazenamento de banco de questões para que os usuários possam constantemente compartilhar e atualizar suas avaliações (provas). Aconselhamos que ao baixar o pacote [EDM](https://github.com/ivanalaman/EDM), seja utilizado a interface gráfica para criar seu banco de questões com o intuito de deixar padronizado entre os usuários e para que o aplicativo possa ler corretamente tais arquivos.

## Padronização do nome dos diretórios do banco de questões
Quando você cria um banco de questões por meio do pacote [EDM](https://github.com/ivanalaman/EDM), ocorre uma padronização na formação do diretório e subdiretórios que ficam organizados da seguinte forma:


![exes_br](https://github.com/ivanalaman/questionbankEDM/blob/master/images/exes_br.jpg)

É importante que esta padronização seja mantida.

## Padronizando o nome dos arquivos
Para que o seu banco de questões seja compartilhado com outros usuários, é necessário que haja uma padronização no nome dos arquivos. Esta padronização é importante, pois permitirá ao usuário indentificar a fonte da questão elaborada. Abaixo, seguem algumas imagens de sugestões de como os arquivos devem ser nomeados.

Caso a sua questão seja extraída de um livro, com capítulo e seção, então uma sugestão seria:

![ex1](https://github.com/ivanalaman/questionbankEDM/blob/master/images/ex1_br.jpg)

Se o livro não tiver seção, apenas capítulo, então o nome do arquivo pode ter o seguinte formato:

![ex2](https://github.com/ivanalaman/questionbankEDM/blob/master/images/ex2_br.jpg)

Caso o livro tenha mais de um autor, então:

![ex3](https://github.com/ivanalaman/questionbankEDM/blob/master/images/ex3_br.jpg)

Se a questão for extraída de um simulado ou algo do gênero, então a sugestão seria:

![ex4](https://github.com/ivanalaman/questionbankEDM/blob/master/images/ex4_br.jpg)

Se a questão elaborada for de autoria própria, então teríamos:

![ex5](https://github.com/ivanalaman/questionbankEDM/blob/master/images/ex5_br.jpg)

## Formando o banco de questões
Quando você cria um banco de questões por meio do aplicativo ([EDM](https://github.com/ivanalaman/EDM)), este é gravado dentro da pasta padrão criada pelo software [R](https://www.r-project.org/) ao instalar um pacote externo pela primeira vez. Se você não lembra ou não sabe onde está pasta, digite no console do [R](https://www.r-project.org/) o comando `.libPaths()`. No sistema operacional Windows por exemplo, geralmente a pasta é criada em **C:\Usuários\Seunome\Documentos\R\win-library\4.0\EDM\questionbank\país\seubanco**. 

Para começar a formar seu banco de questões, copie a pasta criada no diretório padrão do [R](https://www.r-project.org/), conforme já dito no parágrafo anterior, para outro diretório. Este procedimento é importante pois resguardará seu banco de questões contra qualquer __bug__ que por ventura o software possa apresentar. Como sugestão, crie uma pasta no seu diretório de trabalho chamada __banco_de_questao__ e dentro dela cole a pasta copiada (seu banco de questão). Ainda, dentro da pasta __banco_de_questao__ crie um arquivo chamado __DESCRIPTION.md__ conforme imagem abaixo.

![descrbr](https://github.com/ivanalaman/questionbankEDM/blob/master/images/descr_br.jpg)

Os passos anteriores irá manter seu banco de questões organizado e bem documentado. Toda vez que você fizer uma alteração no seu banco de questões, mude a numeração do item __Version__ no arquivo __DESCRIPTION.md__.

### Fluxo de trabalho
Com o banco de questões criado no seu diretório de trabalho, é hora de começar a adicionar questões. O formato de questões segue o padrão do pacote [exams](https://cran.r-project.org/web/packages/exams/index.html). Se você tem familiariade com o programa [LaTeX](https://www.latex-project.org/) ou [markdown](https://daringfireball.net/projects/markdown/), então consulte o site oficial do pacote [exams](https://cran.r-project.org/web/packages/exams/index.html) no seguinte link: http://www.r-exams.org/. Caso você não tenha familiaridade com nenhuma das liguagens citadas, não se preocupe, o pacote [EDM](https://github.com/ivanalaman/EDM) preparou uma interface gráfica para facilitar a programação de suas questões. Consulte a página do pacote [EDM](https://github.com/ivanalaman/EDM) e veja os diversos vídeos explicativos.

Uma vez formado o banco de questões, é hora de usá-lo utilizando o pacote [EDM](https://github.com/ivanalaman/EDM). Para isto, copie seu banco de questões na sua área de trabalho para dentro do diretório de bibliotecas criado pelo [R](https://www.r-project.org/). Perceba que você irá fazer o processo inverso daquele citado anteriormente, ou seja, copia de **C:\Usuários\Seunome\Documentos\banco_de_questao\seubanco** para **C:\Usuários\Seunome\Documentos\R\win-library\4.0\EDM\questionbank\país\seubanco**.








