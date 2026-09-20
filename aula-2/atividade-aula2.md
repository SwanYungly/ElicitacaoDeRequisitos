

## 1. Usuário acompanhar o pedido

### História de usuário
Como usuário, quero acompanhar meu pedido depois da compra, para saber quando ele vai chegar.

### Critérios de aceitação
- **Dado** que fiz um pedido, **Quando** eu abrir meus pedidos, **Então** devo conseguir ver o status dele.
- **Dado** que o restaurante começou a preparar o pedido, **Quando** eu acompanhar o pedido, **Então** deve aparecer que ele está em preparo.
- **Dado** que o entregador saiu com o pedido, **Quando** eu acompanhar o pedido, **Então** deve aparecer que ele saiu para entrega.

---

## 2. Restaurante avisar item indisponível

### História de usuário
Como restaurante, quero marcar um item como indisponível, para que o cliente saiba que ele não pode ser pedido naquele momento.

### Critérios de aceitação
- **Dado** que um item acabou, **Quando** o restaurante marcar ele como indisponível, **Então** o sistema deve atualizar o cardápio.
- **Dado** que um item está indisponível, **Quando** o cliente abrir o cardápio, **Então** ele deve conseguir ver que o item não está disponível.
- **Dado** que o item está indisponível, **Quando** o cliente tentar pedir, **Então** o sistema não deve permitir adicionar esse item.

---

## 3. Entregador reportar um problema

### História de usuário
Como entregador, quero informar um problema durante a entrega, para avisar que aconteceu algum imprevisto.

### Critérios de aceitação
- **Dado** que estou fazendo uma entrega, **Quando** acontecer algum problema, **Então** devo ter uma opção para informar o ocorrido.
- **Dado** que escolhi o problema, **Quando** eu confirmar, **Então** o sistema deve registrar a informação.
- **Dado** que o problema foi registrado, **Quando** o envio for concluído, **Então** o sistema deve avisar sobre o problema.

---

## Priorização MoSCoW

| Ordem | História | Prioridade |

| 1º | Restaurante avisar item indisponível | **Must Have** |
| 2º | Usuário acompanhar o pedido | **Must Have** |
| 3º | Entregador reportar um problema | **Should Have** |

As histórias foram feitas pensando no **INVEST**, tentando manter cada uma simples, útil e possível de testar.
