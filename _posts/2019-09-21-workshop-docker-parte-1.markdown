---
layout: post
title:  "Workshop docker - Parte 1"
date:   2019-09-21 12:12:56 -0300
categories: docker
comments: true
---
Olá, recentemente falei um pouco sobre docker voltado para desenvolvedores. Sempre é um desafio ministrar seja palestras, cursos e afins, porque no final a minha ideia principal é que as pessoas que participam aprendam o máximo possível. 

Para isso você precisa treinar sua didática ao abordar o tema, não adianta sair falando termos tão técnicos se seu workshop for sobre informações básicas, por exemplo.

## Um pouco de história para contextualizar

Começando, falamos um pouco sobre infraestrutura, desde servidores físicos até containerização.

![historia-infraestrutura](https://d33wubrfki0l68.cloudfront.net/26a177ede4d7b032362289c6fccd448fc4a91174/eb693/images/docs/container_evolution.svg){:class="img-responsive"}

Abordamos que até hoje empresas ainda usam servidores físicos para hospedar suas aplicações, estruturas onde são instalados os sistemas operacionais e as aplicações são hospedadas dessa forma consumindo os recursos do host sem isolamento.

Após, falamos um pouco sobre virtualização, onde começamos a utilizar uma tecnologia chamada [hipervisor](https://pt.wikipedia.org/wiki/Hipervisor) para fazer a gestão do que chamamos máquinas virtuais. Nesse processo, nosso host tem o hipervisor instalado e através dele podemos criar e gerenciar múltiplas máquinas virtuais tendo os recursos do host isolados. Já ganhamos isolamento nessa altura do campeonato, isso possibilita maior organização das nossas aplicações, podemos escalar novas máquinas virtuais isolando seus recursos e sabendo como isso vai afetar nosso host.

E nos últimos anos, vimos o boom dos containers surgindo, a chamada containerização. Mas containers já são velhos conhecidos, empresas como Google usam essa tecnologia já faz um tempo. Como na virtualização, onde as máquinas virtuais são isoladas, os containers também usam essa estratégia, porém isso é feito através de primitivas do kernel do sistema operacional como namespaces, chroot e cgroups, com isso o nosso tão falado container é gerenciado, porém a diferença é que os containers são processos dentro do sistema operacional, isso nos dá a possibilidade de trabalhar de uma forma mais leve ainda do que na virtualização visto que um processo tem maior leveza, rapidez e elasticidade para ser iniciado, interrompido e outras operações do nosso cotidiano.

## Containers: o que são ?

Containers são processos executados pelo sistema operacional, eles proporcionam uma maneira padrão de empacotar código, configurações e depedências. Lembre-se containers não são máquinas virtuais mais leves! 

Pessoal, para não tornar massante a leitura este post para por aqui, até o próximo e obrigado por ler!

Obs.: Não deixe de comentar com suas críticas, sugestões e afins.
