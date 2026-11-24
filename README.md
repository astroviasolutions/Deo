# Dra Déo — Estética Avançada (site de agendamento)

Site publicado no Cloudflare Workers (worker `deo`, conta Deobiomedicina), com dados no Supabase.

- Raiz da pasta = site publicado (build compilado; o código-fonte original foi perdido).
- `backup-original-2026-11-04/` = cópia exata da versão anterior (logo antiga), para reverter se preciso.
- `source/` = logo original enviada pela cliente.
- Nova paleta: creme #FAF5F3, rosa #D4998F, vinho #8E4F5E, marrom #4A2F2C.

Publicar: `npx wrangler deploy --assets . --name deo --compatibility-date 2026-10-23`
