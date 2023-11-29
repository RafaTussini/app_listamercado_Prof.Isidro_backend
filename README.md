# app_listamercado_Prof.Isidro_backend
Repositoria da API da lista de mercado, feito em Java com SpringBoot. 

# Sistema lista de mercado
## Requisitos 
- Ser capaz de gerenciar varias listas de mercado (e marcar o seu status como concluida ou não);
- Ser capaz de cadastrar produtos e consulta-los;
- Ser capaz de incluir produtos nas listas e especificar suas quantidades e marcar se o item ja foi comprado ou não;
- Ser capaz de atribuir valores aos itens comprados, para depois ter uma gestão dos custos das listas;
- Ser capaz de adicionar quantidades (kg, quantidades, litros, etc.);


## Casos de uso - Produto
### Cadastrar produtos:
informar o nome de um determinado produtor e o sistema o armazena no banco de dados.
### Consultar produtor: 
informar palavras chaves para consultar ou mesmo buscar produtos a partir de uma lista. 
### Alterar dados de produtos: 
Basicamente alterar o nome do produto/item e ter sua efetivação no banco de dados.

## Casos de uso - Lista
### Criação de listas: 
Criar uma nova lista inserindo a data e o local onde foi feita a compra (supermercado, feira, etc).
### Apagar uma lista: 
Remover uma lista que foi criada por engano, e remover todos os seus intens que foram criados.
### Inserção de itens na lista:
Criar um item associado a uma lista e a um produto, bem como deixar desponivel a possibilidade de modificar quantidade e preço que foi pago.
### Alteração de itens da lista:
Alterar apenas quantidade, preço pago e status.
### Remoção de itens da lista: 
poder remover um item que foi cadastrado na lista.
### Fechamento da lista:
Concluir a lista como sendo completa e gerar seu custo total a partir dos itens comprados. 
