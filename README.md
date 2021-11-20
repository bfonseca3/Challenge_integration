## Alterar integração
Alterar integração local com pequeno server Node remoto. Subir em um repositorio, alterações de integração.

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

# Para rodar o Build:
 ```bash
yarn build
yarn start
```

Open [http://localhost:3000](http://localhost:3000) with your browser to see the result.
