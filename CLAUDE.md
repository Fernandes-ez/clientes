# clientes · biosites entregues (link.ezf-tech.com/<slug>)

- Um site por cliente em `public/<slug>/index.html`, gerado a partir do `_modelo-biosite` do repositório `prototipos`.
- Entrega paga: **sem** `noindex` (remova a meta do modelo). Nunca invente dados do cliente.
- Deploy: Cloudflare (Workers com assets). `wrangler.jsonc` aponta para `./public`; o nome do worker deve continuar `clientes`.
- Anote cada cliente (slug, domínio, data) no `leads.csv` do repositório `prototipos`.
