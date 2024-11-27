# Next.js App

## Descrição

Projeto de início do Next.js, guia seguindo o link: https://nextjs.org/learn

---

Nesse guia é possível aprender os conceitos iniciais do Next com o uso de algumas funcionalidades como 

- Compoentes React
- Contextos
- Renderização condicional
- Roteamento entre os arquivos
- Manipulação de dados
- Criação de CRUD
- Manipulação de formulários
- Tratamentos de exceção
- Renderização de dados
- Server components
- Utilização de SQL para salvar dados em componentes de backend
- Autenticação de usuários
- Deploy do projeto no Vercel

Esses itens essenciais para a criação de projetos com o Next.js, e com uma base de conhecimento bem fundamentada é possível implementar um aplicativo completo e funcional.

## Telas do projeto

- Login

![Página de login](public\login.png)

- Dashboard

![Página dashboard](public\dashboard.png)

- Lista de faturas

![Lista de faturas](public\lista-faturas.png)

- Formulário de faturas

![Formulário de faturas](public\form-faturas.png)

## Guia de instalação

### Requisitos

Node.js 18.18 ou maior.

1. Clonar o projeto

```
git clone git@github.com:VitorCeron/nextjs-dashboard.git
```

2. Instalar as dependências

```
cd nextjs-dashboard
npm install
```

3. Clonar o .env.example e renomear para .env

Nesta etapa, adicionar as chaves de banco de dados do postgres criadas no Vercel, e também uma chave secret para autenticação gerada aleatoriamente.

4. Executar o ambiente de desenvolvimento
```
npm run dev
```
