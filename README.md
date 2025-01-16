# pizzaria

```mermaid

classDiagram
class Pagamento
    Pagamento: -Long id
    Pagamento: -Long pedidoId
    Pagamento: -String formaPagamento
    Pagamento: -Double valorPago
    Pagamento: -Double troco
    Pagamento: -Date dataHoraPagamento
    
    Pagamento: +Pagamento(Long pedidoId)
    Pagamento: +processarPagamento(String formaPagamento, Double valorTotal, Double valorPago)
```