# Introdução ao HTML na prática DIO
Atividades do curso de introdução ao html na prática pela DIO

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

