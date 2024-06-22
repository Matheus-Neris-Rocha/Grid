# CSS Grid Fundamentals

Bem-vindo ao resumo de aula "CSS Grid Fundamentals"! Este documento faz parte do curso da Rocketseat, onde exploramos as propriedades fundamentais do CSS Grid, uma poderosa ferramenta para criação de layouts responsivos e flexíveis.

## Propriedades Fundamentais do CSS Grid

Todo grid é composto de dois principais grupos: o **container** (pai) e os **itens** (filhos).

---

### Container (pai)

O elemento pai em um layout de grid é definido como um container, utilizando as seguintes propriedades:

- `display: grid;`
- `grid-template`:
  - `grid-template-columns`: Define as colunas do grid.
  - `grid-template-rows`: Define as linhas do grid.
  - `grid-template-areas`: Define as áreas do grid.

---

### Itens (filhos)

Os itens dentro de um container de grid utilizam as seguintes propriedades:

- `grid-column`:
  - `grid-column-start`: Define o início da coluna.
  - `grid-column-end`: Define o fim da coluna.
- `grid-row`:
  - `grid-row-start`: Define o início da linha.
  - `grid-row-end`: Define o fim da linha.

---

### Propriedades de Alinhamento

Existem 9 propriedades fundamentais para alinhamento no CSS Grid, divididas em 3 grupos:

**Aplicadas no container:**
- `align-content`: Alinha o conteúdo do grid verticalmente.
- `justify-content`: Alinha o conteúdo do grid horizontalmente.
- `place-content`: Atalho para definir `align-content` e `justify-content` ao mesmo tempo.

- `align-items`: Alinha os itens do grid verticalmente.
- `justify-items`: Alinha os itens do grid horizontalmente.
- `place-items`: Atalho para definir `align-items` e `justify-items` ao mesmo tempo.

**Aplicadas nos itens:**
- `align-self`: Alinha o próprio item verticalmente.
- `justify-self`: Alinha o próprio item horizontalmente.
- `place-self`: Atalho para definir `align-self` e `justify-self` ao mesmo tempo.

### Propriedades Auto

Essas propriedades controlam o comportamento automático das linhas e colunas no grid:

- `grid-auto-flow`: Define o fluxo automático do grid.
- `grid-auto-rows`: Define a altura das linhas criadas automaticamente.
- `grid-auto-columns`: Define a largura das colunas criadas automaticamente.

---
