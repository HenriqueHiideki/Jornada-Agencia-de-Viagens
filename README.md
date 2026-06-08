# 🌏 Jornada Viagens

Projeto de agência de viagens desenvolvido durante a trilha de **Desenvolvimento Front-End** da [Alura](https://www.alura.com.br/), com foco em responsividade, boas práticas de HTML/CSS e técnicas modernas de desenvolvimento web.

---

## 📋 Sobre o Projeto

A **Jornada Viagens** é uma landing page para uma agência de turismo especializada em pacotes de viagem. O projeto abrange uma página inicial e uma página de pacotes (com foco no Japão), contemplando desde a apresentação de destinos até condições de pagamento e depoimentos de clientes.

---

## 🖥️ Páginas

- **index.html** — Página principal com ofertas da semana, categorias de busca, destinos populares, condições de pagamento, depoimentos e rodapé
- **pacotes.html** — Página de pacote específico (Japão), com hero personalizado, destinos da excursão, formas de pagamento e depoimentos

---

## ✨ Funcionalidades

- Menu hambúrguer funcional para mobile (sem JavaScript, usando `checkbox` + CSS)
- Layout responsivo para **mobile**, **tablet** e **desktop**
- Seção de depoimentos com avatares e avaliações
- Cards de ofertas com imagens de fundo
- Seção de pagamento com layout em duas colunas no desktop
- Galeria de imagens dos destinos
- Footer com redes sociais e informações de contato

---

## 🛠️ Tecnologias Utilizadas

- **HTML5** — estrutura semântica com uso de `<header>`, `<section>`, `<article>`, `<footer>`
- **CSS3** — estilização com variáveis CSS, Flexbox e Media Queries
- **Design Responsivo** — abordagem mobile-first com breakpoints em `768px` e `1024px`

---

## 📐 Técnicas Aplicadas

- **Mobile-first** — estilos base voltados para mobile, expandidos progressivamente
- **Variáveis CSS** — paleta de cores e pesos tipográficos centralizados em `:root`
- **Flexbox** — alinhamento e distribuição de layouts em múltiplas seções
- **Media Queries** — adaptações de layout para tablet (`768px`) e desktop (`1024px`)
- **CSS Reset** — normalização de margens, paddings e box-sizing
- **Reutilização de código** — classes compartilhadas entre páginas (`.section-title`, `.button-destination`, etc.)
- **SEO básico** — uso de `<meta>` description, Open Graph tags (`og:title`, `og:description`, `og:type`), atributos `alt` em imagens e `title` em links
- **Acessibilidade** — textos alternativos, labels semânticos e hierarquia de headings

---

## 📁 Estrutura de Pastas

```
jornada-viagens/
├── index.html
├── pacotes.html
├── css/
│   ├── style.css
│   └── pacotes.css
├── img/
│   ├── logo-preto.png
│   ├── logo-footer.png
│   ├── hero-mobile.png
│   ├── hero-tablet.jpg
│   ├── hero-desktop.jpg
│   └── ...
└── fontes/
    └── Montserrat-VariableFont_wght.ttf
```

---

## 🎨 Paleta de Cores

| Variável | Valor | Uso |
|---|---|---|
| `--primary-color` | `#8f0101` | Títulos e destaques |
| `--secondary-color` | `#b81515` | Botões e separadores |
| `--text-primary-color` | `#222222` | Texto principal |
| `--text-secondary-color` | `#ffffff` | Texto sobre fundos escuros |
| `--background-secondary-color` | `#f5f5f5` | Fundos alternativos |

---

## 🚀 Como Executar

1. Clone o repositório:
   ```bash
   git clone https://github.com/seu-usuario/jornada-viagens.git
   ```
2. Abra o arquivo `index.html` diretamente no navegador ou utilize uma extensão como o **Live Server** no VS Code.

> Não há dependências externas ou necessidade de instalação.

---

## 📚 Aprendizados

Durante o desenvolvimento deste projeto foram praticados:

- Estruturação semântica de páginas HTML
- Criação de layouts responsivos do zero com Flexbox
- Organização e reutilização de estilos CSS entre múltiplas páginas
- Implementação de menu mobile sem JavaScript
- Depuração e correção de bugs de layout entre breakpoints
- Técnicas de SEO on-page com meta tags e Open Graph

---



## 👨‍💻 Autor

Desenvolvido como projeto prático da trilha de Front-End da **Alura**.
