<div align="center">
    <h1>
        &lt;Project Title&gt;
    </h1>
    <h4><b>&lt;Project Subtitle&gt;</b></h4>
    <h4>
        <a href="#development-guide">Development guide</a>
        •
        <a href="#contacts">Contacts</a>
    </h4>
    <h3>
        <a href="https://www.odoo.com">
            <img src="https://img.shields.io/badge/odoo-17.0-blue">
        </a>
        <a href="https://www.python.org">
            <img src="https://img.shields.io/badge/Python-3.10-3776AB.svg?style=flat&logo=python&logoColor=white">
        </a>
        <a href="https://pre-commit.com/">
            <img src="https://img.shields.io/badge/pre--commit-enabled-brightgreen?logo=pre-commit&logoColor=white">
        </a>
    </h3>
</div>


```bash
poetry source add odoo https://nightly.odoo.com/17.0/nightly/tgz/odoo_17.0.20240906.zip
```

&lt;Project description&gt;

## Development guide

This guide outlines the steps to set up a development environment and contribute to this project.

### Prerequisites:

For the most part, these are the bare-minimum requirements for getting up-and-running.
- [PostgreSQL](https://www.postgresql.org/) (version 14 or above)
- [Poetry](https://python-poetry.org/)
- [pre-commit](https://pre-commit.com/)

### Running server locally
1. Clone this repository
```bash
git clone <repo_url>
```
2. Navigate to the project directory
```bash
cd <repo>
```
3. Install dependencies
```bash
poetry install
```
4. Create and modify config file from example
```bash
cp odoo.conf.example odoo.conf
```
5. Start server using config file
```bash
poetry run odoo -c /config/path/odoo.conf
```

### Testing
To run the test suite
```bash
poetry run odoo 
```

## Contributions
Please see the CONTRIBUTING.md file for details on coding style, pull request requirements, and how to report issues.

## Contacts
1. [John Doe &ndash; Project Manager](mailto:john@keda-tech.com)
