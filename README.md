<h1 align="center">Projeto de estudos de Grahpql/ Prisma 2/ Nexus</h1>

## ✨ Tecnologias

Esse projeto foi desenvolvido com as seguintes tecnologias:

- [Graphql](https://graphql.org/)
- [Nexus](https://nexusjs.org/)
- [Prisma](https://www.prisma.io/)

## 🚀 Como executar

- Clone o **repositório**
- Rode `yarn` para baixar as dependências
- Rode o `yarn start` para iniciar a aplicação.

## Graphql

-  Graphql é uma especificação para criar e usar APIs que têm sua própria linguagem de query.

- Ele é uma especificação para APIs, para escrever, criar e utilizar APIs e não está ligado a nenhum tipo de banco,
	inclusive ele pode ser usado com qualquer base de dados.

- O Graphql fornece um ambiente para executarmos essas queries usando os dados que fornecermos para ele, não importa de onde esses dados venham.

- Os schemas do Graphql são baseados em como os dados são usados, e não como estão armazenados.

- O Graphql com isso procura resolver um problema em rest, uma questão do rest que costumamos chamar de overfitting, que seria super requisição, e também o underfitting, que é sub requisição. É quando o endpoint ou traz muitos dados que não precisamos numa requisição ou o contrário, precisamos de mais de uma requisição para ter os dados que precisamos.

## Prisma 2
- Toolkit para databases além do orm, não apenas para graphql mas tb para api's rest
- Schemas code-first com nexus.
- Prisma + nexus trabalham muito bem juntos e tornam uma experiencia de graphql e bases de dados ágil/bem fluidas.
- Agiliza o desenvolvimento.

## Nexus

- Combina a sumplicidade e a facilidade de um desenvolvimento focado em abordagem SDL como graphql-tools.
- É um Auto gerador de type-definitions enquanto desenvolve e coloca no código.

## 📄 Comandos interessantes

- Rode `npx prisma migrate down --experimental` para voltar para ultima versão da migração
- Rode `npx prisma migrate` para realizar uma migração
- Rode `npx prisma introspect` para pegar tabelas do banco e relizar um "database-first"
- Rode `npx prisma init` para iniciar um projeto com Prisma
- Rode `npx prisma studio` para pesquisar dados através de uma UI
- Rode `npx prisma migrate dev` para criar migrações à partir do Schema do Prisma, aplicar o banco e gerar os artefatos