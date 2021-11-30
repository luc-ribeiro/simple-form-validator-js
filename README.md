<h1 align="center">
Simple Form Validator
</h1>

## 💻 Projeto
Um validador de formulário simples feito com JavaScript.
O validador irá verificar se um campo está vazio e irá retornar uma mensagem de erro abaixo do campo específico. 

<a href="https://luc-ribeiro.github.io/form-validator/">Live Preview</a>


## 🚀 Tecnologias

<div style="display: inline_block">
	<img align="center" alt="Luc-HTML" height="40" width="50" src="https://raw.githubusercontent.com/devicons/devicon/master/icons/html5/html5-original.svg">
	<img align="center" alt="Luc-CSS" height="40" width="50" src="https://raw.githubusercontent.com/devicons/devicon/master/icons/css3/css3-original.svg">
 <img align="center" alt="Luc-JS" height="40" width="50"  src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/javascript/javascript-original.svg" />
</div>

<br>

### Preview
![banner](https://github.com/luc-ribeiro/form-validator/blob/master/design/preview.gif)

## :page_facing_up: Como utilizar

Faça um clone deste repositório:

```sh
  $ git clone https://github.com/luc-ribeiro/form-validator.git
```

Para validações, inserir um `data-rules` no input que deseja validar.

```html5
 <input type="text" name="email" data-rules="required|email" />
 <input type="password" name="senha" data-rules="required|min=4" />
```
Informar se o campo é obrigatório `required` no data-rules e qual é a restrição. <br>
`email` para validar e-mails e `min` para validar a quantidade mínima de caracteres

<br>

Acesse o projeto utilizando a extensão Live Server do Visual Studio Code.


## :memo: License

Copyright © 2021 Lucas Ribeiro
