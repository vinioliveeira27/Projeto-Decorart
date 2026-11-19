# Decorart – Móveis Sob Medida

Reforma do site da marcenaria do meu pai, com foco em front-end moderno, responsivo e pronto para uso profissional.

## Sobre o projeto

O site original foi criado pelo meu irmão, **Gabriel Oliveira**, para a marcenaria do meu pai. Ele tem cerca de **15 anos** e acompanhou o negócio por muito tempo, mas hoje está desatualizado em design, desempenho e usabilidade em celulares.

Este projeto é a **reformulação completa** desse site. Ele tem dois objetivos:

1. **Aprendizado:** praticar HTML, CSS e JavaScript em um projeto real, com cliente real e necessidades reais.
2. **Uso profissional:** sair do papel e virar o site oficial da marcenaria, ajudando a apresentar os trabalhos e a receber pedidos de orçamento.

## Objetivos

- Modernizar o visual mantendo a identidade da marca.
- Tornar o site totalmente **responsivo** (celular, tablet e desktop).
- Mostrar os **móveis sob medida** em uma galeria de projetos.
- Facilitar o contato e o pedido de orçamento (WhatsApp, telefone e formulário).
- Melhorar **desempenho**, **acessibilidade** e **SEO** básico.
- Servir de portfólio de front-end para quem desenvolve.

## Funcionalidades

- [ ] Página inicial com apresentação da marcenaria
- [ ] Seção "Sobre nós"
- [ ] Galeria de projetos (cozinhas, dormitórios, closets, painéis, etc.)
- [ ] Lista de serviços
- [ ] Formulário de contato / orçamento
- [ ] Botão flutuante de WhatsApp
- [ ] Mapa com a localização
- [ ] Menu responsivo (hambúrguer no celular)
- [ ] Favicon, ícones e imagem de compartilhamento (Open Graph)

## Tecnologias

- **HTML5**: estrutura semântica
- **CSS3**: Flexbox, Grid, variáveis CSS e media queries
- **JavaScript (ES6+)**: menu, galeria e validação do formulário
- **Git e GitHub**: versionamento do código

## Identidade visual

| Item | Valor |
| --- | --- |
| Cor principal (azul) | `#0080FB` |
| Texto escuro | `#2B2B2B` |
| Fundo | `#FFFFFF` |

Os logos e ícones têm **fundo transparente** e ficam nas pastas abaixo:

- `img/logo-completo.png`: logo com o slogan "Móveis Sob Medida".
- `img/logo-sem-slogan.png`: logo sem o slogan.
- `img/logo-fundo-escuro.png`: versão com "art" e slogan em branco, para fundos escuros.
- `favicon/`: `favicon.ico`, PNGs de 16, 32 e 48 px, `apple-touch-icon.png`, `icon-192.png`, `icon-512.png` e `site.webmanifest`.
- `social/og-image.png`: imagem de 1200×630 usada quando o site é compartilhado.

## Estrutura de pastas

```
decorart/
├── index.html
├── css/
│   └── style.css
├── js/
│   └── script.js
├── img/
│   ├── logo-completo.png
│   ├── logo-sem-slogan.png
│   ├── logo-fundo-escuro.png
│   └── icone-d-site.png
├── favicon/
│   ├── favicon.ico
│   ├── apple-touch-icon.png
│   ├── icon-192.png
│   ├── icon-512.png
│   └── site.webmanifest
├── social/
│   └── og-image.png
└── README.md
```

> Ajuste a árvore se a organização real do projeto for diferente.

## Como executar

Não precisa instalar nada:

```bash
# 1. Clonar o repositório
git clone https://github.com/SEU-USUARIO/SEU-REPOSITORIO.git

# 2. Entrar na pasta
cd SEU-REPOSITORIO

# 3. Abrir o index.html no navegador
```

Para uma experiência melhor, use a extensão **Live Server** no VS Code: clique com o botão direito no `index.html` e escolha *Open with Live Server*.

## Roadmap

- [ ] Finalizar o layout responsivo de todas as páginas
- [ ] Adicionar as fotos reais dos projetos do meu pai
- [ ] Otimizar imagens (WebP e *lazy loading*)
- [ ] Revisar acessibilidade (contraste, `alt` nas imagens, navegação por teclado)
- [ ] Configurar SEO básico (título, descrição e dados estruturados)
- [ ] Publicar o site (GitHub Pages, Netlify ou hospedagem própria)
- [ ] Registrar o domínio oficial

## Créditos

- **Site original:** Gabriel Oliveira
- **Reformulação:** Vinicius
- **Marcenaria:** negócio da família

## Status

🚧 Em desenvolvimento, como estudo de front-end e com possível implantação profissional.