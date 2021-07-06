# flexbox-minefield

le 11 juillet 2021

## Introduction

Apprentissage sur les flexbox.

## Mise en oeuvre

En Html:
Découpage en 8 articles dans une section qui commprennent 8 div.
Chaque div contient une class différente par rapport aux éléments désirés.
Les icones proviennent de "https://fontawesome.com/v5.15/icons/bomb?style=solid"

<article class="ligne7">
        <button><div class="relief"></div></button>
        <div class="bombe"><i class="fas fa-bomb"></i></div>
        <div class="bombe"><i class="fas fa-bomb"></i></div>
        <div class="bombe"><i class="fas fa-bomb"></i></div>
        <button><div class="relief"></div></button>
        <div class="trois">3</div>
        <button><div class="relief">2</div></button>
        <button><div class="relief">1</div></button>
    </article>

En CSS:

Au niveau des articles, j'ai utilisé display: flex;
                                     flex-direction: row;
                                     justify-content: center;

Pour chaque div, j'ai utilisé       display: flex;
                                    align-items: center;
                                    justify-content: center;

Pour dévoiller certaines cases, j'ai utilisé 
button {
    border: inset 1px #DCDCDC;
    width: 4.7rem;
    height: 4.7rem;
    font-size: 2rem;
}
.relief {
    opacity: 0;
    border: dottend 1px white;
}
.relief:hover {
    opacity: 100%;
    border: unset;

}
button:hover {
    background-color: white;
    border: dotted 2px #DCDCDC;
}

## Lien 

https://engie-paquot.github.io/flexbox-minefield/

