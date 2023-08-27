<h1 align="center">
  <br>
  <img src="https://raw.githubusercontent.com/gabrielmaialva33/doc-sympla-integration/master/.github/assets/docs.png" alt="Doc: Sympla " width="200">
  <br>
  A documentation for <a href="https://www.sympla.com.br/">Sympla API</a>
  <br>
</h1>

<p align="center">
  <img src="https://img.shields.io/github/languages/top/gabrielmaialva33/doc-sympla-integration?style=flat&logo=appveyor" alt="GitHub top language" >
  <img src="https://img.shields.io/github/languages/count/gabrielmaialva33/doc-sympla-integration?style=flat&logo=appveyor" alt="GitHub language count" >
  <img src="https://img.shields.io/github/repo-size/gabrielmaialva33/doc-sympla-integration?style=flat&logo=appveyor" alt="Repository size" >
  <img src="https://img.shields.io/github/license/gabrielmaialva33/doc-sympla-integration?color=00b8d3?style=flat&logo=appveyor" alt="License" /> 
  <a href="https://github.com/gabrielmaialva33/doc-sympla-integration/commits/master">
    <img src="https://img.shields.io/github/last-commit/gabrielmaialva33/doc-sympla-integration?style=flat&logo=appveyor" alt="GitHub last commit" >
    <img src="https://img.shields.io/badge/made%20by-Maia-15c3d6?style=flat&logo=appveyor" alt="Maia" >  
  </a>
</p>

<p align="center">
  <a href="#bookmark-about">About</a>&nbsp;&nbsp;&nbsp;|&nbsp;&nbsp;&nbsp;
  <a href="#computer-technologies">Technologies</a>&nbsp;&nbsp;&nbsp;|&nbsp;&nbsp;&nbsp;
  <a href="#package-installation">Installation</a>&nbsp;&nbsp;&nbsp;|&nbsp;&nbsp;&nbsp;
  <a href="#wrench-configuration">Configuration</a>&nbsp;&nbsp;&nbsp;|&nbsp;&nbsp;&nbsp;
  <a href="#memo-documentation">Documentation</a>&nbsp;&nbsp;&nbsp;|&nbsp;&nbsp;&nbsp;
  <a href="#memo-license">License</a>
</p>

<br>

## :bookmark: About

**Doc: Sympla API** is a documentation for [Sympla API](https://developers.sympla.com.br/)

<br>

## :computer: Technologies

- **[OpenAPI](https://swagger.io/specification/)**
- **[Insomnia](https://insomnia.rest/)**
- **[Sympla API](https://developers.sympla.com.br/)**

## :package: Installation

```bash
# clone the repository
git clone https://github.com/gabrielmaialva33/doc-sympla-integration.git
# enter the directory
cd doc-sympla-integration
# use inso to generate the documentation
inso generate --spec doc-sympla-integration.yaml --type openapi --output doc-sympla-integration.json
```

### :wrench: **Configuration**

open the `doc-sympla.yaml` file in insomnia or postman and change the host and basePath

```yaml
host: "api.sympla.com.br"
basePath: "/public/v3"
```

### :memo: **Documentation**

```md
# Use insomnia or postman to test the routes

file `doc-sympla.yaml` in root directory
```

### :writing_hand: **Author**

| [![Maia](https://avatars.githubusercontent.com/u/26732067?size=100)](https://github.com/gabrielmaialva33) |
|-----------------------------------------------------------------------------------------------------------|
| [Maia](https://github.com/gabrielmaialva33)                                                               |

## License

[MIT License](./LICENSE)
