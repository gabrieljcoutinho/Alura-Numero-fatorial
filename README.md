# Projeto: Função Fatorial em JavaScript

## Descrição
Este projeto implementa uma função para cálculo do fatorial de um número inteiro não negativo utilizando recursão em JavaScript.

O fatorial de um número `n` (representado por `n!`) é definido como:

- n! = n × (n - 1) × (n - 2) × ... × 1
- Casos base:
  - 0! = 1
  - 1! = 1

---

## Objetivo
Demonstrar o uso de recursão, controle de fluxo e operações matemáticas básicas em JavaScript por meio de um exemplo simples e didático.

---

## Código-fonte

```javascript
const fatorial = function f(num) {
    if (num === 0 || num === 1) return 1;
    return num * f(num - 1);
}

console.log(fatorial(5));
