# Bem Viver — Site Institucional

Site institucional da consultoria fictícia **Bem Viver**, desenvolvido como projeto acadêmico (UFPR).

## Estrutura do projeto

```
bem-viver/
├── index.html          → página principal
├── blog-1.html         → blog 1 (cole seu texto aqui)
├── blog-2.html         → blog 2 (cole seu texto aqui)
├── style.css           → estilos compartilhados
├── logo.png            → logo da marca
└── README.md
```

## Onde editar o quê

| O que você quer mudar | Arquivo | O que procurar |
|---|---|---|
| Texto do blog 1 | `blog-1.html` | bloco "COLE O TEXTO DO BLOG AQUI" |
| Texto do blog 2 | `blog-2.html` | bloco "COLE O TEXTO DO BLOG AQUI" |
| Resumo/título nos cards do blog | `index.html` | comentários `<!-- EDITE: ... -->` |
| Vídeo institucional | `index.html` | bloco "COMO ADICIONAR SEU VÍDEO" |
| Cores da marca | `style.css` | variáveis `--color-*` no topo |

## Como adicionar o vídeo

No `index.html`, procure o comentário **"COMO ADICIONAR SEU VÍDEO"**. Você tem duas opções:

**Opção A — Arquivo local (mp4):**
1. Coloque seu arquivo (ex: `video.mp4`) na mesma pasta do `index.html`.
2. Apague a `<div class="video-placeholder">`.
3. Descomente o bloco `<video>` (apague os `<!--` e `-->` ao redor).

**Opção B — YouTube/Vimeo:**
1. Apague a `<div class="video-placeholder">`.
2. Cole o iframe do YouTube no lugar:
```html
<iframe src="https://www.youtube.com/embed/SEU_ID" allowfullscreen></iframe>
```

## Como publicar no GitHub Pages

1. **Crie um repositório novo no GitHub** (público), por exemplo `bem-viver`.
2. **Faça upload de todos os arquivos** desta pasta para a raiz do repositório (botão "Add file" → "Upload files" na interface do GitHub funciona).
3. No repositório, vá em **Settings → Pages** (menu lateral).
4. Em **"Source"**, selecione `Deploy from a branch`.
5. Em **"Branch"**, selecione `main` e a pasta `/ (root)`. Clique em **Save**.
6. Aguarde 1–2 minutos. A URL do site aparecerá no topo da mesma página (formato `https://SEU-USUARIO.github.io/bem-viver/`).

Pronto — é esse link que você manda pro professor.

## Testando localmente (opcional)

Como o site é HTML/CSS puro, basta dar duplo-clique no `index.html` e abrir no navegador. Para o iframe do Spotify funcionar bem, prefira testar pelo link do GitHub Pages.
