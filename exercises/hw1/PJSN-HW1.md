## Complete slack profile

![](https://github.com/pedrojsn96/if1004-DevOps/blob/master/exercises/hw1/image-profile.jpg)

## Screenshot of completed git tutorial

![](https://github.com/pedrojsn96/if1004-DevOps/blob/master/exercises/hw1/git-task0-main.png)
![](https://github.com/pedrojsn96/if1004-DevOps/blob/master/exercises/hw1/git-task0-remote.png)

## Hooks and Screencast

.git/hooks/post-commit

xdg-open https://github.com/vinicius3w/if1004-DevOps

Link do video: https://github.com/pedrojsn96/if1004-DevOps/blob/master/exercises/hw1/screen-capture.mp4 

## Concepts

### In your own words, explain the difference between continuous integration,continuous delivery, and continuous deployment.

Continuos Integration - É um método de desenvolvimento onde o desenvolvedor passa por todas as fases de elaboração de um software visando a automatização de atividades, a redução do tempo de construção de uma funcionalidade com o objetivo de identificar as falhas da aplicação rapidamente, reduzindo assim o custos com o reparo de erros.
Continuos Delivery - Persiste as modificações da aplicação em uma simulção do ambiente de produção para serem reavaliadas, utilizadas e testadas pelos usuários (teste de comportamento).
Continuos Deployment - Uso de processos automatizados para subir as modificações efetivamente para o ambiente de produção. 

### How does DevOps team model (e.g., site reliability engineer) differ than a NoOps team model (e.g. Netflix team)? What differences in architecture allow for a NoOps model?

A presença de SRE é um ponto de "paz" entre os Devs e os Ops. Um SRE é uma persona que possui uma boa habilidade com desenvolvimento, mas também consegue resolver problemas no nível operacional. No caso de NoOpns, não existe uma barreia estabelecida entre os membros do time, ou seja, aquele de desenvolve uma nova funcionalidade é responsável por coloca-la em operação e realizar o seu monitoramento. 
A arquitetura NoOps requer um gerenciamento de configuração tão bom quanto o de código e um nível avançado de automação de tarefas para implantação, monitoramento e gerenciamento.

### Explain the principle of Every Feature is an Expertiment

Essa visão experimental oferece a empresa a opção de errar em fases iniciais trazendo um feedback sobre a adesão do público com o conjunto de mudança, podendo então decidir em retirar ou não uma das funcionalidades experimentadas quando formalizar as mudanças em uma release.

### Explain the principle of Be Fast to Deploy, Slow(er) to Release

Esse princípio está muito conectado com a relação experimental que é dada a uma feature. A empresa deve está desenvolvendo e testando continuamente com estratégias para não afetar a experiência do usuário no uso da aplicação.

