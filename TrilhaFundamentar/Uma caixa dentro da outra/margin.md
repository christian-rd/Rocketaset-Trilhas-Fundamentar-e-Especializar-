## margin

Espaços entre os elementos

- margin-top | margin-right | margin-bottom | margin-left
- values: `<length>` | `<percentage>`| auto

```css
div {
    /* shorthand */
            /*encima, direita, embaixo, esquerda*/
    margin: 12px 16px 10px 4px;
            /*encima, laterais, embaixo*/
    margin: 12px 16px 0;
            /*horizontal e vertical*/
    margin: 8px 16px;
           /*todas as margem*/
    margin:8px
}
```

    * Cuidado com margin collapsing (top se ajunta ao bottom)