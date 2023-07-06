Simples mascara para CPF e CNPJ utilizando JavaScript puro!  

Esse script aplica uma mascara nos seguintes formatos:
- CPF: 999.999.999-99
- CNPJ: 99.999.999/9999-99

Para aplicar a mascara adicione o script a sua página.
```html
<script type="text/javascript" src="mask-cpf-cnpj-pure-js.js"></script>
```

Selecione os campos, buscando pela classe, no qual deseja aplicar a mascara.
```js
let inputCpfCnpj = document.getElementsByClassName('mask-cpf-cnpj')
```

Por fim, execute a função ```skCpfCnpjPureJs()``` passando por parâmetro os elementos que foram selecionados anteriormente.
```js
maskCpfCnpjPureJs(inputCpfCnpj);
```

Você também pode passar um segundo parâmentro para informar que deseja aplicar a mascara somente para CPF ou CNPJ.
```js
maskCpfCnpjPureJs(inputCpf, 'cpf');
maskCpfCnpjPureJs(inputCnpj, 'cnpj');
```

Caso não seja especificado esse parâmetro, o campo vai conter as duas mascaras ao mesmo tempo.  
O exemplo completo você pode ver no arquivo ```index.html```
