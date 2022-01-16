# Configurando o Jest no projeto Node

**Instalação do pacote**

```bash
yarn add jest -D
```

**Configuração do Jest**

```bash
yarn jest --init
```

**Projeto com TypeScript"**

```bash
yarn add -D ts-jest @types/jest
```

Adicionar a seguinte configuração no arquivo jest.config.[jt]s

```javascript
{
  ...
  preset: 'ts-jest'
}
```


## Link Referência

* [https://jestjs.io/pt-BR/docs/getting-started](https://jestjs.io/pt-BR/docs/getting-started)
* [https://sharklabs.com.br/testes-unitarios-com-nodejs-jest-typescript/](https://sharklabs.com.br/testes-unitarios-com-nodejs-jest-typescript/)