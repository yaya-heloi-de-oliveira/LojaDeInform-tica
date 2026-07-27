## LojEc

**AUTORAS:**
Yasmin Batista de Oliveira e Maria Eduarda.

**NOME DO PROJETO:** LojEc.

**OBJETIVO PRINCIPAL:**
Melhorar a visualização e o gerenciamento de itens disponíveis e indisponíveis no estoque da loja, além de facilitar negociações com fornecedores.

**TECNOLOGIAS UTILIZADAS:**
C# e MySQL.

**DESCRIÇÃO DO PROJETO:**
O projeto consiste em um sistema desenvolvido em C# com integração como MySQL, que auxilia na organização, gerenciamento e visualização de produtos disponíveis e indisponíveis no estoque de uma loja de informática (LOJEC).

<br>

## REQUISITOS FUNCIONAIS:

<br>

**PERMISSÕES**

  Cadastrar produtos e categorias;

  Editar as informações de produtos e categorias;

  Excluir produtos e categorias;

  Consultar produtos por nome, código ou categoria;

  Associar cada produto a uma categoria;

  Associar cada produto a um fornecedor;
  
<br>

**GERENCIAMENTO DE ESTOQUE**

  Registrar entradas de produtos no estoque;

  Registrar saídas de produtos do estoque;

  Atualizar a quantidade disponível após cada movimentação;

  Impedir a retirada de produtos quando a quantidade no estoque for insuficiente;

  Solicitar compra de produtos;
  
<br>

**FORNECEDORES**

  Cadastrar fornecedores;

  Editar os dados dos fornecedores;

  Excluir fornecedores;
  
  <br>
  
**RELATÓRIOS**

  Exibir a lista de produtos cadastrados;

  Informar produtos com estoque baixo;
  
<br>

  **LOGIN**

  Permitir que funcionários, fornecedores e administradores realizem login utilizando usuário e senha;

  Impedir o acesso quando as credenciais forem inválidas;

  Cadastrar funcionários;

  Cadastrar administradores;

  Ativar ou desativar usuários;

  Editar as informações dos usuários;
  
<br>

**PERMISSÕES**

  Possuir três níveis de acesso: Funcionário, Fornecedor e Administrador;

  O administrador deve possuir acesso a todas as funcionalidades do sistema;

  O funcionário poderá consultar produtos, registrar entradas e saídas de estoque e visualizar relatórios;

  O fornecedor poderá consultar apenas os produtos vinculados ao seu cadastro e atualizar seus próprios dados;

  Apenas administradores poderão cadastrar, editar ou excluir produtos;

  Apenas administradores poderão cadastrar, editar ou excluir usuários;

<br>

## REQUISITOS NÃO FUNCIONAIS

<br>

**DESEMPENHO**

  Responder às consultas em até 2 segundos para bases de dados de pequeno e médio porte;

  Manter bom desempenho durante operações simultâneas de consulta;
  
  <br>
  
**SEGURANÇA**

  Exigir autenticação antes do acesso às funcionalidades;

  Armazenar as senhas dos usuários de forma segura;

  Utilizar consultas parametrizadas para evitar SQL Injection;

  Restringir as funcionalidades de acordo com o perfil do usuário autenticado;
