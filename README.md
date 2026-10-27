# Pseudocódigos — Resumo

Repositório colaborativo para resumos de pseudocódigos.  
O objectivo é que cada membro da equipa documente algoritmos e lógica de programação em pseudocódigo claro e estruturado.

---

## O que é pseudocódigo?

Pseudocódigo é uma descrição de alto nível de um algoritmo, escrita de forma legível por humanos, sem seguir a sintaxe rígida de nenhuma linguagem de programação. É útil para planear soluções antes de as implementar.

### Exemplo

```
INÍCIO
  LER numero
  SE numero > 0 ENTÃO
    ESCREVER "Número positivo"
  SENÃO SE numero < 0 ENTÃO
    ESCREVER "Número negativo"
  SENÃO
    ESCREVER "Zero"
  FIM SE
FIM
```

---

## Estrutura do repositório

```
/resumos/
  ├── algoritmos-basicos/
  ├── estruturas-de-dados/
  ├── ordenacao/
  └── pesquisa/
```

---

## Como contribuir

1. Escolhe uma tarefa em aberto nas [Issues](../../issues)
2. Cria um ficheiro `.md` na pasta adequada
3. Escreve o resumo em pseudocódigo com explicação
4. Faz pull request com o teu resumo

---

## Tarefas disponíveis

Consulta as [Issues](../../issues) para ver as tarefas atribuídas e disponíveis.

---

## Formato recomendado para os resumos

```markdown
# Nome do Algoritmo

## Descrição
Breve explicação do que o algoritmo faz.

## Pseudocódigo
\`\`\`
INÍCIO
  ...
FIM
\`\`\`

## Complexidade
- Tempo: O(n)
- Espaço: O(1)

## Observações
Notas adicionais sobre o algoritmo.
```
