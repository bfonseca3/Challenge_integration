## O Projeto
Pequeno projeto que consiste em um CRUD de um empreendimento imobiliario.

## Estrutura de Dados do empreendimento
A Estrutura de dados da entidade empreendimento, pode ser encontrado no arquivo na raiz do projeto: enterprises-server.json

## Criar uma pequeno Server NodeJs + MongoDB, para aplicação desse repositorio.
- [ ] Utilizar Typescript
- [ ] Listar Empreendimentos
- [ ] Criar Empreendimento
- [ ] Editar Empreendimento
- [ ] Deletar Empreendimento
- [ ] Utilizar MongoDB para salvar e estruturar dados
- [ ] Alterar integração do frontend desse repositório
- [ ] Hospedar gratuitamente em alguma plataforma: Heroku, netlify, aws, etc.
- [ ] Subir no github, ou bitbucket e afins..

## Alterar integração
Alterar integração local, para um pequeno server Node remoto. Subir em um repositorio alterações de integração.

## Getting Started

Para rodar o Projeto:

```bash
npm run dev
# or
yarn dev
```

## Para rodar a Fake api: 
  - yarn add [json-server](https://www.npmjs.com/package/json-server)
  - adicionam o seguinte script no package.json:
    - "server": "json-server --watch enterprises-server.json --port 3001"
  - Rodar server: yarn server
  - estará rodando em http://localhost:3001/

## Para rodar o Build:
 ```bash
yarn build
yarn start
```

Open [http://localhost:3000](http://localhost:3000) with your browser to see the result.
