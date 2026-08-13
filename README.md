# FORÇA — PWA

Arquivos:
- `index.html` — aplicação FORÇA com Supabase e registro do Service Worker.
- `manifest.json` — configuração do PWA.
- `service-worker.js` — cache básico/offline do app shell.
- `icons/` — ícones 192x192 e 512x512.
- `.nojekyll` — evita processamento desnecessário do Jekyll no GitHub Pages.

## Publicação
Envie todos esses arquivos para a raiz do repositório e ative GitHub Pages em `main` / `/ (root)`.

## Supabase
A aplicação continua usando o Supabase para autenticação e dados. O modo offline não substitui o banco: sem internet, dados novos do Supabase não serão sincronizados.
