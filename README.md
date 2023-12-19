# Projeto Server

## Descrição
Este é um projeto servidor (server) com a finalidade de fornecer uma base para construção de uma aplicação. O servidor é construído utilizando Node.js e Express, e inclui algumas dependências essenciais para o desenvolvimento.

## Detalhes da Versão
- **Nome**: server
- **Versão**: 1.0.0
- **Licença**: ISC

## Scripts
- O script `start` pode ser executado para iniciar o servidor. Ele utiliza o comando `node` com a opção `--watch` para monitorar alterações no diretório `src/server`.

```bash
npm start
```
## Dependências
Este projeto utiliza as seguintes dependências:

- **cors**: ^2.8.5
  - Descrição: Um middleware para habilitar o controle de acesso a recursos de origens diferentes (CORS) no Express.

- **dotenv**: ^16.3.1
  - Descrição: Carrega variáveis de ambiente a partir de um arquivo `.env` para facilitar a configuração.

- **express**: ^4.18.2
  - Descrição: Um framework web rápido, não opinativo, e minimalista para Node.js.

- **openai**: ^3.2.1
  - Descrição: Biblioteca para interagir com a API da OpenAI, permitindo integração com modelos de linguagem avançados.
