# 🔒 **Desafio Maskify**

Normalmente, quando você compra algo, é perguntado se seu número de cartão de crédito, número de telefone ou resposta à sua pergunta mais secreta ainda estão corretos. No entanto, como alguém poderia olhar por cima do seu ombro, você não quer que isso seja mostrado na sua tela. Em vez disso, mascaramos isso.

Sua tarefa é escrever uma função chamada "maskify", que muda todos os caracteres, exceto os últimos quatro, para '#'.

📝 **Exemplos (entrada --> saída):**
- "4556364607935616" --> "############5616"
- "64607935616" --> "#######5616"
- "1" --> "1"
- "" --> ""

🔐 **Pergunta Secreta:**
- "Qual era o nome do seu primeiro animal de estimação?"
  - "Skippy" --> "##ippy"
  - "Nananananananananananananananana Batman!" --> "####################################man!"


## Bônus

Que tal criamos mais alguns tipos de mascaramento?!


### Desafio de Mascaramento de Números de Telefone:

Crie uma função que receba um número de telefone como entrada e retorne o número mascarado, exibindo apenas os últimos quatro dígitos.

📝 Exemplo:

```py
Entrada: "123-456-7890"
Saída: "******7890"
```

### Desafio de Mascaramento de CPFs:

Escreva uma função que aceite um CPF como entrada e retorne o CPF mascarado, mostrando apenas os últimos quatro dígitos.

📝 Exemplo:

```py
Entrada: "123.456.789-01"
Saída: "***.***.789-01"
```
