# Requisitos Funcionais

- RF001 - O sistema deve permitir que o cliente acesse o cardápio online através de um link enviado a ele.
- RF002 - O sistema deve permitir o atendimento humano, com uma mensagem de permissão tanto para atendimento online via link quanto para atendimento humano.
- RF003 - O sistema deve permitir que o cliente visualize o cardapio com os produtos organizados por categorias.
- RF004 - O sistema deve permitir adicionar os produtos ao carrinho do pedido.
- RF005 - O sistema deve permitir alterar a quantidade dos produtos no carrinho.
- RF006 - O sistema deve calcular automaticamente o preço total dos pedidos dinamicamente.
- RF007 - O sistema deve permitir que o cliente informe nome, endereço e telefone.
- RF008 - O sistema deve permitir que o cliente possa informar o CEP para preencher o endereço automaticamente.
- RF009 - O sistema deve permitir que o usuário escolha a forma de pagamento.
- RF010 - O sistema deve registrar o pedido no banco de dados.
- RF011 - O dashboard deve exibir novos pedidos em tempo real.
- RF012 - O painel da cozinha deve atualizar automaticamente quando um novo pedido for recebido.
- RF013 - O sistema deve mostrar o estado do pedido na conversa do Whatsapp.
- RF014 - O sistema deve permitir que o cozinheiro altere o estado do pedido.
- RF015 - O sistema deve atualizar o estado a cada edição.
- RF016 - O sistema deve enviar um código de entrega ao cliente.
- RF017 - O sistema deve validar a entrega concluída.
- RF018 - O sistema deve permitir o uso das informações de conta para o acesso à página do dashboard.
- RF019 - O sistema deve permitir a visualização da página do dashboard somente para administradores.
- RF020 - O sistema deve permitir a alteração de estados, cardápio, nomes e preços dos produtos.
- RF021 - O sistema deve permitir promoções quando o cliente retornar e comprar um número determinado de vezes, verificando o histórico de compras associado ao telefone.
- RF022 - O sistema deve permitir que o cliente faça pedidos sem necessidade de cadastro prévio.
- RF023 - O sistema deve permitir que o cliente agende pedidos/encomendas para uma data futura.
- RF024 - O sistema deve calcular a taxa de entrega com base no bairro/distância do endereço do cliente.
- RF025 - O sistema deve restringir o atendimento de entrega a uma lista de bairros previamente cadastrados.
- RF026 - O sistema deve impedir o recebimento de novos pedidos após um horário limite definido pela produção.
- RF027 - O sistema deve permitir o cadastro de observações no pedido (ponto de referência, retirada de ingredientes, troco, etc.).
- RF028 - O sistema deve permitir a criação de combos promocionais (individuais e familiares) vinculando múltiplos produtos.
- RF029 - O sistema deve permitir cadastrar variações de tamanho/gramatura para um mesmo produto, cada uma com preço próprio.
- RF030 - O sistema deve exigir confirmação do pagamento antes de liberar o pedido para produção, no caso de encomendas.
- RF031 - O sistema deve permitir que a equipe registre a confirmação manual de pagamentos recebidos.
- RF032 - O sistema deve emitir/imprimir a comanda do pedido para a cozinha.
- RF033 - O sistema deve exibir na TV/painel da cozinha o nome do cliente, número do pedido, itens e horário de cada pedido.
- RF034 - O sistema deve permitir que a equipe altere o status do pedido entre os estados: Recebido, Em preparo, Pronto, Saiu para entrega, Entregue, Cancelado, Atrasado, Aguardando pagamento e Pago.
- RF035 - O sistema deve enviar mensagens automáticas via chatbot do WhatsApp a cada mudança relevante de status (recebido, em preparo, pronto).
- RF036 - O sistema deve enviar uma mensagem automática ao cliente via WhatsApp quando o pedido entrar em atraso ou for cancelado, informando o motivo.
- RF037 - O sistema deve permitir a geração de relatórios de vendas em formato PDF.
- RF038 - O sistema deve permitir múltiplos níveis de acesso ao dashboard (equipe e desenvolvedor).

# Requisitos Não Funcionais

- RNF001 - O sistema deve ser desenvolvido utilizando Laravel.
- RNF002 - O banco de dados deverá ser PostgreSQL.
- RNF003 - O sistema deverá ser responsivo para dispositivos móveis.
- RNF004 - O dashboard deverá exigir autenticação.
- RNF005 - O sistema deverá manter backup periódico do banco de dados.
- RNF006 - O código deverá ser organizado seguindo o padrão MVC do Laravel.
- RNF007 - O sistema não poderá salvar dados como CPF, RG ou dados pessoais.
- RNF008 - O sistema deve suportar volume inicial de aproximadamente 5 a 10 pedidos/dia, com capacidade de escalar conforme o crescimento do negócio.
- RNF009 - O sistema deve ser projetado para suportar expansão futura para múltiplos pontos/unidades de atendimento.
RNF010 - A integração com WhatsApp deve suportar o envio e recebimento automatizado de mensagens (chatbot).

