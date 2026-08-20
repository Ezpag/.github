# EzPag — tela inicial do GitHub

Landing page e perfil da organização GitHub da EzPag.

| Arquivo | Uso |
|---------|-----|
| `index.html` | Tela inicial visual (GitHub Pages) |
| `profile/README.md` | Perfil exibido em `github.com/<ORG>` |
| `assets/` | Banner, hero e logo |

## Publicar o perfil da organização

1. Crie um repositório **público** chamado `.github` na organização.
2. Envie o conteúdo deste projeto para a branch `main`.
3. Confirme que `profile/README.md` existe na raiz do repo `.github`.

O GitHub passa a renderizar o perfil automaticamente na home da org.

## Publicar a tela (GitHub Pages)

1. Em **Settings → Pages**, escolha a branch `main` e a pasta `/ (root)`.
2. A página fica disponível em `https://<ORG>.github.io/` (ou domínio customizado).

## Pré-visualizar localmente

```bash
cd /home/douglas/deploy/ezpag-github
python3 -m http.server 8080
```

Abra [http://localhost:8080](http://localhost:8080).
