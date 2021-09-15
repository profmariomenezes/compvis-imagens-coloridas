# CompVis Imagens Coloridas

Repositório para a atividade de CompVis - Imagens Coloridas

## Exercícios de Fixação

1. Utilize duas imagens coloridas diferentes e refaça os processamentos que fizemos nos notebooks anteriores para explorar os conceitos de imagens coloridas. As imagens devem estar no espaço de cores RGB para estas operações.

    a. Transformações de Intensidade (equalização e normalização)

    b. Filtros Espaciais (filtro de suavização e de aguçamento)

    c. Filtros de Frequência (filtro passa baixa Butterworth e filtro passa-alta Gaussiano)
    
    Para cada processamento, documente os resultados obtidos, indicando se são coerentes ou não.

2. Utilize a função `skimage.color.convert_colorspace` e explore os processamentos nos espaços de cor "RGB" e "HSV". Repita os processamentos da questão 1.

3. Compare os resultados dos processamentos feitos no espaço de cor 'RGB' e 'HSV' e com as imagens convertidas para *nível de cinza*. Explique os resultados obtidos.

### Exercício de implementação

Implemente uma função de conversão de espaço de cor RGB para HSV conforme apresentado no livro texto (Gonzalez & Woods, capítulo 6.) Compare (demonstre) o resultado da sua função com as funções da biblioteca `skimage.color.convert_colorspace`
