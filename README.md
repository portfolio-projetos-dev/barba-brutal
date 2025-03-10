# barba-brutal

Aplicação para agendamento e gerenciamento de horários em uma barbearia. Desenvolvido com NestJS no backend e Next.js com TypeScript no frontend.

![Tela inicial](.gitassets/1.png)
![Tela inicial](.gitassets/2.png)
![Tela inicial](.gitassets/3.png)

## 🤔 O que é este projeto

Barba Brutal é uma plataforma desenvolvida para agendamento e gerenciamento de horários em uma barbearia. A aplicação permite que os clientes reservem seus horários de atendimento e que os administradores controlem os agendamentos de forma eficiente, além de gerenciar as informações dos serviços e profissionais.

## 🖥️ Como rodar este projeto

**Requisitos**:

- Node.js instalado
- PostgreSQL configurado
- Docker (opcional, para ambiente conteinerizado)

1. Clone este repositório:

```sh
git clone https://github.com/seu-repositorio/barba-brutal.git
```

2. Acesse o diretório do projeto:

```sh
cd barba-brutal
```

3. Instale as dependências:

```sh
npm install
```

4. Configure as variáveis de ambiente:  
   Crie um arquivo .env baseado no .env.example e preencha com as credenciais do banco de dados e demais configurações.

5. Execute as migrações do banco:

```sh
npx prisma migrate dev
```

6. Inicie o servidor backend (NestJS):

```sh
npm run start:dev
```

7. Inicie o frontend (Next.js):

```sh
npm run dev
```

8. Acesse o projeto em [http://localhost:3000](http://localhost:3000).

## 🗒️ Features do projeto

- Agendamento e gerenciamento de horários online
- Criação de cadastro para clientes e profissionais
- Controle de serviços oferecidos e valores
- Notificações de agendamento

## 💻 Tecnologias usadas no projeto

<div style="display: grid; grid-template-columns: repeat(auto-fit, minmax(80px, 1fr)); gap: 10px; align-items: center;">
<img src="https://img.shields.io/badge/next.js-%23000000.svg?style=for-the-badge&logo=nextdotjs&logoColor=white" alt="Next.js" />
<img src="https://img.shields.io/badge/nestjs-%23E0234E.svg?style=for-the-badge&logo=nestjs&logoColor=white" alt="NestJS" />
<img src="https://img.shields.io/badge/typescript-%23007ACC.svg?style=for-the-badge&logo=typescript&logoColor=white" alt="TypeScript" />
<img src="https://img.shields.io/badge/prisma-%232D3748.svg?style=for-the-badge&logo=prisma&logoColor=white" alt="Prisma" />
<img src="https://img.shields.io/badge/postgresql-%23316192.svg?style=for-the-badge&logo=postgresql&logoColor=white" alt="PostgreSQL" />
<img src="https://img.shields.io/badge/docker-%230db7ed.svg?style=for-the-badge&logo=docker&logoColor=white" alt="Docker" />
<img src="https://img.shields.io/badge/tailwindcss-%2338B2AC.svg?style=for-the-badge&logo=tailwind-css&logoColor=white" alt="TailwindCSS" />
<img src="https://img.shields.io/badge/jwt-%23323330.svg?style=for-the-badge&logo=json-web-tokens&logoColor=pink" alt="JWT" />
</div>

## ⚙️ Sobre o desenvolvimento desse projeto

Este projeto fullstack foi desenvolvido com uma arquitetura que separa claramente o frontend e o backend, garantindo uma comunicação eficiente entre as camadas.

- **Frontend**: Desenvolvido com Next.js, proporcionando uma experiência dinâmica e responsiva.
- **Backend**: Construído com NestJS, que oferece escalabilidade e robustez na criação da API.
- **Banco de dados**: Utiliza PostgreSQL, com migrations e modelos gerenciados pelo Prisma.

A utilização de Docker é opcional e permite a execução do ambiente de forma conteinerizada, facilitando a integração e o deploy.

## 💎 Links úteis

- [Next.js](https://nextjs.org/docs)
- [NestJS](https://docs.nestjs.com/)
- [Prisma](https://www.prisma.io/docs)
- [PostgreSQL](https://www.postgresql.org/docs/)
- [Tailwind CSS](https://tailwindcss.com/docs)
