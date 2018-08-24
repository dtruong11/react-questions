## In what situation would it make the most sense to impliment Redux into a React project?
<details>
  <summary>Answer here</summary>
  When managing state of individual components becomes too costly or time-consuming. Using Redux allows you to combine all relevant state information into a store that one can access anywhere in the project. Ideal for large projects.
</details>
<br>

## What are the three principles of Redux?
<details>
  <summary>Answer here</summary>
  -Single source of truth
  -State is read-only
  -Changes are made with pure functions
</details>
<br>

## Describe how data flows through a Redux project.
<details>
  <summary>Answer here</summary>
  -Component triggers action
  -Action sends command to reducer (or model, then reducer)
  -Reducer uses action command to update the store
  -The store update triggers the Provider component to re-render the project
</details>
<br>

## What is an action creator and what type of information does it send?
<details>
  <summary>Answer here</summary>
  Action creators generate objects with a type key that specifies a specfic action be done to the state/store and can also contain information with with the reducer will implement into the store/state.
</details>
<br>

## Explain the role of a reducer.
<details>
  <summary>Answer here</summary>
  Reducers are pure functions that specify how the application's state changes in response to an action. The return the newest version of state.
</details>
<br>

## Explain the role of thunk.
<details>
  <summary>Answer here</summary>
  Thunk is a middleware that make asynchronous actions possible in Redux. Thunk can be utilized to connect a back-end database to a redux store through promises.
</details>
<br>

## What is the purpose of the Provider component and where is it implimented?
<details>
  <summary>Answer here</summary>
  Passes the store into the project making it accessible to the components within. Implimented by wrapping around App
</details>
<br>