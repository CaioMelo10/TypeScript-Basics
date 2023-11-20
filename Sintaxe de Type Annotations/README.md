# TypeScript - Exemplo Básico

Este é um exemplo básico de código em TypeScript, mostrando alguns conceitos fundamentais da linguagem.

## Tipos Básicos

No TypeScript, é possível declarar tipos para variáveis. Aqui estão alguns exemplos:

```typescript
let nome: string = 'Luiz';
let idade: number = 0b1010;
let adulto: boolean = true;
let simbolo: symbol = Symbol('qualquer-symbol');
```

`nome`: Uma variável do tipo string que armazena o valor 'Luiz'.
`idade`: Uma variável do tipo número que armazena o valor binário 0b1010, equivalente a 10 em decimal.
`adulto`: Uma variável do tipo boolean que armazena o valor verdadeiro (true).
`simbolo`: Uma variável do tipo símbolo que armazena um símbolo com a descrição 'qualquer-symbol'.

# Arrays

Exemplos de declaração de arrays em TypeScript:

```typescript
let arrayDeNumeros: Array<number> = [1, 2, 3];
let arrayDeNumeros2: number[] = [1, 2, 3];
let arrayDeStrings: Array<string> = ['a', 'b'];
let arrayDeStrings2: string[] = ['a', 'b'];
```

`arrayDeNumeros` e `arrayDeNumeros2`: Arrays contendo números.
`arrayDeStrings` e `arrayDeStrings2`: Arrays contendo strings.


# Objetos

Exemplo de declaração de um objeto:

```typescript
let pessoa: {nome: string, idade: number, adulto?: boolean} = {
  idade: 30,
  nome: 'Luiz'
};
```

`pessoa`: Um objeto com propriedades `nome` (string), `idade` (number) e `adulto` (opcional, boolean).

# Funções

Exemplos de declaração de funções em TypeScript:

```typescript
function soma(x: number, y: number): number {
  return x + y;
}


const soma2: (x: number, y: number) => number = (x, y) => x + y;

```
`soma`: Uma função que recebe dois parâmetros do tipo número e retorna a soma.
`soma2`: Uma função arrow equivalente à função `soma`.

## Espero que isso ajude! Se tiver mais alguma dúvida ou precisar de esclarecimentos adicionais, estou à disposição.