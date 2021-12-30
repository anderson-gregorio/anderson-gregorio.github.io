# Importação de Módulos Node

**Utilizando código JavaScript (sem nenhuma transpilação BABEL ou TYPESCRIPT)**

Para utilizar o ESM é preciso adicionar a seguinte chave ao **package.json**

```json
{
  ...
  "type": "module"
}
```

## CommonJS

Exportando o módulo:

```js
function foo () {
  ...
}

module.exports = foo;
```

Importando o módulo:

```js
const foo = require('./foo');
```

## ESM (ECMAScript Modules)

Exportando o módulo:

```js
export function foo () {
  ....
}
```

Importando o módulo:

*Deve se utilizar a extensão do arquivo*

```js
import foo from '/foo.js';
```

## Link Referência

* [https://developer.mozilla.org/pt-BR/docs/Web/JavaScript/Reference/Statements/export](https://developer.mozilla.org/pt-BR/docs/Web/JavaScript/Reference/Statements/export)
* [https://www.youtube.com/watch?v=0YRyi1BDWyw](https://www.youtube.com/watch?v=0YRyi1BDWyw)
* [https://stackoverflow.com/questions/62488898/node-js-syntaxerror-cannot-use-import-statement-outside-a-module](https://stackoverflow.com/questions/62488898/node-js-syntaxerror-cannot-use-import-statement-outside-a-module)

