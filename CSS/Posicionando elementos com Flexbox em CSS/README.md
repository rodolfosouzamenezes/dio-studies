# O que é o Flex Box?
É um modelo de layout unidimencional e um método que pode oferecer distribuição de espaço entre itens em uma interface e recursos de alinhamento.

## Flex Container
É a tag que envolve os itens e onde nós iremos aplicar a propriedade __"display: flex"__, transformando todos os seus filhos em Flex Itens.

## Propriedades relacionadas ao Flex Container

- __display:__ é o inicializador do container
- __flex-direction:__ define o direcionamento dos flex itens
- __flex-wrap:__ define se haverá quebra de linha
- __flex-flow:__ é um atalho para as propriedades flex-direction e flex-wrap
- __justify-content:__ define o alinhamento dos itens de acordo com a sua direção
- __align-items:__ alinha os itens de acordo com o seu eixo do conteiner
- __align-content:__ alinha as linhas do container

## Propriedades relacionadas ao Flex Item
- __flex-grow:__ define o fator de crescimento 
- __flex-basis:__ define o tamanho inicial que um item deve ter antes que o espaço ao seu redor seja distribuído
- __flex-shrink:__ define a proporção com que um item deve encolher caso seja necessário 
- __flex:__ é um atalho para as propriedades flex-grow, flex-basis e flex-shrink
- __order:__ define a ordem do item
- __align-self:__ define o alinhamento de um item especifico de um item