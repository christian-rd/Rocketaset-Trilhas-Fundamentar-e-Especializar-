# Comentários

* Não irá afetar o seu código
* Ajuda a lembrar blocos de códigos
* Deixa dicas para leitura
* Ajuda outros a entenderem
* Nunca esqueça de fechar um comentário aberto

Comentários começam com /* e termina com */

´´´css

/*Básico*/
/*-----------------------*/
body {
    font: 1em/150% Helvetica, Arial, sans-serif;
    padding: 1em;
    margin: 0 auto;
    max-width: 33em;
}

@media (min-width: 70em) {
    /*comentario*/
    body {
        font-size: 130%
    }
}

/* Elementos específicos */
/* ----------------------------- */
div p, #id:first-line {
    background-color: red;
    border-radius: 3px
}

div p {
    padding: 1em;
}

div p + p{
    padding-top: 0;
}

* Você podera usar para desabilitar parte do seu código

/*
.special {
    color: red;
}
*/