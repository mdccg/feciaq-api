# feciaq-api

## Sumário

- [feciaq-api](#feciaq-api)
  - [Sumário](#sumário)
  - [Motivação](#motivação)
  - [Pilha de tecnologia](#pilha-de-tecnologia)

## Motivação

Esta API é um projeto robusto desenvolvido para organizar e armazenar projetos de Iniciação Científica submetidos à Feira de Ciências de Aquidauana (FECIAQ), uma iniciativa do Instituto Federal de Educação, Ciência e Tecnologia de Mato Grosso do Sul. Cada projeto registrado é associado a uma das cinco áreas de conhecimento, que estão claramente definidas no enumerador [`Area`](./src/entity/Area.ts), abrangendo:

- **CET** (Ciências Exatas e Tecnológicas): onde se inserem projetos voltados a física, química, engenharia e demais campos técnicos;
- **CAE** (Ciências Aplicadas à Educação): direcionada a pesquisas que exploram melhorias e inovações em métodos educacionais;
- **CBS** (Ciências Biológicas e da Saúde): focada em estudos nas áreas de biologia, medicina, saúde pública, e biotecnologia;
- **CHCSA** (Ciências Humanas, Ciências Sociais e Artes): dedicada a pesquisas nas áreas sociais e culturais, como antropologia, artes e ciências humanas;
- **MDIS** (Metodologias de Desenvolvimento e Inovação em Sistemas): voltada para a criação e inovação de sistemas e processos tecnológicos.

Os projetos contam com informações detalhadas sobre seus autores, incluindo nome completo, gênero e CPF. Cada projeto pode ter de um a sete autores, além de contar com orientador e co-orientador. Embora completa em suas funcionalidades de cadastro e gestão de dados, esta API foi concebida exclusivamente como ferramenta pedagógica, servindo para desenvolver testes automatizados utilizando Cypress, sem integrar o sistema oficial da FECIAQ. Essa proposta visa não apenas à prática de desenvolvimento de APIs e testes, mas também ao aprofundamento de habilidades em ambientes reais de simulação de dados científicos. 

Este repositório de código foi apresentado no [Curso Superior de TSI do IFMS](https://www.ifms.edu.br/campi/campus-aquidauana/cursos/graduacao/sistemas-para-internet/sistemas-para-internet) para auxiliar um discente nas atividades do Programa de Monitoria da unidade curricular Linguagem de Programação I.

## Pilha de tecnologia

| Papel                                      | Tecnologia                                    |
|--------------------------------------------|-----------------------------------------------|
| Ambiente de execução                       | [Node](https://nodejs.org/en/)                |
| Linguagem de programação                   | [TypeScript](https://www.typescriptlang.org/) |
| Framework de API                           | [Express](https://expressjs.com/pt-br/)       |
| Tecnologia de mapeamento objeto-relacional | [TypeORM](https://typeorm.io/)                |
| Banco de dados                             | [SQLite3](https://www.sqlite.org/)            |
| Framework de testes                        | [Cypress](https://www.cypress.io/)            |