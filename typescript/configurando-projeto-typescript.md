# Configurando projeto TypeScript

**Instalação do pacote**

```bash
yarn add typescript --dev
```

**Configuração do tsconfig.json**

```bash
yarn tsc --init
```

Sugestão de configuração do arquivo tsconfig.json

```json
{
  "outDir": "./dist"
}
```

**Configurando ambiente desenvolvimento**

Configurando um equivalente do **nodemon**

```bash
yarn add -D ts-node-dev
```

Editar o package.json

```json
"scripts": {
  "dev:server": "ts-node-dev --respawn --transpile-only src/index.ts"
},
```

**--transpile-only**: apenas realiza a conversão do typescript sem verificação de erros