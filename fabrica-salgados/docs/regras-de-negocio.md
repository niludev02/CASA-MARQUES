# Regras de Negócio

RN001 - Um cliente deve possuir ID, nome, endereço e telefone para ser cadastrado.
/
RN002 - Um cliente pode realizar vários pedidos.
RN003 - Um cliente com mais de 10 compras poderá receber um desconto de 10%.
RN004 - Produtos inativos não devem aparecer no cardápio.
RN005 - Um produto pode pertencer a apenas uma categoria.
RN006 - Produtos não podem se misturar entre categorias.
RN007 - Um pedido deve possuir pelo menos um produto.
RN008 - Um pedido pode possuir vários produtos.
RN009 - Um pedido só pode ser concluído com uma forma de pagamento válida.
RN010 - Um pedido só é entregue quando o cliente informar o código de entrega.
RN011 - Um pedido só poderá ser marcado como "Entregue" após ter sido marcado como "Saiu para entrega".
RN012 - Um pedido pode ser marcado como "Atrasado" na produção ou na entrega; por exemplo, se permanecer por mais de 5 minutos no estado "Em preparo".
RN013 - Um pedido pode ser realizado sem que o cliente possua cadastro prévio.
RN014 - Um pedido pode ser agendado para uma data futura, sujeito à disponibilidade de produção.
RN015 - A taxa de entrega é calculada com base no bairro e na distância entre o estabelecimento e o cliente.
RN016 - Um pedido só pode ser aceito para bairros cadastrados como atendidos.
RN017 - Pedidos feitos após o horário limite do dia devem ser processados apenas no próximo dia útil (ou conforme a produção).
RN018 - Uma encomenda só pode entrar em produção após a confirmação do pagamento.
RN019 - Um pedido de pronta-entrega/delivery pode ter o pagamento confirmado no momento da entrega.
RN020 - Um produto pode ter múltiplas variações de tamanho/gramatura, cada uma com preço próprio.
RN021 - Um combo deve conter pelo menos dois itens (produto e/ou bebida).
RN022 - O dashboard administrativo pode ser acessado pela equipe do negócio e pelo desenvolvedor.
