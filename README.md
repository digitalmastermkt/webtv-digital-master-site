# WebTV e Digital Master - Site Comercial

Pagina de vendas da agencia de marketing digital com IA do interior do Piaui.

**URL producao:** https://webtv.agencianobolso.com.br/
**Socios:** Salatiel Batista (IA aplicada) + Fabricio (Portal WebTV Piaui, 47k seguidores)
**Subdominio:** webtv.agencianobolso.com.br (Cloudflare DNS, GitHub Pages)

## Estrutura

- `index.html` - landing comercial single-page
- `assets/` - imagens
- `CNAME` - dominio customizado GitHub Pages

## Deploy

GitHub Pages a partir de `main` branch root. CNAME aponta pra subdominio configurado no Cloudflare DNS da zona `agencianobolso.com.br`.

## Pendencias

- Foto profissional do Fabricio (atualmente placeholder)
- Numero WhatsApp da agencia se for diferente do Salatiel (atual: 86 98114-1438)
- Logo grafica da agencia (se decidirem criar)

## Stack

HTML + CSS puro, mobile-first, sem build. Deploy estatico no GitHub Pages com cert Let's Encrypt automatico.
