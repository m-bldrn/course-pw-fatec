---
marp: true

author: "Eduardo Cruz Araujo"
title: "Programação Web"
description: "Disciplina de Programação Web."

theme: "default"
class: "invert"

footer: "Eduardo Cruz Araujo | Programação Web | Fatec | 2025.02"

paginate: "true"

---

# Programação Web :mortar_board:

*Hands on 'Hello World'* 

---

> As aulas práticas de desenvolvem efetivamente em sala de aula. O conteúdo aqui não passa de um *checklist*. O conteúdo/código produzido será disponibilizado em uma branch específica da aula no repositório [https://github.com/edcaraujo/course-pw-fatec-20252-project](https://github.com/edcaraujo/course-pw-fatec-20252-project)]

---

## Requisitos

- Instalar o [Node.js](https://nodejs.org/en/download) versão `22.18.0 (LTS)`
    - https://nodejs.org/en/download
    

---

## Repositório

- Baixar repositório
    - [https://github.com/edcaraujo/course-pw-fatec-20252-project](https://github.com/edcaraujo/course-pw-fatec-20252-project)]
    - Branch `main`

---

## IDE

- Abrir projeto no [Visual Studio Code](https://code.visualstudio.com/)

---

## Inicializar configurações do projeto (*package.json*) 

```
npm init -y
```

---

## Instalar dependências do projeto

✨ Dependências de `produção`
```
npm install express dotenv
```

---

## Instalar dependências do projeto

🧪 Dependências de `desenvolvimento`
```
npm install -D typescript nodemon ts-node @types/express @types/dotenv
```

---

## Inicializar configurações do projeto (*tsconfig.json*) 

```
npx tsc --init
```

---

## Configurar projeto (*tsconfig.json*) 

Editar arquivo `tsconfig.json`
```
"esModuleInterop": true,
"verbatimModuleSyntax": false,
"rootDir": "./src",
"outDir": "./dist",
```

---

## Configurar projeto (*package.json*)

Editar arquivo `package.json`
```
"scripts": {
    "dev": "nodemon --exec ts-node src/server.ts",
    "build": "tsc",
    "test": "echo \"Error: no test specified\" && exit 1"
},
```
---

## Configurar projeto (*.env*)

Criar e editar arquivo `.env`

```
PORT=3000
```

---

## Estrutura

Criar estrutura básica do projeto

```
src/
  |__ routers/
  |__ controllers/
  |__ repositórios/
  |__ models/
  |__ app.js
  |__ server.js
  |__ .env
  |__ .env.example
```

---

# Obrigado :metal:

---

## Eduardo Cruz Araujo

- E-mail: [eduardo.araujo28@fatec.sp.gov.br](eduardo.araujo28@fatec.sp.gov.br)
- Instagram: [edcaraujo](https://www.linkedin.com/in/edcaraujo/)
- Linkedin: [edcaraujo](https://www.instagram.com/)
- Github: [edcaraujo](https://github.com/edcaraujo)