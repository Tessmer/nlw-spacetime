# Projeto Cápsula do Tempo

Este é o repositório oficial do projeto Cápsula do Tempo desenvolvido durante a Next Level Week SpaceTime (NLW) promovida pela Rocketseat. Trata-se de uma aplicação web e mobile, juntamente com uma API, que permite aos usuários criar e compartilhar mensagens, fotos e vídeos para serem armazenados e visualizados no futuro.

## :rocket: Tecnologias Utilizadas

- [NodeJS](https://nodejs.org/en)
- [TypeScript](https://www.typescriptlang.org/docs/)
- [Prisma](https://www.prisma.io/docs)
- [Fastify](https://www.fastify.io/)
- [NextJS](https://nextjs.org/docs)
- [React](https://react.dev/learn)
- [TailwindCSS](https://tailwindcss.com/docs/installation)
- [SQLite](https://sqlite.org/docs.html)

## :wrench: Funcionalidades

- Autenticação de usuários
- Criação de postagens
- Upload de imagens
- Armazenamento de dados no banco de dados
- Visualização de postagens existentes

## :scroll: Pré-requisitos

Antes de executar o projeto localmente, certifique-se de ter as seguintes dependências instaladas:

- Node.js (versão 18 ou superior)
- Gerenciador de pacotes npm ou yarn

## :paperclip: Instalação

1. :clipboard: Clone este repositório para o seu ambiente de desenvolvimento local:

```powershell
git clone https://github.com/Tessmer/nlw-spacetime.git
```

2. :open_file_folder: Navegue para o diretório raiz do projeto:

```powershell
cd nlw_spacetime
```

3. :clipboard: Instale as dependências necessárias executando o comando:

```powershell
npm install
```

ou

```powershell
yarn install
```

4. :hammer: Configuração do Banco de Dados:

- Execute as migrações do banco de dados com o seguinte comando:

  ```powershell
  npx prisma migrate dev
  ```

- (Opcional) Execute as seeds para criar dados iniciais no banco de dados:

  ```powershell
  npx prisma db seed --preview-feature
  ```

5. Inicie o servidor de desenvolvimento:

```powershell
npm run dev
```

6. Navegue para `http://localhost:3000` para visualizar a aplicação no seu navegador.
