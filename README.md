# Introdução ao HTML na prática DIO
Atividades do curso de introdução ao html na prática pela DIO e pontos importantes das aulas.

![Static Badge](https://img.shields.io/badge/Conhe%C3%A7a%20mais%20sobre%20o%20HTML%20-html?style=for-the-badge&logo=html5&logoColor=white&logoSize=auto&color=blue)
[![LinkedIn](https://img.shields.io/badge/LinkedIn-0077B5?style=for-the-badge&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/isadora-mendes-3b8605336/)

## Composição de um HTML
Composto por uma cabeça (head) e por um corpo (body)
 ```
 Exemplo de início de HTML
 <html>
    <head>
    <title>Meu primeiro site</title></head>
    <body></body>
</html>
```
OBS: se você marcar ! no início do seu software de código, ele escreverá uma estrutura básica de HTML completa para desenvolver:
```
!
```
Após apertar enter, vai sair:
```
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Document</title>
</head>
<body>
    
</body>
</html>
```

## Tags
O HTML possui tags (exemplo: ``<h1>``)
A maioria das tags possuem um início ``<i>`` e um fechamento ``</i>``.

Uma tag comum para o body (a parte que será visível para o usuário do site) é a h1 (tag de título principal):
```
<html>
    <head>
    </head>
    <body>
        <h1>Meu primeiro título</h1>
    </body>
</html>
```
<img src = "imagens md/meu primeiro título1.png">
É possível estilizar esse título dentro do próprio html. Por exemplo, você pode deixar em itálico:

```
<html>
  <head>
  </head>
  <body>
      <h1><i>Meu primeiro título em itálico</i></h1>
  </body>
</html>

```
<img src = "imagens md/meu primeiro título em itálico.png">

Além disso, também é possível deixar esse título em negrito:

```
<html>
 <head></head>
 <body>
     <h1><strong>Meu primeiro título em negrito</strong></h1>
 </body>
</html>

```
Talvez você tenha percebido que eu usei a tag strong e a tag i dentro da tag h1, assim juntou os atributos. Isso significa que você pode juntar as 3 tags também, tornando o título em itálico e em negrito:

```
<html>
 <head></head>
 <body>
    <h1><strong><i>Meu primeiro título em negrito e itálico</i></strong></h1>
 </body>
</html>

```
<img src ="imagens md/meu primeiro título em negrito e itálico.png">

[![Static Badge](https://img.shields.io/badge/Conhe%C3%A7a%20as%20principais%20tags%20-%20HTML?style=for-the-badge&logo=html5&logoColor=white&logoSize=auto&color=blue)
](https://www.brasilcode.com.br/tags-html-conhecas-as-principais-e-mais-usadas/)




## Atributos
Os atributos no HTML dão características específicas. Um exemplo seria a tag input com o atributo type. A tag input é uma tag de entrada, ou seja, alguma coisa será inserida, enquanto o atributo type vai definir o que vai ser inserido:
```
<html lang="pt-BR">
<head>
    <title>Introdução ao HTML</title>
</head>
<body>
   <input type="text">
</body>
</html>
```
<img src ="imagens md/caixa de entrada de texto.png">

Nesse caso, o input é uma caixa de entrada do tipo "text", ou seja, vai ser inserido um texto.
Esse mesmo input poderia ter um novo type, por exemplo, o number. Nesse caso, apenas números seriam inseridos:
```
<html lang="pt-BR">
<head>
    <title>Introdução ao HTML</title>
</head>
<body>
   <input type="number">
</body>
</html>
```
<img src ="imagens md/input number.png">

## Tags iniciais de Textos
As tags iniciais são a de parágrafo (p), a de destaque (mark), a de citação (blockquote) e as de subscrição (sub) e sobrescrição (sup).
```
<html lang="pt-BR">
<head>
    <title>Introdução ao HTML</title>
</head>
<body>
    <p>Aqui nós temos uma tag de parágrafo, ou seja, um texto longo que tem que ser quebrado. Eu não sei o que eu posso escrever aqui para deixar de exemplo, então eu estou só enrolando para ser o suficiente.</p>
</body>
</html>
```
<img src ="imagens md/tag parágrafo.png">

```
<html lang="pt-BR">
<head>
    <title>Introdução ao HTML</title>
</head>
<body>
    <mark>Exemplo para destaque</mark>
</body>
</html>
```
<img src ="imagens md/exemplo tag mark.png">

```
<html lang="pt-BR">
<head>
    <title>Introdução ao HTML</title>
</head>
<body>
    <p>Exemplo abaixo para citação:</p>
    <blockquote>Você está lendo um exemplo da tag citação.</blockquote>
</body>
</html>
```
<img src ="imagens md/tag citação.png">

```
<html lang="pt-BR">
<head>
    <title>Introdução ao HTML</title>
</head>
<body>
    <p>Exemplo para sobrescrição<sup>Esse é um exemplo de sobrescrição</sup></p>
</body>
</html>
```
<img src ="imagens md/sobrescrição.png">

```
<html lang="pt-BR">
<head>
    <title>Introdução ao HTML</title>
</head>
<body>
    <p>Exemplo para sobrescrição<sub>Esse é um exemplo de subscrição</sub></p>
</body>
</html>
```
<img src ="imagens md/subscrição.png">

## Listas Ordenadas e Não-Ordenadas
O HTML permite que você coloque listas com uma ordem de enumeração (ol) e listas sem ordem de enumeração (ul), além de permitir que você coloque listas (li) dentro de outras listas.

```
<html lang="pt-BR">
<head>
    <title>Introdução ao HTML</title>
</head>
<body>
    <p>Exemplo de lista ordenada:</p>
    <ol>
       <li>Item ordenado 1</li>
       <li>Item ordenado 2
            <ol>
               <li>Item 1 dentro de uma lista ordenada dentro de outra lista ordenada</li>
                <li>Item 2 dentro de uma lista ordenada dentro de outra lista ordenada</li>
            </ol>
        </li>
    </ol>
</body>
</html>
```
<img src ="imagens md/ol.png">

```
<html lang="pt-BR">
<head>
    <title>Introdução ao HTML</title>
</head>
<body>

    <p>Exemplo de lista não-ordenada:</p>
    <ul>
       <li>Item não-ordenado 1</li>
       <li>Item não-ordenado 2
            <ul>
               <li>Item 1 dentro de uma lista não-ordenada dentro de outra lista não-ordenada</li>
                <li>Item 2 dentro de uma lista não-ordenada dentro de outra lista não-ordenada</li>
            </ul>
        </li>
    </ul>
</body>
</html>
```
<img src ="imagens md/ul.png">

## Links no seu site
Você pode adicionar links dentro do seu site para que as pessoas possam navegar na internet. Você pode fazer isso usando a tag ancora (a).
```
<html lang="pt-BR">
<head>
    <title>Introdução ao HTML</title>
</head>
<body>
    <a href="https://www.w3schools.com/html/default.asp">Conheça mais sobre HTML no W3SCHOOLS</a>
</body>
</html>
```


No entanto, apenas dessa forma o link vai ser aberto na própria página. Caso você queira que abra em uma nova página, você usa um atributo chamado target e escolhendo a opção blank.

```
<html lang="pt-BR">
<head>
    <title>Introdução ao HTML</title>
</head>
<body>
    <a href="https://www.w3schools.com/html/default.asp" target="_blank">Conheça mais sobre HTML no W3SCHOOLS</a>
</body>
</html>
```
