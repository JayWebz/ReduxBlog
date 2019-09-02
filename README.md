A concise blog application that uses redux to manage data. Data includes blog posts and blog post authors.

# Frameworks and packages
- Semantic UI CSS Framework
- redux
- redux-thunk - middleware to allow for asynchronous actions
- lodash - chaining actions together

Middleware - 
- A plain JS function that gets called with every action dispatched
- Has the ability to stop and modify actions. 
- Linked to project in index.js
- Action creators can return action objects or you can return functions with dispatch and getState as parameters. 
- When a function is called, it is automatically invoked.

# APIs used:
https://jsonplaceholder.typicode.com

# Endpoints used:
/posts
/users
