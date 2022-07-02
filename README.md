# freeCodeCamp-Tribute-Page

Projeto para certificado de progresso do novo curso de Responsive Web Design feito pelo freeCodeCamp.

Usando conceitos de acessibilidade, flexbox, tipografia e box model aprendidos no módulo. Além de outros elementos de HTML e CSS.

Screenshots: https://i.imgur.com/UMcTTcn.png (1ª parte) https://i.imgur.com/R8vLqvv.png (2ª parte) https://i.imgur.com/PP3j9iw.png (3ª parte)

original site by freeCodeCamp: https://tribute-page.freecodecamp.rocks/

## Meu Processo:

### Construído com:

- HTML5
- Elementos básicos de CSS

### Notas Adicionais:

- A minha intepretação com esse projeto foi de chegar o mais próximo possível do resultado original, porém sem ler o código do site ou qualquer direcionamento/dicas disponibilizado pelo site. Por isso, não me ative as cores ou tamanhos exatamente iguais.
- Porém, a partir desse projeto foi introduzido o design style guide (https://design-style-guide.freecodecamp.org/), no qual irei me basear.
- É importante determinar a width e height (ou ao menos saber) de todos os elementos, pois ajuda também a definir margins e heights de parents e childrens.

### Problemas encontrados enquanto fazia o projeto:

- Não há margin da direita e esquerda entre a figure e a imagem em si quando ela está em uma resolução menor. ✅ Resolvido ao ajustar width e height da imagem para ser mais responsivo (width 100% e height auto) e após isso botar um padding no elemento figure.
- o tamanho da figure em uma resolução menor aumenta muito. ✅ Também resolvido ao ajustar o width e height e usar display block ao invvés de flex.
- Não consegui achar uma maneira para alinhar os elementos da lista e a frase em itálico da mesma maneira em que está no site original.
- aparentemente o tamanho da section sobre a vida dele está errado, e por isso não é possível formatar da maneira correta.
