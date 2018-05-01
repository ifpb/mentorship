# Logs of React's mentorship with [Lucas](https://github.com/ifpb/mentorship/blob/master/perfis/mentores/lucas_ferreira.md)

## Students involved:

* [Aaron Santos](https://github.com/ifpb/mentorship/blob/master/perfis/pupilos/aaron_santos.md)
* Bruno Hofmann
* [Mauricio de Lira](https://github.com/ifpb/mentorship/blob/master/perfis/pupilos/mauricio_de_lira.md)
* [Paulo Ferreira](https://github.com/ifpb/mentorship/blob/master/perfis/pupilos/paulo_ferreira.md)

<br>

## Meeting #1 (March 7, 2018)

* Member's introduction
* Explanation and discussion about the working process of the mentorship.
* Some resources to start to study React were shown
* A weekly meetup was scheduled every Tuesday at 4:30 PM

<br>

## Meeting #2 (March 11, 2018)

Some React conpects were shown, such as:

* What is a Component
* Class Component and Functional Component
* Presentational Component and Container Component
* Styles on React (ways of use CSS)
* Props
* State

<br>

## Challenge #1 (March 18, 2018)

Was proposed a small [challenge](https://4q41y03w14.codesandbox.io/) for the pupils train some React basic skills, the challenge consisting in:
1. Create a list of Programming Languages
2. Show them in a Navbar
3. As the user clicks on a specific language, the application will:  
3.1 Through the Github API, obtain a list of the most starred repositories of this language  
3.2 Show some of the repository data on the UI

The idea is that the pupils try to do the challenge so in the next meeting we can comment the code together (through code review)

<br>

## Meeting #3 (March 24, 2018)
First, was solicited for the pupils to explain the concepts seen on the last meeting. The idea is that through an explanation process they can fix more the content.
Were also shown the answers of the Challenge #1, and we commented together the results doing code review.

<br>

## Challenge #2 (March 26, 2018)

Another [challenge](https://6w016xo803.codesandbox.io/) was proposed. This challenge has the goal of make the pupils "learn by doing" some ideas such as comunication between components and how to deal with forms in React.


**Proposal:**
The challenge was inspired in the example from the [Thinking in React](https://reactjs.org/docs/thinking-in-react.html)
section on React oficial docs.

![Challenge image](https://reactjs.org/static/thinking-in-react-mock-1071fbcc9eed01fddc115b41e193ec11-4dd91.png)

The idea is that, from a JSON, a table of products is created, dividing it by name and price.  
JSON:
```json
[
  {category: "Sporting Goods", price: "$49.99", stocked: true, name: "Football"},
  {category: "Sporting Goods", price: "$9.99", stocked: true, name: "Baseball"},
  {category: "Sporting Goods", price: "$29.99", stocked: false, name: "Basketball"},
  {category: "Electronics", price: "$99.99", stocked: true, name: "iPod Touch"},
  {category: "Electronics", price: "$399.99", stocked: false, name: "iPhone 5"},
  {category: "Electronics", price: "$199.99", stocked: true, name: "Nexus 7"}
];
```

Besides that, the application has the following features:
1. An Input that will filter the products by name.
2. An **checkbox** that will filter (or not) just the products that are avaliable in stock.
3. All the products that are not in stock must have their names highlighted by the color red.


### Useful links:

[Thinking in React](https://reactjs.org/docs/thinking-in-react.html)  
[Forms](https://reactjs.org/docs/forms.html)  
[Refs and the DOM](https://reactjs.org/docs/refs-and-the-dom.html)