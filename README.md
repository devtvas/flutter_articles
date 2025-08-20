# Flutter Articles

Bem-vindo à documentação dos artigos Flutter!

## Como rodar localmente

```sh
pip install mkdocs-material mike
mkdocs serve
```

Acesse: http://127.0.0.1:8000

## Publicar no GitHub Pages

- O deploy é feito automaticamente via GitHub Actions (workflow).
- Ou rode manualmente:

```sh
mkdocs gh-deploy
```

## Estrutura sugerida

- docs/
  - 00 Objetivos.md
  - 05 Getting Started.md
  - ...

## Personalização rápida

Use placeholders como:
- `com.your.app` (Bundle ID)
- `Your App` (nome do app)
- `clientA`, `clientB` (flavors)
- `prod`, `dev`, `stg` (ambientes)

Edite os arquivos `.md` conforme necessário.
