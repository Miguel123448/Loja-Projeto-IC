# IC - Projeto da 1ª Avaliação

## 1. Objetivo

Criar um site estático institucional (apenas HTML e CSS) para uma marca fictícia à escolha do trio (ex.: cafeteria, estúdio de design, ONG, clínica, entre outros), focado em HTML semântico, CSS organizado e acessibilidade básica.

## 2. Regras e escopo

**Tecnologias**: apenas HTML5 + CSS3 (sem frameworks; permitido Google Fonts e ícones via CDN).

**Estrutura dos arquivos (no mínimo 3 arquivos .html)**

```bash
/projeto/
  index.html
  sobre.html (sugestão)
  contato.html
  /assets/
    /img/  (otimizar tamanhos)
    /css/
      styles.css
 README.md

```

- **Sem JavaScript** (menus e efeitos devem ser possíveis com CSS).
- **Sem construtores prontos** (Wix/WordPress etc.).

## 3. Páginas obrigatórias

1. **Home (index.html)**
- Hero* com Título, subtítulo e botão/âncora.
- Barra de navegação com links para todas as páginas.
- Destaques em **cards** (mín. 3) em **flex**.

*Hero: Essa seção na página inicial costuma apresentar uma imagem ou vídeo impactante, um título conciso, um texto persuasivo e uma chamada para ação (CTA) que guia o visitante para as próximas etapas desejadas no site. 

1. **Sobre/Serviços/Produtos (sobre.html)**
- Seções com títulos hierárquicos (`<h1>…<h3>`).
- Lista (ordenada ou não) e uma **tabela simples** (ex.: planos, preços, agenda).

1. **Contato (contato.html)**
- Endereço fictício + mapa .

## 4. Requisitos HTML mínimos

**Semântica**: usar `header`, `nav`, `main` e `footer`.
**Acessibilidade básica**:

- Texto alternativo em imagens (`alt`).
- Ordem lógica de títulos (sem pular do `h1` para `h4`).

**Links internos** funcionando e **breadcrumb** simples em páginas internas (opcional).

## 5. Requisitos CSS mínimos

**Tipografia**: declarar 1–2 fontes via Google Fonts 

**Cores**: paleta com 4 cores principais (definir em `:root` com variáveis CSS).

**Layout**: usar **Flexbox** 

**Boas práticas**: evitar `!important`, evitar inline-style, usar classes.

## 6. Conteúdo

Criar uma **identidade mínima** (nome, slogan, paleta, ícones).

Todos os textos devem ser **autênticos** (nada de *Lorem ipsum* puro na entrega final).

## 7. Entregáveis pelo Google Classroom

- **Link** do repositório do Github com toda a estrutura solicitada.
- **Link** para um vídeo de 1 minuto no máximo mostrando a navegação do site e apontando 3 decisões de design/código tomadas pela equipe.
- **Link** do site ativo (Github Pages, Vercel ou qualquer outra ferramenta)

Obs: No repositório o arquivo **README.md** (obrigatório) deve conter:

- Título do projeto + 1 parágrafo de descrição.
- Autores (trio) e papéis (quem cuidou de quê).
- Paleta de cores (hexadecimal) + fontes usadas.
- Como abrir o projeto (basta abrir `index.html`).
- Checklist (copiar a seção do item 8 preenchida).
     
# IC - UrbanStyle
- [x]  3 páginas mínimas (Home/Sobre/Contato) + links funcionando.
- [x]  `header`, `nav`, `main`, `footer` usados com propósito.
- [x]  Hero na página principal
- [x]  **Tabela** simples presente.
- [x]  Paleta no `:root` (variáveis CSS).
- [x]  Google Fonts.
- [x]  Imagens otimizadas com `alt` descritivo.
- [x]  README com papéis, paleta, fontes e decisões.
- [x]  Site no ar.
- [ ]  Vídeo de demonstração.

## Urban Style (Descrição)
A Urban Style é uma marca fictícia de moda urbana que criamos para representar atitude, autenticidade e a identidade das ruas. A ideia foi desenvolver um site institucional moderno, limpo e fácil de navegar, que mostrasse o estilo e a identidade da marca.
O projeto foi feito apenas com HTML5 e CSS3, sem frameworks, focando em semântica, acessibilidade e um design responsivo que se adapta bem em qualquer tela do celular ao computador.

## Paleta de cores (hex)
- `--cor-primaria: #1E1E1E`
- `--cor-secundaria: #F5F5F5`
- `--cor-destaque: #E63946`
- `--cor-texto: #333333`

## Fontes
- Títulos: Poppins (Google Fonts)
- Texto: Open Sans (Google Fonts)
  
## Como abrir
Basta abrir `index.html` no navegador ou acessar o deployment do github.

## Papéis
- **Dev 1: Miguel Pereira – Header, footer e página sobre.
- **Dev 2: João Ricardo – CSS e cards.
- **Dev 3: Saulo Eduardo – Design, Main e otimização de imagens.

Todos revisaram o código uns dos outros (garantir consistência).
