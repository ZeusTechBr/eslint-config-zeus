# ZeusTech ⚡ Configuração ESLint ⚙️

### Descrição

Projeto desenvolvido para disponibilizar a padronização da configuração do ESLint + Prettier em projetos React.js e Node.js que a ZeusTech utiliza.

---

### O que contém? 🤔

- Base da configuração padrão
- Plug-in React
- Plug-in React Hooks
- Plug-in JSX a11y
- Prettier

---

### Instalação

```npm i -D @zeustech/eslint-config eslint```

---

### React.js

```cjs
// Dentro de .eslintrc.cjs

module.exports = {
  extends: [
    '@zeustech/eslint-config/react',
  ]
}
```

---

### React.js + Next.js

```json
// Dentro de .eslintrc.json

{
  "extends": [
    "@zeustech/eslint-config/next", 
    "next/core-web-vitals"
  ]
}
```

---

### Node.js

```json
// Dentro de .eslintrc.json

{
  "extends": "@zeustech/eslint-config/node"
}
```

---

##### ⚡ Feito por ZeusTech ⚡ 