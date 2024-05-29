<h1 align="center">
Simple Form Validator
</h1>

<div align="right">
  Clique <a href="https://github.com/luc-ribeiro/simple-form-validator-js/blob/master/README.md">aqui</a> para ver a versão em Português.
</div>

## 💻 Projeto
A simple form validator made with JavaScript.
The validator will check if a field is empty and will return an error message below the specific field.

<a href="https://luc-ribeiro.github.io/form-validator/">Live Preview</a>


## 🚀 Technologies

<div style="display: inline_block">
	<img align="center" alt="Luc-HTML" height="40" width="50" src="https://raw.githubusercontent.com/devicons/devicon/master/icons/html5/html5-original.svg">
	<img align="center" alt="Luc-CSS" height="40" width="50" src="https://raw.githubusercontent.com/devicons/devicon/master/icons/css3/css3-original.svg">
 <img align="center" alt="Luc-JS" height="40" width="50"  src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/javascript/javascript-original.svg" />
</div>

<br>

### Preview
![banner](https://github.com/luc-ribeiro/form-validator/blob/master/design/preview.gif)

## :page_facing_up: How to use

Clone this repository:

```sh
  $ git clone https://github.com/luc-ribeiro/form-validator-js.git
```

For validations, insert a `data-rules` attribute in the input you want to validate.

```html5
 <input type="text" name="email" data-rules="required|email" />
 <input type="password" name="senha" data-rules="required|min=4" />
```
Specify if the field is required `required` in the data-rules and what the restriction is. <br>
Use `email` to validate emails and `min` to validate the minimum number of characters.

<br>

Access the project using the Live Server extension of Visual Studio Code.


## :memo: License

MIT © 2021 Lucas Ribeiro
