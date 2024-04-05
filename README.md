# Bateria eletrônica midi web

---
## Projeto
O programa consiste em um layout midi de bateria eletrônica que reproduz sons ao clique ou pressionar de certos botões do teclado.

![texto alternativo](https://github.com/caioabueno/js_p_paginas_dinamicas/blob/main/images/visaogeral.jpg)

Nesse curso alguns recursos da linguagem foram abordados, como:  
* Seleção de elemetos via queryselector
* Utilização de funções nativas do JavaScript
* Estrutura de loop, condicional e funções
* Eventos
* Template String
* Função anônima
* Manipulação de elementos no DOM
---
## Mais a respeito dos recursos

### 1. Implementação Inicial dos Sons
Abordou-se a estrutura básica de um teclado de bateria, com botões associados a diferentes sons.
Foi utilizada a função onclick para reproduzir o som correspondente a cada botão.

### 2. Boas Práticas e Seleção de Elementos
Enfatizou-se a importância de evitar a repetição de código ao selecionar e manipular elementos no DOM.
Introduziu-se o uso do querySelectorAll para selecionar todos os botões de forma eficiente e a criação de uma constante (listaDeTeclas) para armazenar esses elementos.

### 3. Iteração e Implementação Generalizada
Introduziu-se o conceito de iteração com while para aplicar a lógica de associação entre os botões e os sons de forma mais eficiente, evitando repetições de código.

### 4. Utilização de Template String e Otimização do Código
Usando template strings no JavaScript, ajustou-se a associação dos botões com os sons de maneira dinâmica e flexível.
Otimizou-se a lógica de iteração, substituindo o while por um loop for.

### 5. Adição de Eventos de Teclado
Explorou-se a interação do teclado com o site, permitindo que as teclas 'Enter' e 'Space' acionassem os botões da mesma forma que o clique do mouse, melhorando a usabilidade do site.

### 6. Melhorias na Função tocaSom e Experiência do Usuário
Realizou-se uma melhoria na função tocaSom, adicionando validações para evitar erros ao passar elementos inválidos ou inexistentes.
Também destacou-se a importância de alterar a aparência dos botões ao serem pressionados via teclado para uma experiência de usuário mais consistente.

*Este é um projeto do curso da plataforma de ensino **[Alura](http:alura.com.br)***
