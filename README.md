# Boilerplate Next.js com App Router

Este é um boilerplate moderno para projetos Next.js utilizando o App Router, TypeScript e várias ferramentas de desenvolvimento para garantir qualidade e produtividade.

## 🚀 Tecnologias

- [Next.js 15](https://nextjs.org/)
- [React 18](https://reactjs.org/)
- [TypeScript](https://www.typescriptlang.org/)
- [Jest](https://jestjs.io/)
- [Testing Library](https://testing-library.com/)
- [Storybook](https://storybook.js.org/)
- [ESLint](https://eslint.org/)
- [Prettier](https://prettier.io/)
- [Husky](https://typicode.github.io/husky/)
- [TailwindCSS](https://tailwindcss.com/)

## 📝 Pré-requisitos

- Node.js (versão LTS recomendada)
- npm ou yarn

## 🎮 Scripts Disponíveis

- `npm run dev` - Inicia o servidor de desenvolvimento
- `npm run build` - Cria a versão de produção
- `npm run start` - Inicia o servidor de produção
- `npm run lint` - Executa a verificação de linting
- `npm test` - Executa os testes
- `npm run test:watch` - Executa os testes em modo watch
- `npm run test:ci` - Executa os testes em ambiente de CI
- `npm run generate` - Gera novos componentes usando plop
- `npm run storybook` - Inicia o Storybook na porta 6006
- `npm run build-storybook` - Cria a versão de produção do Storybook

## 🏗️ Estrutura do Projeto

```
src/
  ├── app/          # Páginas e rotas do Next.js
  ├── components/   # Componentes React reutilizáveis
  ├── styles/       # Arquivos de estilo
  └── types/        # Definições de tipos TypeScript
```

## 🔧 Configurações

O projeto inclui várias configurações para garantir a qualidade do código:

- ESLint para linting
- Prettier para formatação de código
- Jest e Testing Library para testes
- Husky para git hooks
- Lint-staged para verificação de código antes dos commits
- Storybook para documentação de componentes

## 🚀 Começando

1. Clone o repositório

```bash
git clone [url-do-repositório]
```

2. Instale as dependências

```bash
npm install
# ou
yarn
```

3. Inicie o servidor de desenvolvimento

```bash
npm run dev
# ou
yarn dev
```

4. Acesse `http://localhost:3000`

## 📚 Documentação

- Os componentes podem ser visualizados e testados através do Storybook
- A documentação de componentes está disponível rodando `npm run storybook`
- Testes unitários estão localizados junto aos componentes