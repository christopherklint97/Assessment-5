### Conceptual Exercise

Answer the following questions below:

- What is RESTful routing?

    It is a set of standards to create usable routes based on mapping HTTP routes and CRUD actions together conventionally.

- What is a resource?

    A resource is an object sent by the server that corresponds to a specific format to the client.

- When building a JSON API why do you not include routes to render a form that when submitted creates a new user?

    Because including these routes would mean that if the client would refresh the page on a form, then the information would be resubmitted.

- What does idempotent mean? Which HTTP verbs are idempotent?

    An HTTP method is idempotent if the request does not have any side-effects, except for statistics. GET, PUT, DELETE, HEAD, OPTIONS and TRACE HTTP methods are idempotent.

- What is the difference between PUT and PATCH?

    PUT sends and updates the complete entity while PATCH focuses only on the fields that were supplied and affects those alone.

- What is one way encryption?

    One way encryption is encryption that is hard to reverse.

- What is the purpose of a `salt` when hashing a password?

    `salt` is the random data used for input of a function that hashes data or password.

- What is the purpose of the Bcrypt module?

    Bcrypt is used for hasing data (for example, passwords) in Python on the server.

- What is the difference between authorization and authentication?

    Authentication is identifying who the user is while authorization is establishing which rights and privileges a user has.
