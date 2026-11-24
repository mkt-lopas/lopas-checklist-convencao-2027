# Convenção 2027 — Checklist de entrega (camisas e credenciais)

Página online (GitHub Pages) para controlar a entrega de camisas e credenciais do evento Convenção 2027, por regional e interno. Dados compartilhados em tempo real pelo Supabase (projeto mkt-lopas).

## Configuração
1. No Supabase, abra **SQL Editor**, cole o conteúdo de `supabase_checklist.sql` e rode (cria a tabela `chk_entregas` com as 103 pessoas e ativa o tempo real).
2. Em `index.html`, preencha `SUPABASE_URL` e `SUPABASE_ANON_KEY` (Project Settings → API).
3. Em **Settings → Pages** do repositório, publique a branch `main`, pasta `/ (root)`.
