# How to share the business logic in a polyglot app mixing Java and TypeScript
​
Today, developing a modern web app requires to become polyglot, mastering client and
server code, each with its challenges to govern business logic. 
What about easily creating your own fluent API in Java in order to manipulate and
drive the business logic of the whole application, supporting a polyglot approach? 

With the dOOv framework (https://doov.org) we provide a fluent API for object validation
and mapping that could be used symmetrically in Java and in TypeScript. 
We will tell you the story of how we migrated iteratively our web application
containing web forms of hundreds of inputs, with complex validation and dependency logic,
reused effortlessly between client and server side. 

## Private message for committee

Website: http://doov.org
Github: https://github.com/doov-io
Slides: https://doov.org/conference/how_to_create_dsl_with_lambda_builders.html


We developed dOOv to migrate 1000+ business rules to a format that would be easy to write
and to export in a human readable form.

Recently we extend the framework to provide interoperability with TypeScript and provide 
the same fluent API in the Javascript ecosystem with the ability to reuse effortlessly 
some business logic on the client side.

Last year at CodeOne we demonstrated the dOOv framework on a server side application and 
presented the natural language features. We expect to demonstrate new capabilities to 
deploy the approach in the browser side.

We open-sourced our project and present it in conferences because domain object mapping
and validation is a recurrent and important problem in our work, so it might help others.

We like to get feedback on dOOv, discuss about usage and future improvements.