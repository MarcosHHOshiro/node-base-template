# Node Base Template

Este é um template básico para projetos em Node.js utilizando TypeScript, Fastify e Prisma.

## 📦 Tecnologias Utilizadas

- **Node.js**
- **TypeScript**
- **Fastify**
- **Prisma ORM**
- **Zod**
- **ESLint (Rocketseat Config)**
- **TSX**
- **TSUP**

## 🚀 Instalação e Uso

### 1️⃣ Clonar o repositório
```sh
 git clone https://github.com/seu-usuario/seu-repositorio.git
 cd seu-repositorio
```

### 2️⃣ Instalar as dependências
```sh
 npm install
```

### 3️⃣ Configurar as variáveis de ambiente
Crie um arquivo `.env` e adicione as variáveis necessárias, como a URL do banco de dados para o Prisma.

### 4️⃣ Rodar o servidor em desenvolvimento
```sh
 npm run start:dev
```

### 5️⃣ Gerar a build para produção
```sh
 npm run build
```

### 6️⃣ Executar em produção
```sh
 npm run start
```

## 📂 Estrutura do Projeto
```
📦 projeto
 ┣ 📂 src
 ┃ ┣ 📜 server.ts  # Servidor Fastify
 ┃ ┗ 📜 ... outros arquivos
 ┣ 📜 .eslintrc    # Configuração do ESLint
 ┣ 📜 package.json # Dependências e scripts
 ┗ 📜 tsconfig.json # Configuração do TypeScript
```

## 📝 Licença
Este projeto está sob a licença ISC.

