If the application is coded with Python, for linting one can use pylint. For testing, there are pytest and unittest. For building, there exist package managers like pip or poetry. Also, build system like setuptools  is a Python specific library for facilitating Python project packages. There are task runners such as Invoke, that is a task execution tool for shell commands.

Other CI tools include Travis CI, CircleCI and GitLab CI/CD.

To answer the question if this setup would be better in self-hosted or cloud based environment, there are many factors one must consider. These factors include team expertise, the complexity of the project, security needs, budget considerations, performance and the lifecycle of the project. 

Team’s knowledge of CI/CD systems impacts the decision for the system they should use. If they have experience managing servers and CI/CD tools, a self-hosted environment offers control and customization. However, if they lack this expertise, a cloud-based solution may be better to minimize maintenance overhead.

As the application will be released soon, efficiency and speed are important. Cloud-based solutions, often preconfigured for Python, are easy to set up, allowing the team to focus on development instead of infrastructure. Cloud-based solutions can also be more cost-effective for smaller projects. However, if the application is expected to grow larger, ongoing cloud costs might become more expensive than maintaining the self-hosted system.

Since the application is in active development, a cloud-based CI/CD system might be a better choice, making it easier to test and deploy. However, a self-hosted option may be considered if security is a priority.