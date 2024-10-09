# Funções em JavaScript

Em JavaScript, as funções são blocos de construção fundamentais. Elas são usadas para agrupar um conjunto de instruções que podem ser chamadas e executadas em qualquer lugar do seu código. As funções podem aceitar argumentos e podem retornar um valor. Aqui está uma explicação detalhada com exemplos:

## Exemplo 1: Função Simples

Uma função simples em JavaScript pode aceitar um ou mais argumentos e retornar um valor. Neste exemplo, a função `saudacao` recebe um argumento `nome` e retorna uma saudação.

```javascript
function saudacao(nome) {
  return "Olá, " + nome + "!";
}

console.log(saudacao("Fabricio")); // Saída: Olá, Fabricio!
```

# Funções em JavaScript - Exemplos Adicionais

Além das funções básicas, vamos explorar mais alguns exemplos interessantes e comuns de uso de funções em JavaScript.

## Exemplo 2: Função sem Retorno

Este exemplo demonstra uma função que executa uma ação (neste caso, exibe uma mensagem no console), mas não retorna nenhum valor.

### Código:

```javascript
function imprimirNumero(num) {
  console.log("O número é: " + num);
}

imprimirNumero(10); // Saída: O número é: 10

