# pizzaria

```mermaid

classDiagram
class Pagamento
    Pagamento: -Long id
    Pagamento: -Long pedidoId
    Pagamento: -String formaPagamento
    Pagamento: -Double valorPago
    Pagamento: -Double troco
    Pagamento: -LocalDateTime dataHoraPagamento
    
    Pagamento: +Pagamento(Long pedidoId, String formaPagamento, Double valorPago)
    Pagamento: +getTroco() Double
    Pagamento: +setTroco(Double troco) void
```