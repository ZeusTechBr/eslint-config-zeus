# ZeusTech ⚡ ESLint Configuration ⚙️

### Index
<ul>
  <a href="#description"><li>Description</li></a>
  <a href="#whats-included?"><li>What's included?</li></a>
  <a href="#installation"><li>Installation</li></a>
  <a href="#react.js"><li>React.js</li></a>
  <a href="#react.js-+-next.js"><li>React.js + Next.js</li></a>
  <a href="#node.js"><li>Node.js</li></a>
</ul>

---

### Description

Project developed to provide standardization of the ESLint + Prettier configuration in the React.js and Node.js projects that ZeusTech uses.

---

### What's included? 🤔

- Standard configuration base
- React plugin
- React Hooks plugin
- JSX a11y plugin
- Prettier

---

### Installation

```npm i -D @zeustech/eslint-config eslint```

---

### React.js

```cjs
// Inside .eslintrc.cjs

module.exports = {
  extends: [
    '@zeustech/eslint-config/react',
  ]
}
```

---

### React.js + Next.js

```json
// Inside .eslintrc.json

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
// Inside .eslintrc.json

{
  "extends": "@zeustech/eslint-config/node"
}
```

---

##### ⚡ Made by ZeusTech ⚡ 