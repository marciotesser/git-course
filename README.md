# Markdown Tutorial 

## Índice 

1. [Headers](#headers)

2. [Itálicos, Negritos e Negritos Itálicos](#itálicos-negritos-e-negritos-itálicos)

3. [Parágrafos com destaque](#parágrafo-com-destaque)

4. [Criação de Hyperlinks](#criação-de-hyperlinks)

5. [Criando auto-referências](#criando-auto-referências)

6. [Criando snnipets de código](#criando-snippets-de-código)

7. [Listas não ordenadas](#listas-não-ordenadas)

8. [Listas ordenadas](#listas-ordenadas)

9. [Sub-listas](#sub-listas)

10. [Figuras](#figuras)

## Headers

Sempre que escrevermos headers, devemos deixar linhas em branco entre eles. Os headers são representados pelo símbolo #.



Os headers têm 6 níveis que são representados pela quantidade de símbolos escritos. Exemplo:



# h1



## h2



### h3



#### h4



##### h5


###### h6

## Itálicos, Negritos e Negritos Itálicos



Os negritos e itálicos são representados pelo símbolo * ou _.



Uma palavra cercada por 1 asterisco em cada lado terá seu formato modificado para *itálico*.



Uma palavra cercada por 2 asteriscos em cada lado terá seu formato modificado para **negrito**.



Uma palavra cercada por 3 asteriscos em cada lado terá seu formato modificado para ***negrito/itálico***.

[Voltar ao índice](#índice)

## Parágrafo com destaque

Para escrever um parágrafo com destaque, utilizamos o símbolo >.

> Esse é um parágrafo destacado do resto do texto.
> Esse aqui também.
> e assim por diante.

Os paragráfos acima estão destacados do restante do texto escrito.


[Voltar ao índice](#índice)

## Criação de hyperlinks

A criação de hyperlinks é feita através dos símbolos [](). Onde o conteúdo dos colchetes é o texto que será exibido e o conteúdo do parênteses é o link a ser redirecionado.
Ex: [Google](https://www.google.com)

[Voltar ao índice](#índice)

## Criação de auto-referências
Para criar uma referência a capítulos do próprio Markdown, utiliza-se os símbolos de hyperlink [](). Porém, diferente de hyperlinks externos onde dentro do parênteses, acrescenta-se a url desejada, para links internos colocamos o título do capítulo desejado --- se houver espaço no nome do capítulo, substitua-o por hífen --- com o símbolo # o precedendo.
Ex: [Tutorial Markdown](#tutorial-markdown)

[Voltar ao índice](#índice)

## Criando snippets de código
Para criar snippets de código (partes de código) basta utilizar o símbolo de crase 3 vezes junto com a linguagem do snippet.



```java
public static void main(String[] args){
System.out.println("Teste de snippet");
}
```



```python
def teste(){



}
```



```javascript
function bla(){
document.getElementById("teste");
}
```



```json
{
"firstName": "John",
"lastName": "Smith",
"age": 25
}
```

[Voltar ao índice](#índice)

## Listas não-ordenadas
Para criar listas não-ordenadas, utiliza-se o símbolo - no começo da linha.
- linha 1
- linha 2
- linha 3
- linha 4

[Voltar ao índice](#índice)

## Listas ordenadas
Para criação de listas ordenadas, utiliza-se o número seguido de um ponto no começo da linha.
1. linha 1
2. linha 2
3. linha 3

[Voltar ao índice](#índice)

## Sub-listas
Para criação de sublistas utilizamos ambas a anotações explicadas acima junto com uma tabulação.
1. linha 1
- sub-item1
- sub-item2
2. linha 2
1. sub-linha2.1
2. sublinha2.2
3. linha 3



[Voltar ao índice](#índice)

Para acrescentar imagens no texto utiliza-se o símbolo ![](). Onde a exclamação indica uma figura, o conteúdo do colchetes indica o texto alternativo caso a imagem não seja carregada e entre parênteses temos o link da imagem.

![Logo Avanade](https://media-exp1.licdn.com/dms/image/C4E0BAQE9dnFKdWvFBQ/company-logo_200_200/0/1638381014729?e=2147483647&v=beta&t=ZuTeQLXy0CnJVociVFs6dCwjP7a8fTigTOqFTgtvjPU)

![Logo da Avanade local](./img/avanade.jpg)

[Voltar ao índice](#índice)