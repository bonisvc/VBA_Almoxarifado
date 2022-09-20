# VBA_Almoxarifado

## Visão Geral
  Essa é a primeira aplicação VBA que fiz na minha vida. Muito script pode ser simplificado, agregado, e muita poluição visual no código pode ser consertado. No momento a ferramenta está em utilização e é funcional, portanto não haverá atualizações do código, devido também a outras demandas mais urgentes. Porém, tão logo seja possível, tornarei os códigos mais limpos e adequados às boas práticas de programação.

## Objetivo
  Funções para automação da planilha de fluxo de materiais do almoxarifado, contendo, ainda, cadastro de fornecedores, cadastro de produtos e cadastro de clientes internos (colaboradores permitidos a requisitarem ao Almoxarifado)

## Descrição
  A planilha de Gestão do Almoxarifado utiliza formulários para facilitar a inserção dos dados e conta com algumas abas separando Fornecedores, Clientes Internos, Cadastro de Materiais, Movimentação de Materiais e um painel aonde é possível agregar todas as funções de manipulação de qualquer uma das três planilhas.
  Existe um caminho a ser seguido, para que não haja inconsistência:
  
> Não é possível dar entrada/saída em materiais que não tenham sido previamente cadastrados

> Não é possível dar saída em materiais sem discriminar o cliente interno que fez a requisição

> Não é possível dar entrada em materiais sem discriminar de qual fornecedor o material foi comprado

## Reprodução
  O script é muito simples e qualquer usuário de nível básico pode desenvolver algo parecido, porém, caso haja reprodução desse código em sua íntegra, peço por gentileza que seja dado o crédito.

## Permissão
  Apesar de não haver informações delicadas a respeito do cliente para o qual essa automação foi criada, houve permissão por parte da empresa para que houvesse o registro dessas informações aqui no GitHub, evitando, assim, violar qualquer critério de confidencialidade.

## Sugestões
  Aceito sugestões para melhorias no meu script, tanto para performance da ferramenta, quanto para atender às melhores práticas.
