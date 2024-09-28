# 🛠️ Projeto: Desenvolvimento de Habilidades com Map, Reduce, Filter e ForEach

Este projeto foi desenvolvido como parte do curso **JavaScript Pt.4 - Front End Club**. O objetivo principal é aprimorar minhas habilidades no uso dos métodos de array mais utilizados em JavaScript: `map()`, `reduce()`, `filter()` e `forEach()`. Esses métodos são essenciais para manipulação e transformação de arrays de maneira eficiente e são amplamente utilizados em desenvolvimento front end.

## 🚀 Tecnologias Utilizadas

- **JavaScript**: Linguagem de programação utilizada para aplicar lógica de manipulação de arrays.
- **HTML5**: Estrutura básica do projeto para visualização dos resultados.
- **CSS3**: Para estilização simples da página.

## 🎯 Objetivo do Projeto

O objetivo deste projeto é praticar e entender a aplicação dos métodos mais comuns para manipulação de arrays em JavaScript. Cada um desses métodos possui funcionalidades distintas e é ideal para resolver diferentes tipos de problemas no desenvolvimento de aplicações web.

## 💡 Funcionalidades do Projeto

- **`map()`**: Cria um novo array com os resultados da chamada de uma função para cada elemento do array original.
- **`filter()`**: Filtra os elementos de um array com base em uma condição especificada, retornando apenas os elementos que atendem a essa condição.
- **`reduce()`**: Reduz o array a um único valor (acumulador), utilizando uma função callback que processa cada elemento.
- **`forEach()`**: Executa uma função em cada elemento do array sem retornar um novo array, sendo ideal para realizar operações sem a necessidade de transformar o array original.

## 📋 Exemplos Práticos

### `map()`
```javascript
const numeros = [1, 2, 3, 4];
const dobrados = numeros.map(num => num * 2);
console.log(dobrados); // [2, 4, 6, 8]
```

### `filter()`
```javascript
const idades = [12, 25, 36, 45, 50];
const maioresDe30 = idades.filter(idade => idade > 30);
console.log(maioresDe30); // [36, 45, 50]
```

### `reduce()`
```javascript
const numeros = [1, 2, 3, 4];
const somaTotal = numeros.reduce((acumulador, valorAtual) => acumulador + valorAtual, 0);
console.log(somaTotal); // 10
```

### `forEach()`
```javascript
const frutas = ['maçã', 'banana', 'laranja'];
frutas.forEach(fruta => console.log(fruta));
// maçã
// banana
// laranja
```

## 📝 O que Aprendi

- Como aplicar os métodos `map()`, `reduce()`, `filter()` e `forEach()` de forma prática e eficiente.
- A importância de escolher o método correto para a tarefa adequada.
- Como os métodos ajudam a manipular e transformar arrays de maneira funcional e simplificada, facilitando o desenvolvimento de código mais legível e modular.

## 🛠️ Como Executar o Projeto

1. Clone este repositório: 
   ```bash
   git clone https://github.com/seu-usuario/projeto-js-metodos.git
   ```
2. Abra o arquivo `index.html` em seu navegador para visualizar os exemplos na prática.

---
![image](https://github.com/user-attachments/assets/bf47d0b8-e212-4014-bc4c-f5bdb870fa2e)

