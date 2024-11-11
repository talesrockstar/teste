# Codigo
Implemente um algoritmo em C para gerenciar um estoque de produtos em uma loja, permitindo o cadastro e a venda de produtos. O programa deve seguir os seguintes passos:  

## Requisitos:
Criação da Matriz:

- Crie uma para armazenar as informações dos produtos:
- ID do produto (inteiro).
- Quantidade em estoque (inteiro).
- Preço do produto (float).

## Cadastro dos Produtos:
Utilize um laço de repetição para preencher a matriz com ID, quantidade e preço para os 10 produtos.
## Menu de Opções:

- Exiba um menu com as seguintes opções:
- Exibir produtos
- Vender produto
- Sair do programa
## Exibição dos Produtos:
- Mostre a lista de produtos no formato:
- ID | Quantidade | Preço
- Se a quantidade de um produto for menor que 3 unidades, exiba "-> Estoque Baixo".
## Venda de Produtos:
- O usuário informa o ID do produto e a quantidade a ser vendida.
- Se houver estoque suficiente, o sistema atualiza a quantidade restante e calcula o valor total da venda:
- Valor da venda = quantidade * preço
- Se o produto estiver , exiba a mensagem: "Estoque esgotado. Venda não permitida."
- Se a quantidade disponível for insuficiente, exiba "Estoque insuficiente."
