# react_typescript_02

### Instalando Projeto

Sempre lembrar de utilizar o --template typescript para que possamos utilizar typescript em nosso código.

```
npx create-react-app app --template typescript
```

Instalando o SASS:  
```
npm install --save-dev sass  
```

Instalando typescript-plugin-css-modules:  
```
npm install -D typescript-plugin-css-modules  
```

Dentro de tsconfig.json:  
```js
{
  "compilerOptions": {
    "plugins": [{ "name": "typescript-plugin-css-modules" }]
  }
}
```

Instalando uuid v4:
```
npm i uuid
```
```
npm i --save-dev @types/uuid
```

Instalando o CSS Normalize:  
```
npm install normalize.css
```
Depois instalado basta importar o normalize.css dentro do nosso index.tsx como ```import 'normalize.css';```


### Limpando Projeto

Dentro de app/src, excluir: "setupTests.ts", "reportWebVitals.ts", "logo.svg" , "App.tsx", "App.test.tsx", "App.css".  

Deixar apenas dentro de src: "index.css", "index.tsx", "react-app-env.d.ts".  

Dentro de app/public, excluir: "robots.tsx", "manifest.json", "logo512.png", "logo192.png", "favicon.ico".  

Dentro de index, remover os comentários, as funções e os imports que já não estão sendo usados.  

### Iniciando Projeto

```
npm start
```
