# Everton Miranda · Decorações & Locações para Festas

Site da loja de locação de itens para festa M.E Decorações (Penha, São Paulo).
Página única em HTML/CSS/JS puro, sem build.

## Publicação (Vercel)

Publicado em produção na Vercel e **liberado para o Google** (`robots.txt` + `sitemap.xml`):
https://everton-miranda-festas.vercel.app. Cada commit na `main` vai direto para o ar.

Para esconder do Google de novo, volte a pôr no `vercel.json`:

```json
"headers": [
  { "source": "/(.*)", "headers": [{ "key": "X-Robots-Tag", "value": "noindex, nofollow" }] }
]
```

## Para confirmar com o Everton

- [ ] Horário da loja (veio do Google: terças e sextas, 11h às 15h).
- [ ] Ocasiões atendidas e as categorias do acervo.
- [ ] Se faz montagem fora da Zona Leste e se cobra frete.
- [ ] Instagram da loja, para pôr no site.
- [ ] Fotos reais das montagens, para uma galeria.
