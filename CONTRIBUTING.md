# Contributing

Thanks for considering contributing to this project! Each contribution is
highly appreciated. In order to maintain a high code quality, please follow
all steps below.

## Requirements

- Composer
- PHP >= 8.1

## Preparation

```bash
# Clone repository
git clone https://github.com/mteu/basic-project-template.git
cd basic-project-template

# Install dependencies
composer install
```

## Run linters

```bash
# All linters
composer lint

# Specific linters
composer lint:composer
composer lint:editorconfig
composer lint:twig
```

## Validate `config.yaml`

```bash
composer validate-schema
```

:bulb: You need a local Docker installation for this command.

## Submit a pull request

Once you have finished your work, please **submit a pull request** and describe
what you've done. Ideally, your PR references an issue describing the problem
you're trying to solve.

All described code quality tools are automatically executed on each pull request
for all currently supported PHP versions. Take a look at the appropriate
[workflows][2] to get a detailed overview.

[1]: http://nvie.com/git-model
[2]: .github/workflows
