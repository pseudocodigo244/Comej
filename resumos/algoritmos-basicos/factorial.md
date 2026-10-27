# Factorial

## Descrição
Calcula o produto de todos os números inteiros positivos de 1 até n.  
Exemplo: 5! = 5 × 4 × 3 × 2 × 1 = 120

---

## Pseudocódigo — Versão Iterativa

```
INÍCIO
  LER n
  resultado ← 1
  PARA i DE 1 ATÉ n FAZER
    resultado ← resultado × i
  FIM PARA
  ESCREVER resultado
FIM
```

## Pseudocódigo — Versão Recursiva

```
FUNÇÃO factorial(n)
  SE n = 0 OU n = 1 ENTÃO
    RETORNAR 1
  SENÃO
    RETORNAR n × factorial(n - 1)
  FIM SE
FIM FUNÇÃO
```

---

## Complexidade
| Versão     | Tempo | Espaço |
|------------|-------|--------|
| Iterativa  | O(n)  | O(1)   |
| Recursiva  | O(n)  | O(n)   |

---

## Exemplo passo a passo

**Entrada:** n = 4

**Iterativo:**
```
i=1 → resultado = 1 × 1 = 1
i=2 → resultado = 1 × 2 = 2
i=3 → resultado = 2 × 3 = 6
i=4 → resultado = 6 × 4 = 24
```
**Saída:** 24
