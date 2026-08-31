# Módulo 01: O que é HTML?

O **HTML** (*HyperText Markup Language* ou Linguagem de Marcação de Hipertexto) é a base de todas as páginas da internet. Ele não é uma linguagem de programação (não possui lógica ou cálculos), mas sim uma linguagem de marcação que define o esqueleto e a estrutura do conteúdo.

## Estrutura Básica de um Documento HTML

Todo arquivo HTML moderno segue esta estrutura fundamental:

```html
<!DOCTYPE html>
<html lang="pt-BR">
  <head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Minha Primeira Página</title>
  </head>
  <body>
    <h1>Olá, Mundo!</h1>
    <p>Este é o meu primeiro documento HTML.</p>
  </body>
</html>

```
## O que significa cada parte?
`<!DOCTYPE html>`: Informa ao navegador que o documento usa HTML5.

`<html lang="pt-BR">`: Elemento raiz que envolve todo o documento e define o idioma.

`<head>`: Contém configurações e metadados que não aparecem visualmente na página.

`<body>`: Contém todo o conteúdo visível aos usuários (textos, imagens, botões, etc.).
