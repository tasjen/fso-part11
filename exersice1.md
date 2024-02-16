I would choose Github Actions (cloud-based) for building CI pipelines for my Java-React app. With tools for linting, testing, and building steps being Checkstyle, JUnit, and Maven, respectively. There are several reasons why I choose Github Actions.

1. It is cloud-based. Which is simpler to setup than self-hosted CI tools e.g Jenkins. No need to worry about infrastructure setup or maintenance.
2. Although Jenkins provides more plugins that provide additional functionality, my app is small to medium-sized which doesn't require much functionality or customization options. So it would be overkill to use Jenkins.
3. Popularity. Since Github actions is the most popular cloud-based CI tools. It comes with big active communities and documentation resources available. And the app is already hosted in Github. There is no other reason to use any other tools
4. Setting up Jenkins may require additional cost for its infrastructure. Since my app is small and simple, the free plan of Github Actions would be enough for my CI process.

There are many alternatives CI tools such as

1. Travis CI (cloud-based)
2. CircleCI (both cloud-based and self-hosted)
3. GitLab CI/CD (cloud-based)
4. Azure Pipelines (cloud-based)
5. Bitbucket Pipelines (cloud-based)
6. Bamboo (self-hosted)
7. TeamCity (both cloud-based and self-hosted)
