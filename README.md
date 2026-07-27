# LojaDeInformatica
Trabalho semestral - ETEC

FEITO POR: Yasmin Batista de Oliveira e Maria Eduarda

LOJA DE INFORMÁTICA: LojEtec

OBJETIVO PRINCIPAL: Melhorar a visualização e gerenciamento dos itens faltantes ou não no estoque da loja  e facilitar as negociações com os fornecedores 

TECNOLOGIAS UTILIZADAS: c# e MySQL

DESCRIÇÃO BÁSICA DO PROJETO: Um sistema em c# com banco de dados integrado que organizará os produtos disponíveis e não disponíveis no estoque da loja

REQUISITOS FUNCIONAIS: 
Permissões do sistema:
  cadastro de produtos e categorias;        
  editar as informações de um produto ou categoria;
  excluir produtos ou categorias;
  consultar produtos por nome, código ou categoria;
  associar cada produto a uma categoria;
  associar cada produto a um fornecedor;

Gerenciamento do estoque:
  registrar entradas de produtos no estoque;
  registrar saídas de produtos do estoque;
  atualizar a quantidade disponível após cada movimentação;
  impedir a retirada de produtos quando a quantidade em estoque for insuficiente;
  solicitar compra;

Fornecedores: 
  cadastrar fornecedores;
  ditar os dados dos fornecedores;
  excluir fornecedores;

Relatórios:
  exibir a lista de produtos cadastrados;
  informar produtos com estoque baixo;

Controle de acesso:
Logins:
  funcionários, fornecedores e administradores realizem login utilizando usuário e senha;
  impedir o acesso quando as credenciais forem inválidas;
  cadastro de funcionários;
  cadastro de administradores;
  ativar ou desativar usuários;
  editar as informações dos usuários;

Permissões:
  possuir três níveis de acesso: Funcionário, Fornecedor e Administrador;
  administrador deve possuir acesso a todas as funcionalidades do sistema;
  funcionário poderá consultar produtos, registrar entradas e saídas de estoque e visualizar relatórios;
  fornecedor poderá consultar apenas os produtos vinculados ao seu cadastro e atualizar seus próprios dados;
  apenas administradores poderão cadastrar, editar ou excluir produtos;
  Apenas administradores poderão cadastrar, editar ou excluir usuários;
  
  




Requisitos não funcionais: 
