# Adriana Reis Beauty - Estética em Moema

Site institucional one-page para a Estética em Moema | Adriana Reis Beauty.

## Estrutura

```
adriana-reis-estetica/
├── index.html              # One-page principal
├── sitemap.xml             # Sitemap pro Google
├── robots.txt              # Diretivas pros crawlers
└── img/                    # Imagens otimizadas (JPEG 85, progressive, max 1200px)
    ├── adriana-reis-fundadora-estetica-moema.jpg
    ├── adriana-reis-sobre-estetica-moema.jpg
    ├── estetica-moema-sala-atendimento.jpg
    ├── estetica-moema-recepcao.jpg
    ├── estetica-moema-produtos-profissionais.jpg
    └── estetica-moema-atendimento-adriana-reis.jpg
```

## Stack Técnica

- HTML/CSS/JS puro (zero dependências)
- Schema Markup: BeautySalon + LocalBusiness + FAQPage + AggregateRating
- Fontes: Cormorant Garamond + Manrope
- Performance: anti-FOUC, reveal sem CLS, imagens lazy-loaded
- Mobile-first

## Deploy (Render Static Site)

1. Push pro GitHub
2. No Render: New > Static Site > conectar repo
3. Build Command: (deixar vazio)
4. Publish Directory: `.`
5. Auto-Deploy: On

## SEO Pós-Deploy

- [ ] Configurar domínio `adrianareisestetica.com.br` no Render
- [ ] Verificar site no Google Search Console
- [ ] Enviar sitemap.xml pelo Search Console
- [ ] Otimizar Google Meu Negócio (categoria, fotos, posts)
- [ ] Coletar 10+ reviews 5 estrelas no GMB nos primeiros 30 dias

© 2026 Adriana Reis Beauty
