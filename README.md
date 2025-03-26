[![CI Status][ci-shield]][ci-url]
[![Contributors][contributors-shield]][contributors-url]
[![Forks][forks-shield]][forks-url]
[![Stargazers][stars-shield]][stars-url]
[![Issues][issues-shield]][issues-url]
[![Documentation][mkdocs-shield]][docs-url]


<br />
<div align="center">
  <a href="https://github.com/parkermmr/compendium">
    <img src="docs/img/logo.webp" alt="Logo" width="80" height="80">
  </a>

  <h3 align="center">Compendium CI/CD</h3>

  <p align="center">
    A full multi-language CI/CD suite for streamlining personal projects & industry workflows. 
    <br />
    Made for GitHub Actions natively.
    <br />
    <a href="https://compendium.pages.io.teampixl.info"><strong>Explore the docs »</strong></a>
    <br />
    <br />
    <a href="https://github.com/parkermmr/compendium">View Demo</a>
    &middot;
    <a href="https://github.com/parkermmr/compendium/issues/new?labels=bug&template=bug-report---.md">Report Bug</a>
    &middot;
    <a href="https://https://github.com/parkermmr/compendium/issues/new?labels=enhancement&template=feature-request---.md">Request Feature</a>
  </p>
</div>

<details>
  <summary>Table of Contents</summary>
  <ol>
    <li>
      <a href="#about-the-project">About The Project</a>
      <ul>
        <li><a href="#built-for">Built For</a></li>
      </ul>
    </li>
    <li>
      <a href="#getting-started">Getting Started</a>
      <ul>
        <li><a href="#prerequisites">Prerequisites</a></li>
        <li><a href="#installation">Installation</a></li>
      </ul>
    </li>
    <li>
      <a href="#usage">Usage</a>
      <ul>
        <li><a href="#compendium-jobs">Compendium Jobs</a></li>
      </ul>
    </li>
    <li><a href="#acknowledgments">Acknowledgments</a></li>
  </ol>
</details>

## About The Project


### Built For

<p align="center">
  
- [![Python][python]][python-url]
- [![Git][git]][git-url]
- [![GitHub Actions][github-actions]][github-actions-url]
- [![Docker][docker]][docker-url]

</p>
<p align="right">(<a href="#readme-top">back to top</a>)</p>

## Getting Started

### Prerequisites

### Installation

### Compendium Jobs

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
| **compendium/jobs/security/secure@v1**             | CodeQL security check for vulnerabilities               |

### Acknowledgments:

<a href="https://github.com/parkermmr/compendium/graphs/contributors">
  <img src="https://contrib.rocks/image?repo=parkermmr/compendium" alt="contrib.rocks image" />
</a>

<p align="right">(<a href="#readme-top">back to top</a>)</p>

[ci-shield]: https://img.shields.io/github/actions/workflow/status/parkermmr/compendium/publish.yml?branch=main&style=for-the-badge
[ci-url]: https://github.com/parkermmr/kraken/actions/workflows/compendium.yml
[contributors-shield]: https://img.shields.io/github/contributors/parkermmr/compendium.svg?style=for-the-badge
[contributors-url]: https://github.com/parkermmr/compendium/graphs/contributors
[forks-shield]: https://img.shields.io/github/forks/parkermmr/compendium.svg?style=for-the-badge
[forks-url]: https://github.com/parkermmr/compendium/network/members
[stars-shield]: https://img.shields.io/github/stars/parkermmr/compendium.svg?style=for-the-badge
[stars-url]: https://github.com/parkermmr/compendium/stargazers
[issues-shield]: https://img.shields.io/github/issues/parkermmr/compendium.svg?style=for-the-badge
[issues-url]: https://github.com/parkermmr/compendium/issues
[python]: https://img.shields.io/badge/python-FFE873?style=for-the-badge&logo=python&logoColor
[python-url]: https://www.python.org/
[git]: https://img.shields.io/badge/Git-F05032?style=for-the-badge&logo=Git&logoColor=white
[git-url]: https://git-scm.com/
[github-actions]: https://img.shields.io/badge/GitHub%20Actions-2088FF?style=for-the-badge&logo=GitHub%20Actions&logoColor=white
[github-actions-url]: https://github.com/features/actions
[docker]: https://img.shields.io/badge/Docker-2496ED?style=for-the-badge&logo=Docker&logoColor=white
[docker-url]: https://www.docker.com/
[compendium]: https://github.com/parkermmr/compendium
[mkdocs-shield]: https://img.shields.io/badge/documentation-online-green?style=for-the-badge
[docs-url]: https://compendium.pages.io.teampixl.info