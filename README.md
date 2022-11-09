
# MongoDB Commerce

Este projeto se trata de uma série de 'queries' em arquivos JavaScript para resolver os desafios propostos. Tais quais de alteração, inserção, verificação, criação e deleção de informações em um banco de dados NoSQL (MongoDB)  chamado então de: “commerce”.
O mesmo, possui informações de sanduiches da rede da fast-food McDonald's em uma coleção de “produtos”.


## Demonstração

![ezgif com-gif-maker](https://user-images.githubusercontent.com/99827602/200957468-4897fb05-b38c-454d-b0ae-837b9620c864.gif)

# Requisitos

  Cada requisito possui sua própria query em seu arquivo em ./challenges.
  - Ex.: Requisito 1, corresponde ao desafio1.js
  
<details>
<summary>Funcionalidade de cada query:</summary>
<br>

    1 - Retornar a quantidade de documentos inseridos na coleção `produtos`.

    2 - Ordenar a coleção `produtos` pela quantidade de lanches vendidos em ordem crescente, mostrando apenas o `nome` e a quantidade de lanches `vendidos`
    
    3 - Retornar o lanche mais vendido, mostrando apenas o `nome` e a quantidade do lanche mais vendido
    
    4 - Retornar os lanches que tiveram vendas maiores que `50` e menores que `100`, mostrando apenas o nome e a quantidade de lanches `vendidos` em ordem crescente
    
    5 - Retornar o `nome`, as `curtidas` e `vendidos` dos lanches que tiveram quantidade de `curtidas` igual a `36` ou tenham a quantidade de vendas igual a `85`
    
    6 - Retornar o `nome` e as `curtidas` dos lanches que tiveram curtidas maiores que `10` e menores que `100`
    
    7 - Retornar o `nome` e `vendidos` dos lanches que tenham sido `vendidos` com uma quantidade diferente de `50` e em que o campo `tags` não exista
    
    8 - Deletar os lanches com menos de `50` `curtidas` e retornar o `nome` dos lanches que restaram no banco
    
    9 - Retornar o `nome` de todos os lanches que possuam `calorias` abaixo de `500`
    
    10 - Retornar o `nome` de todos os lanches que tenham o percentual de `proteínas` maior ou igual a `30` e menor ou igual a `40`
    
    11 - Retornar o `nome` do produto, a quantidade de `curtidas` e quantos itens foram `vendidos` dos produtos que não sejam iguais a `Big Mac` e `McChicken`
    
    12 - Adicionar `ketchup` aos `ingredientes` para todos os sanduíches menos o `McChicken`, garantindo que não haja duplicidade nos `ingredientes`
    
    13 - Incluir o campo `criadoPor` em todos os documentos, colocando `Ronald McDonald` no valor desse campo
    
    14 - Retornar todos os lanches que possuem *picles* em seus ingredientes e mostrar apenas os `3` primeiros itens contidos no array `valoresNutricionais`
    
    15 - Adicionar o campo `avaliacao` em todos os documentos da coleção e efetuar alterações nesse campo
    
    16 - Adicionar o campo `ultimaModificacao` com a data corrente somente no sanduíche `Big Mac`
    
    17 - Retornar a quantidade total de produtos em uma nova coleção chamada `resumoProdutos`.
    
    18 - Incluir `bacon` no final da lista de `ingredientes` dos sanduíches `Big Mac` e `Quarteirão com Queijo`
    
    19 - Remover o item `cebola` de todos os sanduíches
    
    20 - Remover o primeiro `ingrediente` do sanduíche `Quarteirão com Queijo`
    
    21 - Remover o último `ingrediente` do sanduíche `Cheddar McMelt`
    
    22 - Adicionar a quantidade de vendas dos sanduíches por dia da semana
    
    23 - Insirir os valores `combo` e `tasty` no _array_ `tags` de todos os sanduíches e deixar os valores em ordem alfabética ascendente (A a Z)
    
    24 - Ordenar em todos os documentos os valores do _array_ `valoresNutricionais` pelo campo `percentual` de forma decrescente
    
    25 - Adicionar o valor `muito sódio` ao final do _array_ `tags` nos produtos em que o `percentual` de `sódio` seja maior ou igual a `40`
    
    26 - Adicionar o valor `contém sódio` ao final do _array_ `tags` nos produtos em que o `percentual` de `sódio` seja maior do que `20` e menor do que `40`
    
    27 - Contar quantos produtos contém `Mc` no nome, sem considerar letras maiúsculas ou minúsculas
    
    28 - Contar quantos produtos têm `4` ingredientes
    
    29 - Renomear o campo `descricao` para `descricaoSite` em todos os documentos
    
    30 - Remover o campo `curtidas` do item `Big Mac`
    
    31 - Retornar o `nome` dos sanduíches em que o número de `curtidas` é maior que o número de sanduíches `vendidos`
    
    32 - Retornar o `nome` e a quantidade de vendas (`vendidos`) dos sanduíches em que o número de vendas é múltiplo de `5`
    
</details>

## Stack utilizada

**Back-end:** MongoDB, Docker


## Autor

- [@thales-sz](https://www.github.com/thales-sz)

