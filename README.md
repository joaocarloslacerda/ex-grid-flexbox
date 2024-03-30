# EXERCÍCIO SOBRE GRID E FLEXBOX

Neste exercício são trabalhados conceitos e técnicas sobre grid e flexbox no CSS para definir todo o layout de um site.

Trabalhando com grid-template-areas foram definidos os espaços em que os campos header, aside, main e footer podem ocupar, e com grid-template-columns e rows os tamanhos que os mesmo tem.

Na parte central, a qual possui uma cor mais avermelhada, foi utilizado flexbox, definindo na parte avermelhada o um flex-direction: column para que fique disposto em colunas e depois na parte azul um flex-direction: row para que fique em linhas.

Os campos aside em verde foram criados dois por cada linhas em azul, desta forma acabam ficando em linha por padrão, devido ao seu container pai estar em linha.

Para que as linhas azuis e os asides em verde fiquem responsivos também, foi definido um flex-grow: 1 , e desta forma eles ocupam todo o espaço dos seus pais de uma forma igualitaria.