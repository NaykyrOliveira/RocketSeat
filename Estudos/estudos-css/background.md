## Background

- Define um fundo para o nosso elemento
- Sua área de atuação é a caixa toda
- Por padrão, é transparente

### Exemplos 

- Usar cores sólidas
- Usar imagens
- Controlar
    - a posição das imagens
    - se elas se repetem ou não
    - o tamanho delas na caixa
- Usar cor e imagem juntas
- Usar cor gradiente

### Background-color

# HTML

<header>
        
</header>
        
<main>
    <h1>Evolua rápido com a tecnologia.</h1>
    <p>Junte-se a milhares de devs e acelere na direção dos seus objetivos.</p>
</main>
    

# CSS

* {
    margin: 0;
}

header {
    height: 100px
    border: 7px solid red;
    background-color: aqua; /* cor de fundo */
    background-image: url(unsplash.com); /* imagem no fundo */
    background-repeat: no-repeat; 
    background-repeat: repeat-y; /* Repetição horizontal */
    background-repeat: repeat-x: /* Repetição vertical */

    /* Por padrão ela se repete tanto na vertical quanto na horizontal */

    background-position: right center; /* de onde vai iniciar a imagem(top / bottom) left é o padrão*/
}