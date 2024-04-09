PYTHON

For linting, the most used tools in Python are flake8 and black. 
flake8 finds style errors in the code base. However, it does not fix them.
This is where black comes in. Black does the job of cleaning the code into a format that is easy to read and maintain.

Testing in Python is usually taken care of with PyUnit or pytest.
PyUnit is the built-in framework for testing in Python, especially focused on unit tests.
Pytest is an open-source framework that can be used to write almost all types of software tests, like unit tests, integration tests, end-to-end tests, and functional tests.

Regarding the building step, the most popular tool in Python is probably Poetry, a framework that offers automated dependency managing and building/packaging.

Popular alternatives to Jenkins and Github Actions are: CircleCI, Buildkite, GitLab CI, Travis CI and Atlassian Bamboo.

Based on the information we have, I would say that a cloud based environment like Github Actions would be better for this project.
Reasons for this choice are based on the limited size of the project (considering the size of the developers team) and the absence of any special requirement.
The information needed to make an informed choice of CI/CD environment would be how many people are working on the project (managing a self-hosted environment may be time expensive for a small group of developers) and the specific requirements for the software that is being developed (for example if it requires the use of a specific piece of hardware).