# Zona Técnica Futsal — Site

Site estático das competições nacionais de futsal 2026/27.

## Publicação

O site está no Netlify: https://thriving-pixie-ef42b0.netlify.app

### Deploy automático (Netlify + GitHub)

1. Netlify → Site settings → Build & deploy → Continuous deployment → "Link repository"
2. Escolhe este repo (branch `main`)
3. Build command: (vazio) — é site estático
4. Publish directory: `.`

A partir daí, cada `git push` publica automaticamente.

### Deploy manual (drag-drop)

Zipar a pasta e arrastar para Netlify → Deploys.

## Bump de versão (força PWA a refrescar)

Editar `version.txt` com um timestamp novo (`date +%s`).
