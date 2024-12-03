# Introdução-ao-HTML-na-prática-DIO
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
<img src = "imagens md/meu primeiro título.png">
É possível estilizar esse título dentro do próprio html. Por exemplo, você pode deixar em itálico:

```
<html>
  <head>
  </head>
  <body>
      <h1><i>Meu primeiro título em itálico</i></h1>
  </body>
</html>


