# Projeto de Avliação 1 - Introdução a Computação
## Protótipo de site para Tania Bonfim Bolos.

### 1. Objetivo

>Criar um site estático institucional (apenas HTML e CSS) para uma marca fictícia à escolha do trio (ex.: cafeteria, estúdio de design, ONG, clínica, entre outros), focado em HTML semântico, CSS organizado e acessibilidade básica.

### 2. Regras e escopo

>**Tecnologias**: apenas HTML5 + CSS3 (sem frameworks; permitido Google Fonts e ícones via CDN).

### 3. Páginas obrigatórias

1. **Home (index.html)**
- Hero* com Título, subtítulo e botão/âncora.
- Barra de navegação com links para todas as páginas.
- Destaques em **cards** (mín. 3) em **flex**.

*Hero: Essa seção na página inicial costuma apresentar uma imagem ou vídeo impactante, um título conciso, um texto persuasivo e uma chamada para ação (CTA) que guia o visitante para as próximas etapas desejadas no site. 

2. **Sobre/Serviços/Produtos (sobre.html)**
- Seções com títulos hierárquicos (`<h1>…<h3>`).
- Lista (ordenada ou não) e uma **tabela simples** (ex.: planos, preços, agenda).

3. **Contato (contato.html)**
- Endereço fictício + mapa.

### 4. Requisitos HTML mínimos

**Semântica**: usar `header`, `nav`, `main` e `footer`.
**Acessibilidade básica**:

- Texto alternativo em imagens (`alt`).
- Ordem lógica de títulos (sem pular do `h1` para `h4`).

**Links internos** funcionando e **breadcrumb** simples em páginas internas (opcional).

### 5. Requisitos CSS mínimos

**Tipografia**: declarar 1–2 fontes via Google Fonts 

**Cores**: paleta com 4 cores principais (definir em `:root` com variáveis CSS).

**Layout**: usar **Flexbox** 

**Boas práticas**: evitar `!important`, evitar inline-style, usar classes.

### 6. Conteúdo

Criar uma **identidade mínima** (nome, slogan, paleta, ícones).

Todos os textos devem ser **autênticos** (nada de *Lorem ipsum* puro na entrega final).

### 7. Entregáveis pelo Google Classroom

- **Link** do repositório do Github com toda a estrutura solicitada.
- **Link** para um vídeo de 1 minuto no máximo mostrando a navegação do site e apontando 3 decisões de design/código tomadas pela equipe.
- **Link** do site ativo (Github Pages, Vercel ou qualquer outra ferramenta)

Obs: No repositório o arquivo **README.md** (obrigatório) deve conter:

- Título do projeto + 1 parágrafo de descrição.
- Autores (trio) e papéis (quem cuidou de quê).
- Paleta de cores (hexadecimal) + fontes usadas.
- Como abrir o projeto (basta abrir `index.html`).
- Checklist (copiar a seção do item 8 preenchida).

### 8. Checklist (colar no README e marcar)

- [ ]  3 páginas mínimas (Home/Sobre/Contato) + links funcionando.
- [ ]  `header`, `nav`, `main`, `footer` usados com propósito.
- [ ]  Hero na página principal
- [ ]  **Tabela** simples presente.
- [ ]  Paleta no `:root` (variáveis CSS).
- [ ]  Google Fonts.
- [ ]  Imagens otimizadas com `alt` descritivo.
- [ ]  README com papéis, paleta, fontes e decisões.
- [ ]  Site no ar.
- [ ]  Vídeo de demonstração.