# elpoemario-auth

OAuth proxy (GitHub) para Decap CMS de [El Poemario](https://elpoemario.com).

Desplegado en `https://auth.elpoemario.com` vía Cloudflare Workers.
Réplica del Worker hermano `elfabulario-auth`.

## Despliegue

```
npm install
wrangler secret put OAUTH_CLIENT_ID
wrangler secret put OAUTH_CLIENT_SECRET
wrangler deploy
```