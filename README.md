<p align="center">
  <a href="https://www.sonarsource.com/" target="blank"><img src="./statics/sonarqube.svg" width="200" alt="Sonarqube Logo" /></a>
</p>

## Installation

- Install [Docker](https://www.docker.com/) and docker-compose in your system.

- Run the `docker-compose.yml` file with the next command:
  ```bash
  $: docker-compose up -d
  ```

- Install [sonarqube-cli](https://docs.sonarsource.com/sonarqube/latest/analyzing-source-code/scanners/sonarscanner/)

- Copy the example configuration file `sonar-project.properties` in your project root.

  Run the next code in your project root:
  ```bash

  $: sonar-scanner

  ```

## Created by
[HamselBG](https://github.com/HBG07/)