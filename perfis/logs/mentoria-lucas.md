# Logs da Mentoria de React com [Lucas](https://github.com/ifpb/mentorship/blob/master/perfis/mentores/lucas_ferreira.md)

## Alunos envolvidos:

* [Aaron Santos](https://github.com/ifpb/mentorship/blob/master/perfis/pupilos/aaron_santos.md)
* Bruno Hofmann
* [Mauricio de Lira](https://github.com/ifpb/mentorship/blob/master/perfis/pupilos/mauricio_de_lira.md)
* [Paulo Ferreira](https://github.com/ifpb/mentorship/blob/master/perfis/pupilos/paulo_ferreira.md)

<br>

## Reunião #1 (07/04/2018)

* Apresentação dos integrantes
* Explicação e discussão sobre o funcionamento do processo da mentoria.
* Mostrado alguns materiais para começar a estudar sobre React
* Formação das "duplas" inicias para pair programming
* Foi marcado uma reunião semanal todas as terças a partir das 16h30

<br>

## Reunião #2 (11/04/2018)

Foram apresentados alguns conceitos de React como:

* O que é um Componente
* Class Component e Functional Component
* Presentational Component e Container Component
* Estilização no React (formas de usar CSS)
* Props
* State

<br>

## Desafio #1 (18/04/2018)

Foi proposto um pequeno [desafio](https://4q41y03w14.codesandbox.io/) para os pupilos treinarem algumas skills básicas do React, o desafio consiste em:
1. Criar uma lista de linguagens de programação
2. Mostrar essas linguagens em uma navbar
3. Conforme o usuário clique em uma linguagem, a aplicação irá:  
3.1 Através da API do Github, obter a lista dos repositórios com mais Stars dessa linguagem  
3.2 Mostrar esses dados organizados na UI

A idéia é que os pupilos tentem fazer o desafio para que na nossa próxima reunião comentarmos junto os códigos (code review).

<br>

## Reunião #3 (24/04/2018)

Primeiramente foi solicitado aos pupilos explicar os conceitos vistos na reunião anterior, a idéia é que através de uma explicação eles consigam fixar mais os conteúdos.
Também foram mostrados as respostas do Desafio #1, e comentamos juntos os resultados fazendo code review.

<br>

## Desafio #2 (26/04/2018)

Outro [desafio](https://6w016xo803.codesandbox.io/) foi proposto, esse desafio tem o objetivo de fazer os pupilos aprenderem na prática a idéia de comunicação entre componentes e também como lidar com formulários no React.


**Proposta:**
O desafio foi inspirado no exemplo da sessão [Thinking in React](https://reactjs.org/docs/thinking-in-react.html) da documentação oficial.

![Imagem do desafio](https://reactjs.org/static/thinking-in-react-mock-1071fbcc9eed01fddc115b41e193ec11-4dd91.png)

A idéia é que a partir de um JSON seja criado uma tabela de produtos, dividindo por nome e preço.  
JSON:
```js
[
  {category: "Sporting Goods", price: "$49.99", stocked: true, name: "Football"},
  {category: "Sporting Goods", price: "$9.99", stocked: true, name: "Baseball"},
  {category: "Sporting Goods", price: "$29.99", stocked: false, name: "Basketball"},
  {category: "Electronics", price: "$99.99", stocked: true, name: "iPod Touch"},
  {category: "Electronics", price: "$399.99", stocked: false, name: "iPhone 5"},
  {category: "Electronics", price: "$199.99", stocked: true, name: "Nexus 7"}
];
```

Além disso, a aplicação terá as seguintes features:
1. Um Input que irá filtrar os produtos por nome
2. Uma caixa de **checkbox** que irá filtrar (ou não) apenas os produtos que estão no Estoque.
3. Todos os produtos que não estão no Estoque deverão ter seu nome destacados pela cor vermelha.


Links úteis:
[Thinking in React](https://reactjs.org/docs/thinking-in-react.html)
[Forms](https://reactjs.org/docs/forms.html)
[Refs and the DOM](https://reactjs.org/docs/refs-and-the-dom.html)