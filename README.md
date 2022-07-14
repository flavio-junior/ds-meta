# Ferramentas de desenvovimento

- Node.js: `node-v16.15.1-x64.msi`
- STS 
- VS Code
  - `IntelliCode`
  - `ESLint`
  - `JSX HTML <tags/>`

# Configurações

![DevSuperior no Instagram](https://raw.githubusercontent.com/devsuperior/bds-assets/main/sds/pastas-dsmeta.png)

> Para os passos a seguir, acessar a pasta do projeto e abrir o terminal

***Criar front end***
```
  yarn create vite frontend --template react-ts
```

***Baixar dependências do projeto***
```
  yarn
```

***Executarr projeto***
```
  yarn dev
```

***Parar projeto***
```
ctrl + c
```

# Configurações do Spring Initializr

Acessar o site do [Spring Initializr](https://start.spring.io/)

* Project: `Maven Project`
* Language: `Java`
* Spring Boot: `2.7.1`

***Project metadata:***
* Group: `com.devsuperior `
* Artifact: ` dsmeta `
* Name: ` dsmeta `
* Description: ` Projeto da Semana Spring React DevSuperior `
* Package name: ` com.devsuperior.dsmeta `
* Packaging: ` Jar `
* Java: ` 17 `

***Dependências:***
 - `Web`
 - `JPA`
 - `H2`
 - `Security`

> Ao clicar em `GENERETE ` que baixar o projeto renomear o projeto com o nome `backend` e mover para a pasta dsmeta dentro da pasta backend

# Abrir projeto no SpringToolSuite4


# Datepicker

**Dependência**
```
  yarn add react-datepicker@4.8.0 @types/react-datepicker@4.4.2
```

***Imports:***
```javascript
  import DatePicker from "react-datepicker";
  import "react-datepicker/dist/react-datepicker.css";
```

***Capturando a data:***
```javascript
<DatePicker
    selected={new Date()}
    onChange={(date: Date) => {}}
    className="dsmeta-form-control"
    dateFormat="dd/MM/yyyy"
/>
```

***Documentação:***
 - [Datepicker](https://github.com/Hacker0x01/react-datepicker)
