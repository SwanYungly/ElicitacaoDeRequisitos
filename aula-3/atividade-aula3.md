

## História 1

**Como cliente, quero avaliar o pedido depois da entrega, para ajudar outros clientes a escolherem melhor.**

### Critérios de aceitação

- **Dado** que o pedido foi entregue, **quando** o cliente abre o app, **então** aparece a opção de avaliar o pedido.
- **Dado** que o cliente avalia com nota e comentário, **quando** confirma o envio, **então** a avaliação aparece no perfil do restaurante.

### Requisitos não funcionais

1. A tela de avaliação deve carregar em até 2 segundos.  
   **Característica ISO/IEC 25010:** Eficiência de desempenho.

2. A tela de avaliação deve ser simples e fácil de entender.  
   **Característica ISO/IEC 25010:** Usabilidade.

3. A avaliação enviada pelo cliente não deve ser perdida em caso de falha do sistema.  
   **Característica ISO/IEC 25010:** Confiabilidade.

---

## História 2

**Como cliente, quero salvar um cartão de pagamento, para não digitar os dados a cada compra.**

### Critérios de aceitação

- **Dado** que o cliente cadastra um cartão válido, **quando** confirma o cadastro, **então** o cartão fica disponível para escolha no checkout.
- **Dado** que o cliente tem um cartão salvo, **quando** faz um novo pedido, **então** pode selecionar esse cartão sem redigitar os dados.

### Requisitos não funcionais

1. Os dados do cartão devem ser protegidos e não podem ficar visíveis para outras pessoas.  
   **Característica ISO/IEC 25010:** Segurança.

2. O cartão salvo deve aparecer rapidamente na tela de pagamento.  
   **Característica ISO/IEC 25010:** Eficiência de desempenho.

3. A opção de escolher um cartão salvo deve ser fácil de usar.  
   **Característica ISO/IEC 25010:** Usabilidade.

---

## História 3

**Como dono de restaurante, quero ver um resumo diário de vendas, para acompanhar o desempenho do dia.**

### Critérios de aceitação

- **Dado** que o dia comercial termina, **quando** o restaurante abre o painel de vendas, **então** vê o total de pedidos e o faturamento do dia.
- **Dado** que o restaurante seleciona um período diferente, **quando** aplica o filtro, **então** o resumo é recalculado para aquele período.

### Requisitos não funcionais

1. O resumo de vendas deve carregar em até 3 segundos.  
   **Característica ISO/IEC 25010:** Eficiência de desempenho.

2. As informações de vendas devem continuar corretas mesmo após uma falha ou reinício do sistema.  
   **Característica ISO/IEC 25010:** Confiabilidade.

3. O painel deve ser organizado e fácil de entender.  
   **Característica ISO/IEC 25010:** Usabilidade.
