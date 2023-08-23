# LP1

public class TrocaVariaveis {
    public static void main(String[] args) {
        int A = 10;
        int B = 20;

        int C = A;
        A = B;
        B = C;

        System.out.println("Valor de A: " + A);
        System.out.println("Valor de B: " + B);
    }
}
```

Saída:

```
Valor de A: 20
Valor de B: 10
```

Teste de mesa:

Para os valores 32, 150 e 3:

| Variáveis | X  | Y   | Z   | Resposta |
|-----------|----|-----|-----|----------|
| Valor     | 32 | 150 | 3   |          |
| Passo 1   |    |     |     |          |
| Passo 2   |    |     |     |  f        |
| Passo 3   |    |     |     |          |
| Passo 4   |    |     |     |          |
| Passo 5   |    |     |     |          |
| Passo 6   |    |     |     |          |
| Passo 7   |    |     |     |          |
| Passo 8   |    |     |     |          |

Para os valores 7, -1 e -2:

| Variáveis | X | Y | Z | Resposta |
|-----------|---|---|---|----------|
| Valor     | 7 | -1| -2|          |
| Passo 1   |   |   |   |          |
| Passo 2   |   |   |   |          |
| Passo 3   |   |   |   |          |
| Passo 4   |   |   |   |          |
| Passo 5   |   |   |   |          |
| Passo 6   |   |   |   |          |
| Passo 7   |   |   |   |          |
| Passo 8   |   |   |   |          |

Para os valores 5, 50 e 3:

| Variáveis | X | Y  | Z | Resposta |
|-----------|---|----|---|----------|
| Valor     | 5 | 50 | 3 |          |
| Passo 1   |   |    |   |          |
| Passo 2   |   |    |   |          |
| Passo 3   |   |    |   |          |
| Passo 4   |   |    |   |          |
| Passo 5   |   |    |   |          |
| Passo 6   |   |    |   |          |
| Passo 7   |   |    |   |          |
| Passo 8   |   |    |   |          |

Vamos preencher o quadro passo a passo:

Para os valores 32, 150 e 3:

| Variáveis | X  | Y   | Z   | Resposta |
|-----------|----|-----|-----|----------|
| Valor     | 32 | 150 | 3   |          |
| Passo 1   | 32 | 150 |     |          |
| Passo 2   | 32 | 150 | 4835|          |
| Passo 3   | 32 | 150 | 4835|          |
| Passo 4   | 32 | 150 | 4835|          |
| Passo 5   | 32 | 150 | 4835|          |
| Passo 6   | 32 | 150 | 4835|          |
| Passo 7   | 32 | 150 | 4835|          |
| Passo 8   | 32 | 150 | 4835|   C      |

Para os valores 7, -1 e -2:

| Variáveis | X | Y | Z | Resposta |
|-----------|---|---|---|----------|
| Valor     | 7 | -1| -2|          |
| Passo 1   | 7 | -1|     |          |
| Passo 2   | 7 | -1|  -2 |          |
| Passo 3   | 7 | -1|  -2 |          |
| Passo 4   | 7 | -1|  -2 |          |
| Passo 5   | 7 | -1|  -2 |          |
| Passo 6   | 7 | -1|  -2 |          |
| Passo 7   | 7 | -1|  -2 |          |
| Passo 8   | 7 | -1|  -2 |   A      |

Para os valores 5, 50 e 3:

| Variáveis | X | Y  | Z | Resposta |
|-----------|---|----|---|----------|
| Valor     | 5 | 50 | 3 |          |
| Passo 1   | 5 | 50 |     |          |
| Passo 2   | 5 | 50 | 255 |          |
| Passo 3   | 5 | 50 | 255 |          |
| Passo 4   | 5 | 50 | 255 |          |
| Passo 5   | 5 | 50 | 255 |          |
| Passo 6   | 5 | 50 | 255 |          |
| Passo 7   | 5 | 50 | 255 |          |
| Passo 8   | 5 | 50 | 255 |   B      |

