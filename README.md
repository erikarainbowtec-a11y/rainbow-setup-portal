# 🌈 Rainbow Setup Portal

Portal de levantamento de informações para parametrização da plataforma Rainbow.

## Versão

`v0.1` — base navegável, compatível com GitHub e Cloudflare Pages.

## Estrutura

```text
index.html
css/style.css
js/app.js
```

## Publicação no Cloudflare Pages

- Framework preset: **None**
- Build command: deixar em branco
- Build output directory: `/`
- Branch de produção: `main`

## Limitação atual

Nesta versão, as respostas são salvas no `localStorage` do navegador. A próxima etapa será conectar autenticação e banco de dados Supabase.
