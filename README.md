# Noodle Markets Coding Challenge

The Noodle Markets coding challenge is required for all engineering candidates.

## Guidelines

Create the backend and frontend for an API-driven single page web application an ecommerce
site might use to manage its product listings.  In order to keep things simple, a product
is only required to have a name a list of associated string attributes.

For instance, the store might have a product named "Book" that has "free_shipping" and
"on_sale" attributes associated with it.  The same attribute may be associated with more
than one product.

### Functional requirements

A user must have the ability to:

- Create a new product
- List existing products
- Delete a product
- Create an attribute
- Associate an attribute with a product
- Remove an attribute from a product

### Architecture

The backend must be implemented as a RESTful API built in Python.  Feel free to use any
available open-source frameworks or libraries that might make this task easier.

**Front-end engineering candidates only:** You may implement the backend in whatever
language you're most comfortable with.  As a last resort you may use mocked API responses.

The frontend must be built as a single-page app using javascript, leveraging AJAX calls to
the backend data service you create.  Again, open-source frameworks and libraries are more
than welcome.  How the UI is designed is up to you, but it should be functional,
intuitive, and aesthetically pleasing.

### Documentation

Include a README.md that documents the problem this code solves, your architecture and
framework choices, and how to set up and run the project and tests.

If any requirements aren't being met or if there are any known issues with the code, this
is the place to document them.

## Review criteria

Submissions will be evaluated on the following criteria:

- **Correctness:** Does the solution meet all functional requirements?
- **Code style:** Is the code understandable, maintainable, and organized?  Is the code
  style consistent and reasonable?  Are there any anti-patterns or other red flags?
- **Overall UX:** Is the UI intuitive, clean, and functional?  Does it look professional?
- **Architecture:** Does the code follow the architecture guidelines above?
- **Tests:** Does the code include automated tests?  Is it clear what the tests are doing?
  Is there a good mix between unit and integration tests where appropriate?
- **Documentation:** Does the code include a README?  Does it follow the guidelines above?

## Some tips

- **Feel free to ask questions.** We encourage you to seek clarification where things aren't
  obvious.  Points are never deducted for questions.
- **Make use of open-source libraries and frameworks.** We're a startup so we value speed
  and correctness over hard work.  No need to reinvent the wheel.
- **Quality is most important.** If you don't have time to finish everything, don't worry
  about it.  What we most want to see is production-ready code that's clean and correct.
  Just make sure to document any tradeoffs you had to make in the project's README.md.
