# Jenkins & CI/CD
## CI/CD
- Pipeline that allows the team to rapidly and reliably deliver changes to code
### Continuous Integration
- Frequently (often many times a day) integrating all of the developers work
- Using version controlling to keep track of changes
- Automatically testing that code in the testing environment to give instant
feedback to the developers and ensure that any code that gets deployed is up to
the correct standard
### Continuous Delivery
- Pushes these changes to a pre production environment (note yet live) that can
be deployed manually at a moments notice
### Continuous Deployment
- Code that properly integrates and passes the relevant tests can be
automatically passed to the production environment to deploy the code (now live)
## Jenkins
- Free, opensource, built on Java
- An automation server that can be used to implement a CI/CD pipeline
- Link up to github where it can automatically run tests against the code
pushed and give instant feedback
- If tests pass you can allow it to push this code to deployment or to an
environment where it can be deployed at a moments notice
