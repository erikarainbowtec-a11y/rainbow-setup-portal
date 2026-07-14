# 🌈 Rainbow Setup Portal

Portal de implantação e parametrização da plataforma Rainbow.

## Versão

`v0.2.0` — aplicação navegável com login demonstrativo, dashboard, gestão de projetos e wizard completo.

## Funcionalidades

- Login demonstrativo.
- Dashboard de projetos.
- Criação de novos projetos.
- Busca e filtro de projetos.
- Wizard de parametrização com 9 etapas.
- Cadastro dinâmico de documentos.
- Salvamento automático no `localStorage`.
- Exportação das respostas em JSON.
- Layout responsivo.

## Estrutura

```text
index.html
css/
  style.css
js/
  app.js
README.md
.gitignore
```

## Publicação no Cloudflare Pages

Ao conectar o repositório GitHub:

- Framework preset: `None`
- Build command: deixar em branco
- Build output directory: `/`
- Production branch: `main`

## Acesso demonstrativo

- E-mail: `erika@rainbowtec.com.br`
- Senha: `rainbow123`

Nesta versão, qualquer e-mail e senha preenchidos permitem o acesso, pois a autenticação real ainda não foi conectada.

## Próxima versão

- Supabase Auth.
- Banco PostgreSQL.
- Controle de acesso por perfil.
- Persistência compartilhada entre usuários.
