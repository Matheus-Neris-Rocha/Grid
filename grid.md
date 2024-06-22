## PROPRIEDADES FUNDAMENTAIS

Todo grid é composto de 2 principais grupos:
`container: o pai` e `itens: o(s) filhos`

---

### CONTAINER (pai)

- diaplay: grid;
- grid-template:
 - grid-template-columns;
 - grid-template-rows;
 - grid-template-areas;

--- 
### ITENS (filhos)

- grid-column;
    - grid-column-start;
    - grid-column-end;
- grid row;
    - grid-row-start;
    - grid-row-end;

--- 
### PROPRIEDADES DE ALINHAMENTO 

Existem 9 propriedades fundamentais

** 6 aplicadas em container **
`align-content`
`justift-content`
`place-content`

`align-items`
`justift-items`
`place-items`

** 3 aplicadas em items **
`align-self`
`justift-self`
`place-self`

Então podemos separar em 3 grupos:
`align`, `justify`, `self`

E cada um deles irá observar ou o 
- conteúdo do elemento `content`
- itens do elemento `items`
- o próprio elemento `self`
--- 

### PROPRIEDADES AUTO

- grid-auto-flow
- grid-auto-rows
- grid-auto-columns


