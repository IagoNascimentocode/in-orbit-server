
# Projeto: `In Orbit`

![Demonstração do Projeto](src/assets/example.gif)

**Descrição:**
O `In Orbit` é um rastreador de hábitos, onde é possível criar e monitorar o progresso de novos hábitos ao longo da semana. Os usuários podem definir quantas vezes desejam realizar um hábito e marcar quando ele for concluído, exibindo seu progresso na interface do usuário.

**Recursos:**

- Criação e monitoramento de hábitos.
- Definição de metas semanais para cada hábito.
- Exibição do progresso de cada hábito em tempo real.

**Tecnologias Utilizadas:**

- [Fastify](https://www.fastify.io/) para o servidor HTTP.
- [Zod](https://zod.dev/) para validação de dados.
- [PostgreSQL](https://www.postgresql.org/) com [Drizzle ORM](https://orm.drizzle.team/) para manipulação de banco de dados.
- [Dayjs](https://day.js.org/) para manipulação de datas.
- [TypeScript](https://www.typescriptlang.org/) para tipagem estática.

**Instalação e Configuração:**

1. Clone estes repositório:
```bash
https://github.com/IagoNascimentocode/in-orbit-web.git
```

2. Instale as dependências:
```bash
npm install
```
3. Configure o arquivo .env com as variáveis de ambiente necessárias, como as credenciais do banco de dados PostgreSQL.

4. Execute as migrations e seeds para configurar o banco de dados:
```bash
 npm run seed
```

5. Inicie o servidor de desenvolvimento:
```bash
 npm run dev
```

# Observação: 

Este repositório contém apenas o **backend** do projeto `In Orbit`. Para acessar o **frontend**, visite o seguinte repositório:  
[Link para o repositório do frontend](https://github.com/seu-usuario/in-orbit-frontend)

