
# Funcionalidades da programação
## 2º Desafio - Hiring Coders
### Deploy:https://amazing-curie-329dfb.netlify.app
## Formulario cadastro cliente

* Há doi componentes front end :
* 1º  Cadastro de clientes com salvamento de dados local, que podem ser visualizados no localStorage do Navegador.
* 2º Cadastro de produtos e visualização dos itens cadastrados ou ja adicionados sendo visualizado em outra tela.Onde uma função chama um arquivo html simples para mostrar os dados.


## Linguegens Utilizadas
* JS
* HTML
* CSS

- Nao foi feito o uso de Framework ou Material UI

## Formulario cadastro cliente

Temos um formulario com , lable , campos de input e buttom.

### -----------------------------------------------------------------------------------------------------------
Função: salvarForm (sem retorno )Grava informações do imput no armazenamento local do navegador localstorage
- Verifica se o navegador é compativel com armazenamento local de dados
- "cadastro_" armazena dados eviados para localStorage

## Cadastro de Produtos e estoque

Temos um formulario com , lable , campos de input, buttom,select e imagem.

### -----------------------------------------------------------------------------------------------------------
 Função: validarProduto(idNomeProduto, idCodProduto, idQtidadeProduto)
 Verifica se foram informados o nome e o código do produto
 Parâmetros:
 - idNomeProduto: id do campo que contém o nome do produto
 - idCodProduto: id do campo que contém o código do produto
 - idQtidadeProduto: id do campo que contém a quantidade do produto
 OBS: Se faltar alguma informação (nome ou código do produto) aparecerá uma mensagem de erro. Em caso de 
 sucesso (todas as informações preenchidas), chama a função cadastrarProduto(...)
 Retorno: nenhum
### -----------------------------------------------------------------------------------------------------------

Função: cadastrarProduto(produto, codig, qtidade)
 Cadastra um novo produto (nome, código e quantidade) no estoque
 Parâmetros:
 - produto: nome do produto a ser cadastrado no estoque (Ex: arroz)
 - codig: código do produto a ser cadastrado no estoque (Ex: a01)
 - qtidade: quantidade do produto a ser cadastrado no estoque (Ex: 7)
 OBS: Apos cadastrar o novo produto no estoque, atualiza a quantidade de itens no carrinho, ou seja, chama 
 a função atualizarTotalEstoque()
 Retorno: nenhum

### -----------------------------------------------------------------------------------------------------------

Função: atualizarTotalEstoque(idCampo)
 Incrementa a quantidade de itens cadastrado no estoque (carrinho localizado no canto superior da tela)
 Parâmetros:
 - idCampo: identificador do campo que contem a quantidade de itens no estoque
 Retorno: nenhum
### -----------------------------------------------------------------------------------------------------------

Função: carregarTotalEstoque(idCampo)
 Incrementa a quantidade de itens cadastrado no estoque (carrinho localizado no canto superior da tela)
 Parâmetros:
 - idCampo: identificador do campo que contem a quantidade de itens no estoque
 Retorno: nenhum
### -----------------------------------------------------------------------------------------------------------

Função: function listarEstoque() exibe todos os itens do estoque (nome, código e quantidade)
 Retorno: nenhum
### -----------------------------------------------------------------------------------------------------------
