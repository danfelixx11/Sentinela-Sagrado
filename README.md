# Sentinela Sagrado

Página de links oficial do projeto **Sentinela Sagrado**, criada para reunir conteúdos, produtos digitais, livros, redes sociais e projetos relacionados em um único cartão digital responsivo.

## Sobre o projeto

Este repositório contém um site estático em HTML, CSS e JavaScript. A página funciona como uma vitrine de acesso rápido para materiais do Sentinela Sagrado, incluindo guia gratuito, ebook, livros, Estantya e redes sociais.

O layout foi construído a partir da proposta de página de links no estilo DevLinks, com identidade visual própria, imagens locais, alternância entre tema claro e escuro e adaptação para desktop e mobile.

## Funcionalidades

- Lista centralizada de links para produtos, livros e projetos.
- Alternância entre modo claro e modo escuro.
- Troca automática do avatar conforme o tema selecionado.
- Imagens de fundo diferentes para mobile, desktop, light mode e dark mode.
- Links sociais com ícones do Ionicons e marca da Estantya.
- Layout responsivo sem dependência de build.

## Tecnologias

- **HTML5** para a estrutura da página.
- **CSS3** para responsividade, temas, animações e estilos visuais.
- **JavaScript** para a troca de tema e atualização do avatar.
- **Ionicons** via CDN para ícones sociais.
- **Google Fonts** via CDN para a fonte Inter.

## Estrutura

```text
.
├── assets/
│   ├── avatar.png
│   ├── avatar-light.png
│   ├── bg-desktop.jpg
│   ├── bg-desktop-light.jpg
│   ├── bg-mobile.jpg
│   ├── bg-mobile-light.jpg
│   ├── estantya.branco.png
│   ├── moon-stars.svg
│   └── sun.svg
├── index.html
├── script.js
├── style.css
└── README.md
```

## Como executar localmente

Como o projeto é estático, basta abrir o arquivo `index.html` no navegador.

Também é possível usar qualquer servidor local simples. Por exemplo, com Python:

```bash
python -m http.server 8000
```

Depois acesse:

```text
http://localhost:8000
```

## Links presentes na página

- Guia gratuito
- Ebook **IA e Fé**
- Livro **O Código do Fim** na Amazon
- Livro **O Código do Fim** no Clube de Autores
- Estantya
- Instagram do Sentinela Sagrado
- YouTube do Sentinela Sagrado
- LinkedIn de Daniel Félix

## Personalização

Para atualizar os links principais, edite a lista dentro de `index.html`.

Para alterar cores, imagens de fundo, espaçamentos e comportamento visual do tema, edite as variáveis e estilos em `style.css`.

Para modificar a lógica do botão de tema, edite a função `toggleMode()` em `script.js`.

## Autor

Projeto mantido por [Daniel Félix](https://github.com/danfelixx11).

© 2026 Sentinela Sagrado. Todos os direitos reservados.
