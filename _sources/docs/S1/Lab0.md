(Lab0)=
# Lab0

## Objetivos de aprendizagem

Com este guião, pretende-se 
+ rever a programação concorrente;
+ introduzir o desenho de soluções paralelas;
+ sensibilizar para a necessidade de usar métricas de desempenho.


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

## Etapas

Estude o caso, seguindo as seguintes etapas:

1. Defina o caso de estudo.
1. Crie os casos de teste.
1. Desenhe/escolha um algoritmo para o presente caso de estudo. Para cada algoritmo:
    1. identifique as vantagens
    1. identifique limitações.
1. Implemente num programa sequencial uma solução para este caso.
    1. Escolha os valores com que vai testar a sua solução, justificando a escolha.
    1. Meça o desempenho da sua solução, e avalie esse desempenho.
1. Para uma implementação concorrente:
    1. Identifique constrangimentos
    1. Proponha uma alternativa para obviar esses constrangimentos.
