# Site pessoal (Eduardo)

Site feito com [Jekyll](https://jekyllrb.com/) e o starter [al-folio](https://github.com/alshedivat/al-folio) (MIT), em português.

## Já configurado

Usuário do GitHub: `eduardobatista26`; sobrenome: Batista. Se algo estiver errado, ajuste em `_config.yml`, `_data/socials.yml`, `_data/cv.yml` e `assets/json/resume.json`.

## Onde editar

| O que | Arquivo |
| --- | --- |
| Nome, descrição, rodapé, idioma | `_config.yml` |
| Foto | `assets/img/prof_pic.jpg` |
| Página inicial | `_pages/about.md` |
| Prêmios, publicações e eventos | `_pages/publications.md` |
| Ensino e monitoria | `_pages/teaching.md` |
| Links sociais | `_data/socials.yml` |
| Fontes e efeitos de texto | `assets/css/custom.css` |

## Publicar no GitHub Pages

1. Crie um repositório **público** chamado exatamente `eduardobatista26.github.io` e envie estes arquivos para a branch `main`.
2. O workflow `.github/workflows/deploy.yml` roda sozinho e cria a branch `gh-pages`.
3. Em **Settings → Pages**, escolha a branch `gh-pages` como fonte.
