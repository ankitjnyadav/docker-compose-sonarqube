The Software Industry is exponentially evolving day to day. Since its invention, the lines of code and business logic functions are increasing rapidly to compete with each other and this leading to un-maintainability of code. Every firm has the following concerns on dealing with its code

  *  Code maintainability
  *  Bugs in code
  *  Security

These can problems can be addressed using static code analysis before releasing the software in the market. SonarQube is primarily focused to identify the Maintainability issues, reliability and security issues.
And it shows the overall health of an application on Web dashboard by highlighting the possible code smells and issues with defined quality gates and profiles. By fixing the leaks, software can improve its code quality steadily. And it can easily integrate with several CI/CD tools.

Using an external PostgreSQL database instead of the default one. This is important for various reasons, including being able to migrate all the data through SonarQube upgrades.

For this I have made use of docker-compose, it lets you bring up a complete development environment with only one command: "docker-compose up", and tear it down just as easily using "docker-compose down".
