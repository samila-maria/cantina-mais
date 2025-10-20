# Ator: Funcionário
# Objetivo do funcionário: Atender pedidos
# Descrição: Atender os pedidos dos clientes

# Fluxo principal:
# 1 - O pedido vai na tela do funcionário
# 2 - O funcionário vai olhar os pedidos e atender o cliente
# 3 - O funcionário vai marcar o pedido como concluído e por a hora de entrega





# Ator: Funcionário
# Objetivo do funcionário: Por o cardápio no aplicativo
# Descrição: Por o cardápio no aplicativo para os clientes verem e pedirem

# Fluxo principal:
# 1 - Terá uma tela de cadastro de lanche
# 2 - O funcionário vai olhar a lista de cadastro e por um novo lanche no cardápio
# 3 - O funcionário vai ficar atento para quando um cliente fizer um pedido





# Ator: Funcionário / Cliente
# Objetivo do funcionário / Cliente: Fazer login no sistema
# Descrição: O funcionário / cliente deve se cadastrar informando seu e-mail e senha

# Fluxo principal:
# 1 - Terá uma tela de login para o funcionário / cliente informar o e-mail e senha para entrar
# 2 - O funcionário / cliente vai logar com seu e-mail e senha

# Fluxos Alternativos:
# E-mail / Senha incorretos: Se o e-mail ou senha estiverem incorretos aparecerá uma mensagem de erro





# Ator: Cliente
# Objetivo do Cliente: Visualizar o cardápio 
# Descrição: Cliente visualizar o cardápio para fazer o pedido

# Fluxo principal:
# 1 - Terá uma tela de cardápio com a exibição dos lanches disponiveis
# 2 - O cliente vai olhar o cardápio e fazer o pedido do lanche de sua preferência
# 3 - O funcionário receberá uma notificação quando o cliente realizar o pedido





# Ator: Cliente
# Objetivo do Cliente: Realizar pagamento antes do pedido
# Descrição: Ao receber o pedido realizar o pagamento do lanche se for dinheiro em espécie

# Fluxo principal:
# 1 - O cliente deve escolher se quer realizar o pagamento com dinheiro em espécie quando receber o lanche ou pagar antes de receber com pix ou cartão
# 2 - Caso o cliente escolha pagar com pix ou cartão abrir a tela de pagamento

# Fluxo alternativo: Caso o cliente não tenha saldo suficiente na conta para pagar, o aplicativo não vai efetuar a compra e o pedido será cancelado





# Ator: Sistema
# Objetivo do Sistema: Permitir o pedido de lanches
# Descrição: Permitir o pedido de lanches e identifica-los

# Fluxo principal:
# 1 - O cliente deve realizar o pedido do lanche
# 2 - Se o cliente efetuar o pagamento o sistema vai autorizar e gerar um código de identificação
# 3 - O pedido será enviado para os funcionários





# Ator: Sistema
# Objetivo do Sistema: Gerar o feedback do pedido
# Descrição: Gerar o feedback do lanche, do tempo de busca e da forma de pagamento usada

# Fluxo principal:
# 1 - Terá uma tela para o feedback
# 2 - O cliente vai avaliar como foi atendimento
# 3 - O sistema vai avaliar o cliente de acordo com tempo de busca e da forma de pagamento usada