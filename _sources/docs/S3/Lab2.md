---
title: "Lab2"
date: "10 de março de 2022"
author: "Margarida Madeira e Moura"
---
(Lab2)=
# Lab2

*Tema incial*: Números primos

## Objetivo funcional
Pretendemos um ficheiro com os $n$ primeiros números primos, um por linha, por ordem crescente.

## Objetivos de aprendizagem

• Desenho de programas paralelos

## Caso de estudo

Tendo uma implementação sequencial de referência para a determinação dos números primos e procedido a uma implementação paralela usando os conceitos anteriores de programação concorrente e 

tendo feito a avaliação de desempenho dessa implementação

Siga as etapas do desenho manual de programas paralelos e reveja a sua proposta de implementação paralela.


### Metodologia sugerida

Partindo da implementação sequencial de referência

1. Na *Definição do problema*, considere
   + Soluções algorítmicas possíveis
   + Zonas de maior carga (usando uma ferramenta de *profiling* geral como *gprof* ou *gcov*)
   + Estrangulamentos
2. Considere a adotação de *Decomposição*
   + Domínio
   + Funcional
3. Analise a *Comunicação*, considerando
   + Transferência de dados
   + Sincronização
   + Dependência de dados
4. No *Mapeamento*, considere
   + Granularidade
   + Aglomeração e balanceamento de carga


### A entregar

Até ao fim de dia 21 de Março, entregar pela Tutoria Eletrónica o relatório revisto.


### Cotação global (em pontos)

• qualidade do relatório: 12 pts


## Webgrafia deste exercício

<a id="1">[1]</a> [Parallel.pdf](https://tutoria.ualg.pt/2021/pluginfile.php/201772/mod_folder/content/0/3.Parallel.pdf?forcedownload=1), slide 52

<a id="2">[2]</a> "Designing and Building Parallel Programs". Ian Foster. http://www.mcs.anl.gov/~itf/dbpp/

<a id="3">[3]</a> [Introduction to Parallel Computing Tutorial](https://hpc.llnl.gov/documentation/tutorials/introduction-parallel-computing-tutorial##Designing), Blaise Barney, Livermore Computing (retired), Donald Frederick, LLNL, acedido em https://hpc.llnl.gov/documentation/tutorials/introduction-parallel-computing-tutorial a 7 de março de 2022

<a id="4">[4]</a> GNU gprof, acedido em https://sourceware.org/binutils/docs/gprof/ a 7 de março de 2022

<a id="5">[5]</a> gcov — a Test Coverage Program, acedido em https://gcc.gnu.org/onlinedocs/gcc-11.2.0/gcc/Gcov.html#Gcov a 7 de março de 2022

## Rubricas de avaliação

Qualidade do conteúdo revisto do relatório, nomeadamente:
   + descrição da metodologia
   + descrição das etapas executadas no desenho manual de um programa paralelo
   + discussão dos resultados

