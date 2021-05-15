### Conceptual Exercise

Answer the following questions below:

- What is the purpose of the React Router?

  - React Router, and dynamic, client-side routing, allows us to build a single-page web application with navigation without the page refreshing as the user navigates.React Router uses component structure to call components, which display the appropriate information.

- What is a single page application?

  - A single-page application is a web application or website that interacts with the user by dynamically rewriting the current web page with new data from the web server, instead of the default method of a web browser loading entire new pages.

- What are some differences between client side and server side routing?
  - The major differences between client side and server side routing is that with server side routing, a new request must be made to the server with every route which causes a new page to render. With client-side routing, such as React Router, is a web application or website that interacts with the user by dynamically rewriting the current web page with new data from the web server, instead of the default method of a web browser loading entire new pages.
- What are two ways of handling redirects with React Router? When would you use each?

  - You can use either the Redirect component, which is useful for instances like where a user is on a page they shouldn't have gotten to and is automatically redirected, or you can push to the history object which allows the user to then use the forward/backward button to reach the page again, such as after a form submission.

- What are two different ways to handle page-not-found user experiences using React Router?

  - The first way would be to use redirect to send the user to a 404 page, or you can use Switch to have a catchall that displays a 404 component for any route that isn't matched.

- How do you grab URL parameters from within a component using React Router?
  - URL paramaters can be caught within a component using the useParams hook.
- What is context in React? When would you use it?

  - Context is a React API which allows a parent component to pass down data to children without the use of props. This is useful in situations like when you need to pass down information to deeply nested components but don't need to access that information at every level.

- Describe some differences between class-based components and function
  components in React.

  - First of all, the clear difference is the syntax. Just like in their names, a functional component is just a plain JavaScript function that returns JSX. A class component is a JavaScript class that extends React. ... On the other hand, when defining a class component, you have to make a class that extends React.

- What are some of the problems that hooks were designed to solve?
  - reusability of logic between components, and the cleaning up of the code.
