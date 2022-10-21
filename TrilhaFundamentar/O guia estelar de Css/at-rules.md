# At-rules

* Está relacionado ao comportamento do CSS  
* começa com o sinal de '@' seguido do indentificador e valor

## Exemplos comuns

- @import /* incluir o CSS externo, de outros arquivos por exemplo */

- @media /* regras condicionais para dispositivos(responsividade) */

- @font-face /* fontes externas */
 
- @keyframes /* Animation */

```css
@import url("https://local.com/style.css");

@media (min-width: 500px) {
    /* rules here */
}

@font-face {
    /* rules here */
}

@keyframes nameofanimation {
    /* rules here */
}
```