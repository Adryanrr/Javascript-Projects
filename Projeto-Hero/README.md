## Projeto Hero

Este é um projeto desenvolvido como parte de um desafio proposto pela dio.me. O objetivo do projeto é criar uma classe em JavaScript chamada `Hero` que representa um herói fictício com nome, idade e tipo. Além disso, o herói pode atacar, e o tipo de ataque varia de acordo com o tipo do herói.

### Funcionalidades

- **Classe Hero**: A classe `Hero` possui um construtor que inicializa as propriedades `nome`, `idade` e `tipo` do herói.
  
- **Ataque**: O método `atacar()` da classe `Hero` determina o tipo de ataque com base no tipo do herói e exibe uma mensagem indicando o tipo de ataque realizado.

### Uso

Para utilizar o projeto, basta criar uma instância da classe `Hero` com os parâmetros `nome`, `idade` e `tipo`, e em seguida chamar o método `atacar()` para que o herói realize um ataque.

Exemplo de uso:

```javascript
const meuHeroi = new Hero("Sung", 23, "mago");
meuHeroi.atacar();
````

### Exemplo de Saida 
O Heroi Sung de classe mago atacou usando usou magia!

