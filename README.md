# Controle de Gastos Diário

Página simples que calcula quanto você pode gastar por dia no mês, baseado no que você recebeu e já gastou.

## Como funciona

```
Dinheiro restante = Entrada - Saídas fixas - Saídas do cartão de crédito
Gasto por dia = Dinheiro restante / Dias do mês
```

## Como usar

Abra o arquivo [`index.html`](index.html) diretamente no navegador. Não há dependências nem build — é um único arquivo HTML.

## Campos

- **Entrada**: quanto você recebeu no mês.
- **Saídas fixas**: aluguel, contas, assinaturas, etc.
- **Saídas do cartão de crédito**: gastos da fatura do cartão.
- **Dias do mês**: quantidade de dias para dividir o valor restante.

## Próximos passos

- Salvar histórico por mês
- Separar gastos do cartão em itens/parcelas
- Adicionar categorias às saídas fixas
- Persistência em banco de dados
