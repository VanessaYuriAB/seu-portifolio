# 🗂️ Seu Portfólio

Este é um **projeto educacional guiado** desenvolvido durante o curso de Desenvolvimento
Web da **TripleTen**, iniciado na **Sprint 2 – Layout de Página e Semântica** e
posteriormente expandido na **Sprint 4 – HTML e CSS Avançados**.

O projeto simula um _portfólio pessoal_, utilizado como exercício prático para consolidar
conceitos essenciais de **estruturação de páginas web**, **semântica HTML** e, em uma
etapa posterior, **interatividade visual com CSS**.

> Após a conclusão do curso, o projeto foi personalizado e adaptado, passando a
> representar um portfólio pessoal, com projetos próprios desenvolvidos ao longo do
> bootcamp e links reais de contato.

---

## 🔗Visualização do Projeto:

Está disponível via **GitHub Pages**:

➡️ https://vanessayuriab.github.io/seu-portfolio/

---

## 📌 Visão Geral

O site apresenta projetos organizados em seções temáticas, com código progressivamente
aprimorado ao longo das Sprints do curso.

Cada etapa teve um **objetivo educacional específico**, refletindo a evolução técnica do
conteúdo estudado.

Após a finalização o curso, foram realizadas adaptações autorais, incluindo:

- Adição dos **projetos desenvolvidos pela autora**
- Inserção de **links reais para redes sociais e repositórios**
- **Personalização de cores e detalhes visuais**, reforçando identidade própria

Essas alterações não fizeram parte da avaliação do curso e foram realizadas de forma
independente.

---

## 🧠 Conceitos Trabalhados - Sprint 2

### _Meta Tags e Semântica HTML_

Na **Sprint 2**, o projeto foi iniciado a partir de uma **estrutura base fornecida**, com
foco exclusivo em **HTML semântico** e **boas práticas de marcação**, **sem aplicação de**
**Flexbox ou layout avançado** nesta etapa.

#### ✅ Idioma e SEO Básico

- Definição do idioma da página com:

```HTML
<html lang="pt-BR">
```

- Uso do atributo **lang** em conteúdos específicos (ex: link em inglês no cabeçalho)

#### ✅ Meta Tags

Configuração das principais meta tags no `<head>`:

- charset
- viewport
- description
- keywords
- author

Objetivo:

- Melhor compatibilidade entre navegadores
- Preparação inicial para SEO

---

##### ✅ Substituição de `<div>` por Tags Semânticas

Conversão de blocos genéricos em elementos HTML5 semânticos:

- `<div class="header">` → `<header>`
- `<div class="menu">` → `<nav>`
- `<div class="main">` → `<main>`
- `<div class="footer">` → `<footer>`

📌 As _classes foram mantidas_, reforçando a separação entre _estrutura (HTML)_ e _estilo
(CSS)_.

---

##### ✅ Organização Semântica do Conteúdo

- Divisão da página em `<section>` com títulos claros
- Uso correto da hierarquia de títulos:
  - `<h1>` no cabeçalho
  - `<h2>` para seções de conteúdo
- Criação de identificadores (**id**) para navegação interna:
  - **beginner**
  - **libraries**
  - **practice**

---

##### ✅ Listas Semânticas

Conversão de blocos de projetos em listas reais:

- `<ul>` para grupos de projetos
- `<li>` para cada card

Benefícios:

- Marcação semanticamente correta
- Melhor leitura por leitores de tela
- Código mais legível e organizado

Remoção dos estilos padrão das listas via CSS:

```CSS
list-style: none;
padding: 0;
margin: 0;
```

---

##### ✅ Navegação Interna

- Transformação dos itens do menu em **links âncora**
- Ligação direta entre o `<nav>` e as `<section>` correspondentes

Isso melhora:

- Usabilidade
- Acessibilidade
- Estrutura semântica da página

---

## ✨ Atualizações Posteriores – Sprint 4

### _Interatividade com CSS_

Na **Sprint 4**, o projeto foi expandido para incluir **interações visuais e seletores
avançados de CSS**, sem uso de `JavaScript`.

#### 🔹 Pseudoclasses

- `:hover`
- `:focus`
- `:last-of-type`
- Controle de estados visuais de links e cards

#### 🔹 Overlays Interativos

- Links posicionados sobre os cards de projeto
- Exibição controlada por `opacity`
- Centralização com `Flexbox` (introduzido nesta etapa)

#### 🔹 Pseudo‑elementos

- Uso de `::before` e `::after`
- Inserção dinâmica de saudações e símbolos

#### 🔹 Seletores de Atributo

- Alteração de conteúdo com base no atributo `lang`
- Demonstração de controle contextual de estilo via `CSS`

---

## 🗂️ Estrutura do Projeto

```bash
seu-portfolio/
├── .gitignore
├── index.html
├── README.md
└── style.css
```

---

## 🛠️ Tecnologias Utilizadas

- `HTML5`
  - Semântica
  - Meta tags
- `CSS3`
  - Seletores avançados
  - Pseudoclasses e pseudo-elementos
- `normalize.css` (via _CDN_ da _TripleTen_)
  - Garantia de consistência entre navegadores

_🌐 `Content Delivery Network` (`Rede de Distribuição de Conteúdo`): infraestrutura de
servidores espalhados pelo mundo que serve arquivos estáticos com mais rapidez. Usado com
`<link>` ou `<script>`. Fornece CSS, JS, imagens, fontes. E não processa lógica._

---

## 🎯 Objetivo Educacional

Consolidar fundamentos essenciais do desenvolvimento front‑end, preparando a base para:

- Layouts responsivos
- `JavaScript`
- Frameworks modernos
- Portfólio técnico para processos seletivos

O projeto reflete a **evolução progressiva do aprendizado**, respeitando os limites e
objetivos de cada sprint.

---

## 🚀 Como Abrir o Projeto

1. Clone o repositório:

```bash
git clone git@github.com:VanessaYuriAB/seu-portfolio.git
```

2. Abra o arquivo `index.html` em qualquer navegador moderno.

**Obs**: você pode, também, utilizar a extensão `Live Server` do `VS Code`.

---

## 👩‍💻 Autora

Vanessa Yuri A. Brito

Projeto educacional desenvolvido durante o curso de Desenvolvimento Web da TripleTen e
organizado como parte de um portfólio profissional no GitHub, com foco em clareza técnica
e boas práticas.
