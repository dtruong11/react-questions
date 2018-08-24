
What is a React Component? Give an Example.

<details>
  <summary>Answer here</summary>
  A React Component is a function that returns a single react element, a repeatable part of a website. Examples might include a form, navbar, list, list item.
</details>
<br>

## What are the types of React Components and what are pros and cons of each?

<details>
  <summary>Answer here</summary>
  The two types of React Components are Functional versus Stateful Class Components. Functional components are preferred if possible because of simplicity, however Stateful Class Components can be used to manage the state of a particular element if necessary. A recurrent example of a Stateful Class Component is with a Form, where the inputs should be managed by state.
</details>
<br>

## How do we access props?

<details>
  <summary>Answer here</summary>
Props are properties passed down from the parent component. Within a functional component, props are accessed directly with the argument props, or destructured keys of props. Within a stateful class component props are accessed with this.props (after a constructor is built with props as an arguement and super(props){} is within that constructor)
</details>
<br>

## What is the relationship between components in React?

<details>
  <summary>Answer here</summary>
  parent-child relationship tree like relationship where props are passed from the parents and used in the components

</details>
<br>


## When does a component render?

<details>
  <summary>Answer here</summary>
  1. When the state changes
	1. Parent's props changes
	1. Component mounts the first time(when the page loads)

</details>
<br>

## Describe the concept of "state" and the pros and cons of using it.

<details>
  <summary>Answer here</summary>
  1. State are objects that stores the information about a component.
  1. States must be kept simple. States are the objects which determine components rendering and behavior.
  1. accessed by this.state()
  1. pros - powerful, render the components easily with state
  1. cons - can be heavy

</details>
<br>

## What are the differences between html and jsx notation?

<details>
  <summary>Answer here</summary>
  JSX (Java Script XML) allows one to inject javascript into html notation and is used by React to generate more dynamic html. HTML is similar, but does not allow javascript outside of script tags.
</details>
<br>

## Explain the most commonly used react lifecycle methods and when we would use them.

<details>
  <summary>Answer here</summary>
  componendDidMount() - Commonly used to load data with an ajax call. May set state in this method.
  componendWillReceiveProps() - Used to trigger state changes based on changes to particular props. May set state.
</details>
<br>

## What is the difference between using React and not?

<details>
  <summary>Answer here</summary>
  React is a stronger tool when it comes to handeling state; it has an entire lifecycle system that allows your code to be more dynamic and 'react' to changes more efficiently. However, writing your code with a typical MCV model is also efficient depending on how dynamic your pages are.
</details>
<br>

## What is a controlled component? What is an example?

<details>
  <summary>Answer here</summary>
  Controlled component: manages its own state. Form can be constructed as a controlled component.
</details>
