## PJSN - HW6

Esse paper trás um estudo como ênfase a fase de build de aplicações em Java e C++. Ele coloca em foco
os problemas decorrentes dessa fase, como por exemplo: erros na compilação, erros de dependências. 

O paper apresenta três questões para orientar o estudo: 
1 - How often do builds fail? (Frequência das falhas)
2 - Why do builds fail? (O porque)
3 - How long does it take fix broken builds? (E quanto tempo para resolver)

Entendi que eles fizeram uso de métricas para identificar os principais tipos de erros, e onde eles
acontencem para desenvolver ferramentes para dar suporte ao desenvolvedor na correção dessas falhas
de uma forma mais fácil e rápida. 
Eles compreendem que a falha faz parte do processo de build e querem atuar para diminuir o tempo que
os desenvolvedores passam para corriguir-las fazendo uso de ferramentas que auxiliam no "debug", por
examplo: fazer uso de IDE's diminui a quantidade de erros. Foi observado que aplicações em Java tem 
menos erros que aplicações em C++. O erro mais frequente é o de dependências.
