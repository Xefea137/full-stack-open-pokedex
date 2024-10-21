## <u>**11.1 For a team of about 6 people working on a Python application which is in active development and will be released soon.**</u>

**Answer 1** <br>
Tools for taking care of linting, testing and building in Python:
- Linting: Pylint, Flake8
- Testing: Unittest, Pytest, Nose/Nose 2, Doctest
- Building: PyBuilder, Poetry, Setuptools, SCons

**Answer 2** <br>
Alternatives to set up the CI besides Jenkins and GitHub Actions:
- Spacelift
- CodeShip
- AWS CodePipeline
- Azure Pipelines
- TeamCity

**Answer 3** <br>
I think a cloud-based environment would be a better option for the setup.
Since the team is small, a cloud based environment is a better choice because it is easier to setup and easier to maintain. So, the small team will have more time in hand to work on developing the application specially since the application is going to be released soon.

The information needed to make the decision between choosing a self-hosted or a cloud-based environment are:
- Budget: If the resources are limited, it is better to choose the cloud-based environment as the cloud-based solutions often have low or free costs for initial usage.
- Team size: If the team size is small, a cloud-based environment is better because it is easier to setup or is already setup, so the team can focus on developing the application instead of setting up and managing the system.
- Resources: A cloud-based environment has some resource limitations which is not the case for a self-hosted environment. In a self hosted environment, if a build is slow, a company can just get extra resources to fix it, while in a self-hosted environment, there are resource limitations.