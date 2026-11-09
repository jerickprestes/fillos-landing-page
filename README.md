# Fillos · Landing page

Landing page da clínica Fillos (transplante capilar, Taubaté - SP), construída a partir do layout do Figma ("Desktop - Escuro").

HTML5 semântico, CSS3 (Grid/Flexbox), mobile first, sem frameworks e sem JavaScript de terceiros.

## Estrutura

```
index.html   # marcação
main.css     # todo o estilo (sem estilos inline)
assets/      # imagens, ícones SVG e favicon
```

## Como ajustar

- **Vídeo:** cole a URL de incorporação (embed) em `data-embed` na `div.video` do `index.html`, por exemplo `https://www.youtube.com/embed/ID_DO_VIDEO`.
- **Formulário:** está com `action="#"`. Aponte para o backend, um serviço de formulários ou trate o envio em JavaScript.
- **Cores e tamanhos:** variáveis CSS no bloco `:root` do `main.css` (`--gold`, `--bg`, `--fs-*`).
- **Compartilhamento:** depois de publicar, adicione `og:image` e `og:url` (endereços absolutos) no `<head>`.

## Breakpoints

Mobile first. O layout em colunas aparece a partir de 640px e o layout desktop do Figma (coluna de 840px) a partir de 900px.

## Publicação

Qualquer hospedagem estática serve (GitHub Pages: Settings → Pages → branch `main`, pasta `/ (root)`).
