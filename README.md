![CI Status](https://github.com/TEAM-PIXL/PIXL-POS/actions/workflows/compendium.yml/badge.svg)
[![Documentation](https://img.shields.io/badge/mkdocs-online-green)]()

# Compendium CI/CD Suite

| **Component**                                      | **Purpose**                                             |
|----------------------------------------------------|---------------------------------------------------------|
| **compendium/jobs/docker/build@v1**                | Build from Dockerfile and publish to registry.          |
| **compendium/jobs/java/lint-checkstyle@v1**        | Lint using CheckStyle linting for java.                 |
| **compendium/jobs/java/gradle/build@v1**           | Build a JAR from java source with gradle.               |
| **compendium/jobs/java/maven/compile@v1**          | Compile java code with maven.                           |
| **compendium/jobs/java/maven/test-junit@v1**       | Test java code with maven junit tests.                  |
| **compendium/jobs/java/maven/javadocs-publish@v1** | Publish javadocs with Github pages and maven.           |
| **compendium/jobs/release/deploy-tag@v1**          | Deploy a tag to GitHub on success of pipeline.          |
| **compendium/jobs/release/publish-docs@v1**        | Publish mkdocs with GitHub pages.                       |
| **compendium/jobs/python/lint-flake8@v1**          | Lint python code to flake8, black, and isort standards. |
| **compendium/jobs/python/poetry/pytest@v1**        | Test python code using poetry as a package manager.     |
