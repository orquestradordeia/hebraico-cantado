# Hebraico Cantado

Protótipo estático em `index.html` com upload/URL de áudio, transcrição e teleprompter.

## Publicar no GitHub Pages

Este repositório já possui workflow em `.github/workflows/deploy-pages.yml` para deploy automático.

### Passos no GitHub (uma vez)

1. Vá em **Settings → Pages**.
2. Em **Build and deployment**, selecione **Source: GitHub Actions**.
3. Faça push na branch principal (ou rode manualmente em **Actions**).
4. A URL será exibida no job `Deploy static site to GitHub Pages`.

### Branches monitoradas

O workflow dispara em pushes para:

- `main`
- `master`
- `work`

Se quiser, ajuste em `.github/workflows/deploy-pages.yml`.
