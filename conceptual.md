### Conceptual Exercise

Answer the following questions below:

- What is a JWT?
  JWT stands for JSON Web Token and it is a way to securely transmit information between parties as a JSON object. The information is digitally signed which makes it secure. JWT's are an open standard and are implemented across tech stacks, making it easy to share tokens across different services.

- What is the signature portion of the JWT? What does it do?
  The signature of the JWT is what allows the integrity of the info inside it to be verified. It includes the encoded header, payload, and a secret key so it can be validated later.

- If a JWT is intercepted, can the attacker see what's inside the payload?
  Yes. The payload is encoded but not encrypted so do not put secret information in the payload.

- How can you implement authentication with a JWT? Describe how it works at a high level.
  To authenticate a JWT the client sends the user's credentials to the server which in turn authenticates the user and creates a JWT containing informations about the user.

- Compare and contrast unit, integration and end-to-end tests.
  Unit tests test an individual component, function or method.
  Integration tests are written with unittest frameworks and combine them to test multiple functions at a time.
  End to end tests take the application as a whole and test it for functionality.

- What is a mock? What are some things you would mock?
  Mocking is used in unit testing to replace objects and behaviors that would be tricky to incorporate into the unit test. Some items to mock would be impure functions, AJAX requests and reading/writing to files.

- What is continuous integration?
  Continuous integration is the practice of merging in small code changes frequently, rather than merging a large change at the end of a development cycle. This allows you to develop and test your software in smaller increments. Tools that are used for CI include Travis CI, Jenkins, Circle CI and Buddy.

- What is an environment variable and what are they used for?
  An environment variable is a key/value pair configured outside your application. They are stored in a .env file and should be added to the .gitignore file so they are not accessed or compromised.

- What is TDD? What are some benefits and drawbacks?
  TDD stands for test-driven development. Write tests first that will fail and write only the code necessary to get the tests to pass. This will allow you to focus on task at hand by using the red(tests fail), green(writing code to get tests to pass), refactor method.

- What is the value of using JSONSchema for validation?
  Stops bad data by failing user data before it gets to your database. Reduces amount of code for processing and validating data. It also is a validation system that is easy to setup and maintain.

- What are some ways to decide which code to test?
  Don't test everything or get caught up in percentages. Write code to pass tests not the other way around.

- What does `RETURNING` do in SQL? When would you use it?
  It returns data that was inserted, updated or deleted. This is useful when we want only the values that were inserted, updated or deleted as a result of the operation.

- What are some differences between Web Sockets and HTTP?
  Web Sockets allow realtime communication between the server and client. HTTP connections work by sending requests and waiting for responses and then terminating the connection.

- Did you prefer using Flask over Express? Why or why not (there is no right
  answer here --- we want to see how you think about technology)?
  In terms of speed I would choose Express even though Flask is very simple to setup and use.
