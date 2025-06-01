# webPortal
Este é um projeto de portal web desenvolvida em React/Angular/JavaScript/TypeScript para treinamento de Frontend e DevOps.

Abaixo estão as instruções para configuração, execução e uso.

## Pré-requisitos

- [Node.js](https://nodejs.org/) instalado (versão 14 ou superior).
- [npm](https://www.npmjs.com/) ou [yarn](https://yarnpkg.com/) instalado.

## Instalação

1. Clone o repositório:
    ```bash
    git clone https://github.com/leoalmeida/webPortal.git
    cd webPortal
    ```

2. Instale as dependências:
    ```bash
    npm install
    # ou
    yarn install
    ```

## Uso

### Executar em ambiente de desenvolvimento

```bash
npm run dev
# ou
yarn dev
```

### Executar em ambiente de produção

1. Compile o projeto:
    ```bash
    npm run build
    # ou
    yarn build
    ```

2. Inicie o servidor:
    ```bash
    npm start
    # ou
    yarn start
    ```

## Scripts Disponíveis

- `dev`: Inicia o servidor em modo de desenvolvimento.
- `build`: Compila o projeto para produção.
- `start`: Inicia o servidor em modo de produção.

## Estrutura do Projeto

```plaintext
webPortal/
├── src/
│   ├── components/
│   ├── tests/
│   ├── App.js
│   ├── App.scss
│   └── custom.scss
├── public/
│   ├── index.html
│   ├── manifest.json
├── .dockerignore
├── .gitignore
├── Dockerfile
├── docker-compose.yml
├── eslint.config.mjs
├── package.json
├── package-lock.json
├── app.js
├── auth.js
└── README.md
```

## Contribuição

Contribuições são bem-vindas! Siga os passos abaixo:

1. Faça um fork do projeto.
2. Crie uma branch para sua feature:
    ```bash
    git checkout -b minha-feature
    ```
3. Commit suas alterações:
    ```bash
    git commit -m "Adiciona minha feature"
    ```
4. Envie para o repositório remoto:
    ```bash
    git push origin minha-feature
    ```
5. Abra um Pull Request.
