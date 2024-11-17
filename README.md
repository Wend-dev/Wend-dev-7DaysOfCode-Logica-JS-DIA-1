# Comparação de Variáveis em JavaScript

Este projeto demonstra como comparar variáveis em JavaScript considerando valores e tipos, utilizando operadores de igualdade (`==`) e igualdade estrita (`===`).

## Descrição

O código realiza as seguintes tarefas:
- Compara variáveis numéricas e strings que possuem valores iguais ou diferentes.
- Verifica se os tipos das variáveis são iguais ou diferentes.
- Imprime mensagens adequadas com base nos resultados das comparações.

## Código

```javascript
let numeroUm = 1;
let stringUm = '1';
let numeroTrinta = 30;
let stringTrinta = '30';
let numeroDez = 10;
let stringDez = '10';

if (numeroUm == stringUm && typeof numeroUm !== typeof stringUm) {
  console.log('As variáveis numeroUm e stringUm têm o mesmo valor, mas tipos diferentes');
} else {
  console.log('As variáveis numeroUm e stringUm não têm o mesmo valor');
}

if (numeroTrinta === stringTrinta) {
  console.log('As variáveis numeroTrinta e stringTrinta têm o mesmo valor e mesmo tipo');
} else {
  console.log('As variáveis numeroTrinta e stringTrinta não têm o mesmo tipo');
}

if (numeroDez == stringDez && typeof numeroDez !== typeof stringDez) {
  console.log('As variáveis numeroDez e stringDez têm o mesmo valor, mas tipos diferentes');
} else {
  console.log('As variáveis numeroDez e stringDez não têm o mesmo valor');
}
