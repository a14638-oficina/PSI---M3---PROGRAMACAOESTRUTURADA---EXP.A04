# PSI---M3---PROGRAMACAOESTRUTURADA---EXP.A04

<h1> Introdução </h1>
O código implementa um sistema de gestão de pedidos para registar, consultar, atualizar, exibir e eliminar pedidos de manutenção, utilizando um menu interativo. O sistema armazena as informações de cada pedido em um dicionário.
Problema
O código precisa permitir ao usuário gerenciar pedidos de manutenção de maneira eficiente. Isso inclui registrar novos pedidos, consultar o status de pedidos existentes, atualizar seu estado e eliminar pedidos.
<h1>Requisitos </h1>
O código deve:
Registar pedidos com uma descrição e um estado inicial de "Pendente".
Consultar pedidos pelo ID, exibindo a descrição e o estado.
Atualizar o estado de um pedido, permitindo opções como "Pendente", "Em Andamento" ou "Concluído".
Exibir todos os pedidos com seu ID, descrição (limitada a 15 caracteres) e estado.
Eliminar pedidos com base no ID, removendo o pedido do sistema.
<h1>Estrutura do Código (Python) </h1>
Funções:

registar_pedido(pedidos):

Registra um novo pedido, solicitando uma descrição do problema e atribuindo um estado inicial de "Pendente". O ID do pedido é gerado automaticamente com base no número de pedidos existentes.
consultar_pedido(pedidos):

Permite consultar um pedido pelo ID. Se encontrado, exibe a descrição e o estado do pedido.
atualizar_estado(pedidos):

Permite atualizar o estado de um pedido existente. O estado pode ser "Pendente", "Em Andamento" ou "Concluído". Verifica se o novo estado é válido.
exibir_pedidos(pedidos):

Exibe uma lista de todos os pedidos com seu ID, descrição (limitada a 15 caracteres) e estado.
eliminar_pedido(pedidos):

Permite eliminar um pedido com base no seu ID. Se o pedido existir, ele é removido do dicionário.
Função Principal (main()):

Exibe um menu interativo, permitindo ao usuário escolher a operação desejada (registrar, consultar, atualizar, exibir ou eliminar pedidos).
O programa continua executando até que a opção de "Sair" seja escolhida.
Fluxo de Execução:

O programa apresenta um menu que permite ao usuário realizar diferentes operações com os pedidos. A cada escolha, a função correspondente é chamada para gerenciar os pedidos.
O sistema encerra quando o usuário escolhe a opção "Sair".
