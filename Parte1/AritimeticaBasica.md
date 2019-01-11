
# Aritimética simples

Como de costume vamos começar com o básico da linguagem.
Abaixo temos exemplos de soma, subtração, multiplicação e divisão respectivamente

```` haskell
2 + 2
2 - 3
2 * 3
3.0 / 2.0
````

isso tudo parece bem intuitivo mas existem questões a serem ressaltadas.  
Primeiro, é possível que as mesmas operações acima sejam feitas da seguinte maneira:

```` haskell
(+) 2 2
(-) 2 3
(*) 2 3
(/) 3.0 2.0
````

Algo peculiar para quem não está acostumado mas bastante útil para a redibilidade e legibilidade do código.  

Repare que a operação de divisão (/) foi feita usando números do tipo float, isso porque em Haskell a divisão utilizando este operador é feita somente utilizando núemros do tipo float.  

Por exemplo, as operaççoes abaixo emitirá erros de compilação:

```` haskell
3 / 2
50 / 2
````
