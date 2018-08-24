
<h2> React Router Questions </h2>
<br>

What is the difference between using Route components exclusively versus Route components within a Switch statement? 
<details>
  <summary>Answer here</summary>
  Using route components exclusively causes all routes that match the specified path to render whereas within a switch statement only the first route to match the path loads. Example would be route with path /profiles and route with path /:user. Given a path of /profiles using routes exclusively  both would render whereas within a switch only the first would load.
  </details>
<br>

Follow up question, how can you use exact to minimize this difference? What is an example of where it would help, and when it would not?
<details>
  <summary>Answer here</summary>
  Exact, when true, will match if the path matches exactly. It can minimize the difference between using Switch components versus Routes exclusively by making the specified path more exclusive. Ex. of when it would help with /profile and /profile/:id. Would not help with /profile and /:user
</details>
<br>

What is a technique to protect a particular route, where would our verify function be best used?
<details>
  <summary>Answer here</summary>
  We can place authorization check/ verify within the render function of a particular route, loading the route only if the user is verified or sending them back to login if unverified
</details>
<br>


Discuss how we can use higher order components for authorization of particular routes. What are the benefits of making such a higher order component.
<details>
  <summary>Answer here</summary>
  We can create a "helper" component that takes the same props as a Route component. Within the higher order component we apply the props to a Route component but add authorization within the render function. The benefits would be the ability to reuse the helper component across your project, instead of applying authorization to each route component
</details>
<br>

Discuss how we can use higher order components for authorization of particular routes. What are the benefits of making such a higher order component.
<details>
  <summary>Answer here</summary>
  We can create a "helper" component that takes the same props as a Route component. Within the higher order component we apply the props to a Route component but add authorization within the render function. The benefits would be the ability to reuse the helper component across your project, instead of applying authorization to each route component
</details>
<br>
