---
title: "Lab1"
date: "2 de março de 2021"
author: "Margarida Madeira e Moura"
---
(Lab1)=
# Lab1

*Tema incial*: Números primos

## Objetivo funcional
Pretendemos um ficheiro com os $n$ primeiros números primos, um por linha, por ordem crescente.

## Objetivos de aprendizagem

• Ensaio de abordagens de paralelização 
• Avaliação de desempenho e documentação da paralelização
• Familiarização com as abordagens de implementação sequencial e paralelas.

## Caso de estudo

Os números primos são interessantes, em parte pela suas aplicações criptográficas.
No presente caso, vamos usar o cálculo ou determinação de números primos para exercitar a programação concorrente.
Pretendemos um ficheiro com os $n$ primeiros números primos, um por linha, por ordem crescente.

### Detalhes de implementação

O programa deve receber um número $n$ e uma string `nome-ficheiro` e escrever no ficheiro `nome-ficheiro` os primeiros $n$ números primos, um número por linha, por ordem crescente.

### Exemplo A

*Input*
```
5 p5.txt
```

*Output*
O ficheiro `p5.txt` contém:
```
2
3
5
7
11
```


### Casos a estudar

0 - Implementação sequencial
1 - Implementação paralela usando tarefas


### A entregar
- Relatório e código 
- Uma semana (até ao início da aula seguinte)

### Cotação global (em pontos)

• casos sequencial e paralelo: 5 pts
• qualidade do relatório: 5 pts


## Webgrafia inicial

<a id="1">[1]</a> https://en.wikipedia.org/wiki/Prime_number

<a id="2">[2]</a> https://mathworld.wolfram.com/PrimeNumber.html

<a id="3">[3]</a> https://sapientia.ualg.pt/handle/10400.1/14941


## Rubicas de avaliação

Qualidade do relatório

 - Forma: estrutura adequada, correção (ortográfica e gramatical) da linguagem, referências no texto, bibliografia, figuras
 - Conteúdo
    descrição da metodologia
    descrição da estratégia de implementação
    avaliação de desempenho - tempo de execução, aceleração, eficiência, escalabilidade ou rácio RC
    discussão dos resultados

