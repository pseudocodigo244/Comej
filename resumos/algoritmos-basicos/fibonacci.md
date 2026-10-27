# Fibonacci

## Descrição
Produz uma sequência onde cada número é a soma dos dois anteriores.  
Sequência: 0, 1, 1, 2, 3, 5, 8, 13, 21, ...

---

## Pseudocódigo — Versão Iterativa

```
INÍCIO
  LER n
  SE n = 0 ENTÃO
    ESCREVER 0
  SENÃO SE n = 1 ENTÃO
    ESCREVER 1
  SENÃO
    a ← 0
    b ← 1
    PARA i DE 2 ATÉ n FAZER
      c ← a + b
      a ← b
      b ← c
    FIM PARA
    ESCREVER b
  FIM SE
FIM
```

## Pseudocódigo — Versão Recursiva

```
FUNÇÃO fibonacci(n)
  SE n = 0 ENTÃO
    RETORNAR 0
  SENÃO SE n = 1 ENTÃO
    RETORNAR 1
  SENÃO
    RETORNAR fibonacci(n - 1) + fibonacci(n - 2)
  FIM SE
FIM FUNÇÃO
```

---

## Complexidade
| Versão     | Tempo  | Espaço |
|------------|--------|--------|
| Iterativa  | O(n)   | O(1)   |
| Recursiva  | O(2^n) | O(n)   |

---

## Exemplo passo a passo

**Entrada:** n = 5

**Iterativo:**
```
a=0, b=1
i=2 → c=1, a=1, b=1
i=3 → c=2, a=1, b=2
i=4 → c=3, a=2, b=3
i=5 → c=5, a=3, b=5
```
**Saída:** 5
