# JL Marcenaria · Inteligência de orçamento

Versão pronta para subir no GitHub e publicar no Netlify.

## Arquivos principais

- `index.html` — app completo corrigido.
- `manifest.json` — configuração PWA.
- `sw.js` — service worker.
- `icons/` — ícones do app/PWA.
- `netlify.toml` — configuração de deploy Netlify.
- `supabase-schema.sql` — tabela `projetos`, RLS e políticas.

## Antes de testar o Supabase

Rode o arquivo `supabase-schema.sql` no SQL Editor do Supabase.

## Commit sugerido

```bash
git add .
git commit -m "fix: stabilize Supabase integration and PWA assets"
git push
```


## Versão v4.2 — Design VS Marcenaria aplicado

Esta versão aplica o design system de marcenaria premium ao app:

- Paleta mogno/noite, âmbar mel e cobre.
- Tipografia Playfair Display + Source Serif 4 + JetBrains Mono.
- Textura sutil de veios de madeira no fundo.
- Raios menores, com sensação de corte preciso.
- Cards, botões, abas, inputs, KPIs e proposta PDF ajustados ao novo visual.
- Manifest e Service Worker atualizados para nova versão visual.
