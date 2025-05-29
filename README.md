
```markdown
# Boilerplate TypeScript + Node.js

Este repositório é um boilerplate minimalista para desenvolvimento com **TypeScript** e **Node.js**, utilizando `tsx` para execução em ambiente de desenvolvimento e `tsup` para build de produção.

## 📦 Estrutura

```

├── src/
│   └── server.ts       # Arquivo principal do servidor
├── .env                # Variáveis de ambiente
├── dist/               # Arquivos transpilados (gerado após build)
├── package.json
├── tsconfig.json       # (você pode adicionar conforme a necessidade)

```

## 🚀 Scripts

| Comando           | Descrição |
|------------------|-----------|
| `npm run start-dev` | Inicia a aplicação em modo de desenvolvimento com suporte a `.env` |
| `npm run start-watch` | Inicia a aplicação com watch mode (hot-reload) |
| `npm run dist`       | Gera a build de produção usando `tsup` |
| `npm run start-dist` | Gera a build e executa o código transpilado em produção |

> **Nota:** Certifique-se de ter um arquivo `.env` na raiz do projeto, se estiver usando variáveis de ambiente.

## 🛠️ Tecnologias Utilizadas

- [TypeScript](https://www.typescriptlang.org/)
- [tsx](https://github.com/esbuild-kit/tsx) - Execução de TypeScript sem build explícito
- [tsup](https://tsup.egoist.dev/) - Empacotador para produção
- [Node.js](https://nodejs.org/)

## 📄 Licença

Este projeto está licenciado sob a licença ISC.

---

Sinta-se à vontade para adaptar este boilerplate às suas necessidades!
```

