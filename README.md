## Boiler o que?
O boilerplate é onde todos os projetos usando essas mesmas carácterísticas começam.

Do mesmo jeito em que teríamos que escrever essa arquitetura over and over toda vez que rodamos `create-next-app`,
o boilerplate surge para iniciar e finalizar a arquitetura mínima que todo projeto compartilha, tornando assim, 
muito mais simples iniciar um projeto.

## Tá, mas quais dependências vocês tem aqui?
Quanto as versões das dependências, você pode encontrar facilmente no `package.json`.

Quanto a dependências, estamos usando tudo que há de mais divertido e que conceitualmente se adapte ao objetivo de um e-commerce next/react.

NextJs e React - frameworks de desenvolvimento front-end.

TS, TSX e ESLint - linguagem e Linter

## Começando

Primeiramente, execute o comando:

```bash
npm run dev
# or
yarn dev
```

abra [http://localhost:3000](http://localhost:3000) no seu navegador pra ver o resultado.

## Configurações adicionais do linter:
- [react-hooks](https://www.npmjs.com/package/eslint-plugin-react-hooks)
- [prop-types](https://github.com/yannickcr/eslint-plugin-react/blob/master/docs/rules/prop-types.md) - desabilidado uma vez que usaremos TS.
- [react/react-in-jsx-scope](https://github.com/yannickcr/eslint-plugin-react/blob/master/docs/rules/react-in-jsx-scope.md) - desabilidado por que o escopo do react no next é gobal.
- [@typescript-eslint/explicit-module-boundary-types](https://github.com/typescript-eslint/typescript-eslint/blob/master/packages/eslint-plugin/docs/rules/explicit-module-boundary-types.md) - Quando o tipo é inferido pelo TS, não se torna obrigatório tipar o retorno.

## Git Hooks
- [husky](https://typicode.github.io/husky/#/) - documentação do husky

O husky não permite que commits que não passarem nos testes ou linters sejam feitos.

- [lint-staged](https://github.com/okonet/lint-staged) - documentação do lint-staged

Como o nome diz, roda linters contra os arquivos `staged` para encontrar problemas.

## Testes
- [jest](https://jestjs.io/docs/getting-started#using-typescript) - instalação do jest para typescript

## Aprenda mais sobre
- [o que é boileplate?](https://www.freecodecamp.org/news/whats-boilerplate-and-why-do-we-use-it-let-s-check-out-the-coding-style-guide-ac2b6c814ee7/)
- [documentação do nextjs](https://nextjs.org/docs) - aprenda mais sobre as features do next e suas apis.
- [Aprenda nextjs](https://nextjs.org/learn) - tutorial interativo do next.
- [Editor config](https://editorconfig.org/#overview) - Overview geral do editor config.

This is a [Next.js](https://nextjs.org/) project bootstrapped with [`create-next-app`](https://github.com/vercel/next.js/tree/canary/packages/create-next-app).
