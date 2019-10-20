---
layout: post
title:  "Talk sobre 12 factor app"
date:   2019-10-20 12:34:56 -0300
categories: software
comments: true
---
Duas semanas atrás fiz uma talk no GBG Curitiba sobre 12 factor app. Esse assunto é de extrema importância principalmente quando estamos criando apps cloud native.
Mas, não somente nesse caso, com 12 factor app você consegue criar apps com elasticidade, desacoplamento e desenvolvimento com muita interação entre os times na sua empresa.

## GBG Curitiba

O GBG Curitiba "é uma comunidade que reúne empreendedores de mentalidade semelhante para construir relacionamentos, aprender uns com os outros e inspirar o sucesso dos seus negócios."

Todas as segundas temos o evento que não se resume somente à talks de tecnologia. Temos talks sobre business, inglês e tudo relacionado com o ecossistema vibrante da comunidade em Curitiba.

Para mais informações acesse o site oficial do [GBG Curitiba](https://www.gbgcuritiba.org/).

## Introdução: The Twelve-Factor App

Comecei falando sobre o que é 12 factor app, que é uma metodologia com 12 práticas focadas em te proporcionar a criação de software como serviço de maneira fácil, escalável, portável e pronta para implantação contínua.

Essa metologia foi criada por pessoas envolvidas e com experiência em centenas de projetos cloud native dentro da plataforma Heroku. Os padrões promovidos nos 12 fatores existem com a finalidade não só de criação do software mas também para amadurecimento das aplicações ao longo do tempo, contribuição das pessoas do time como um todo e foi inspirado nos livros de Martin Fowler, [Padrões de Arquitetura de Aplicações Enterprise](https://books.google.com.br/books/about/Patterns_of_enterprise_application_archi.html?id=FyWZt5DdvFkC&redir_esc=y&hl=pt-BR) e [Refatorando](https://books.google.com.br/books/about/Refactoring.html?id=1MsETFPD3I0C&redir_esc=y).

Vamos hoje listar os 12 fatores e nos próximos posts sobre esse tema falarei sobre cada um mostrando exemplos práticos do nosso cotidiano com códigos para ilustrar as situações.

### Os Doze Fatores


**1  Base de Código** <br />
    Uma base de código com rastreamento utilizando controle de revisão, muitos deploys

**2  Dependências** <br />
    Declare e isole as dependências

**3  Configurações** <br />
    Armazene as configurações no ambiente

**4  Serviços de Apoio** <br />
    Trate os serviços de apoio, como recursos ligados

**5  Build, release, run** <br />
    Separe estritamente os builds e execute em estágios

**6  Processos** <br />
    Execute a aplicação como um ou mais processos que não armazenam estado

**7  Vínculo de porta** <br />
    Exporte serviços por ligação de porta

**8  Concorrência** <br />
    Dimensione por um modelo de processo

**9  Descartabilidade** <br />
    Maximizar a robustez com inicialização e desligamento rápido

**10  Dev/prod semelhantes** <br />
    Mantenha o desenvolvimento, teste, produção o mais semelhante possível

**11  Logs** <br />
    Trate logs como fluxo de eventos

**12  Processos de Admin** <br />
    Executar tarefas de administração/gerenciamento como processos pontuais

Caso, você tenha interesse pelo tema no site do projeto tem muita informação [12 factor app](https://12factor.net/pt_br/)

E aqui tem os slides (que prometi na talk subir em algum lugar hehe) [Slides talk 12 factor app - GBG Curitiba](https://www.slideshare.net/thaiseestevam/12-factor-app-184450329)

Obs.: Não deixe de comentar com suas críticas, sugestões e afins.

E até a próxima.