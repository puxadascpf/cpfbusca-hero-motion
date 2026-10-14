# 🎬 CPF Busca — Hero Motion (loop premium)

Vídeo de produto SaaS de **14s em loop perfeito**, 1920×1080 @ 60fps, sem texto promocional (apenas a interface do produto), feito para a primeira dobra de landing pages.

- `cpfbusca-hero-loop.webm` — VP9 (web)
- `cpfbusca-hero-loop.mp4` — H.264
- `poster.jpg` — frame do dashboard
- `index.html` — página de demonstração (player em loop)

## Sequência

Abertura com linhas cyan → Dashboard → Consulta com dados mascarados (`***.***.***-**`) → Histórico → API (Start/Plus/Pro/Scale + fluxo de requisição) → Segurança → fechamento só com a logo, conectando ao primeiro frame.

## Uso no hero

```html
<video autoplay muted loop playsinline preload="metadata" poster="poster.jpg" aria-hidden="true">
  <source src="cpfbusca-hero-loop.webm" type="video/webm" />
  <source src="cpfbusca-hero-loop.mp4" type="video/mp4" />
</video>
```

Site oficial: **https://cpfbusca.com/**
