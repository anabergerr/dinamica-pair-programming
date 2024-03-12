# Desafio de Identificação do Emissor do Cartão de Crédito:

Implemente uma função que, dada uma sequência numérica correspondente ao número do cartão de crédito, determine a bandeira do cartão (Visa, Mastercard, American Express, etc.).

Para facilidar, use essa base de dados:

```py
bancos = {
    "Visa": {
        "prefixo": ["4"],
        "tamanho": [13, 16]
    },
    "Mastercard": {
        "prefixo": ["51", "52", "53", "54", "55"],
        "tamanho": [16]
    },
    "American Express": {
        "prefixo": ["34", "37"],
        "tamanho": [15]
    },
    # Adicione mais bandeiras conforme necessário
}
```

📝 Exemplo:

```py
Entrada: "4532756279624063"
Saída: "Visa"
```
