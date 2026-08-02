# LojEc
- Sistema de gerenciamento de uma loja de informática
  
## AUTORAS:
- Yasmin Batista de Oliveira
-  Maria Eduarda.

## TEMA ESCOLHIDO:
- Loja de Informática.

## NOME DO PROJETO: 
- LojEc.

## OBJETIVO PRINCIPAL:
- Melhorar a visualização e o gerenciamento de itens disponíveis e indisponíveis no estoque da loja,
 além de facilitar negociações com fornecedores.

## TECNOLOGIAS UTILIZADAS:
- C# 
- MySQL.

## DESCRIÇÃO DO PROJETO:
O projeto consiste em um sistema desenvolvido em C# com integração com o MySQL, que auxilia na organização, gerenciamento e visualização de produtos disponíveis e 
indisponíveis no estoque de uma loja de informática (LOJEC).

<br>
<br>

# REQUISITOS FUNCIONAIS:

<br>

## PERMISSÕES

 - Cadastrar produtos e categorias;

 - Editar as informações de produtos e categorias;

 - Excluir produtos e categorias;

 - Consultar produtos por nome, código ou categoria;

 - Associar cada produto a uma categoria;

 - Associar cada produto a um fornecedor;
  
<br>

## GERENCIAMENTO DE ESTOQUE

 - Registrar entradas de produtos no estoque;

 - Registrar saídas de produtos do estoque;

 - Atualizar a quantidade disponível após cada movimentação;

 - Impedir a retirada de produtos quando a quantidade no estoque for insuficiente;

 - Solicitar compra de produtos;
  
<br>

## FORNECEDORES

 - Cadastrar fornecedores;

 - Editar os dados dos fornecedores;

 - Excluir fornecedores;
  
  <br>
  
## RELATÓRIOS

 - Exibir a lista de produtos cadastrados;

 - Informar produtos com estoque baixo;
  
<br>

  ## LOGIN

 - Permitir que funcionários, fornecedores e administradores realizem login utilizando usuário e senha;

 - Impedir o acesso quando as credenciais forem inválidas;

 - Cadastrar funcionários;

 - Cadastrar administradores;

 - Ativar ou desativar usuários;

 - Editar as informações dos usuários;
  
<br>

## PERMISSÕES

 - Possuir três níveis de acesso: Funcionário, Fornecedor e Administrador;

 - O administrador deve possuir acesso a todas as funcionalidades do sistema;

 - O funcionário poderá consultar produtos, registrar entradas e saídas de estoque e visualizar relatórios;

 - O fornecedor poderá consultar apenas os produtos vinculados ao seu cadastro e atualizar seus próprios dados;

 - Apenas administradores poderão cadastrar, editar ou excluir produtos;

 - Apenas administradores poderão cadastrar, editar ou excluir usuários;

<br>
<br>

# REQUISITOS NÃO FUNCIONAIS

<br>

## DESEMPENHO

 - Responder às consultas em até 2 segundos para bases de dados de pequeno porte;

 - Manter bom desempenho durante operações simultâneas de consulta;
  
  <br>
  
## SEGURANÇA

 - Exigir autenticação antes do acesso às funcionalidades;

 - Armazenar as senhas dos usuários de forma segura;

 - Utilizar consultas parametrizadas para evitar SQL Injection;

 - Restringir as funcionalidades de acordo com o perfil do usuário autenticado;


<br>

## USABILIDADE E DISPONIBILIDADE
- Interface simples, intuitiva e de fácil utilização.

- Sistema sempre disponível durante todo o horário de funcionamento da loja.

- O código deverá seguir boas práticas de programação.

- Código organizado em camadas (Interface, Lógica de Negócio e Banco de Dados), facilitando futuras manutenções.

- O sistema deverá permitir a inclusão de novas funcionalidades sem necessidade de reconstrução completa.

- Manter um padrão visual em todas as telas, utilizando cores, botões e menus consistentes para facilitar a navegação.

- Deverá funcionar em computadores com sistema operacional Windows 10 ou superior.


<br>
<br>
<br>

#Diagrama de Caso e Uso
<div aling="center">
<img src="https://github.com/yaya-heloi-de-oliveira/LojaDeInform-tica/issues/1#issue-5042837629" width="700px"/>
</div>

