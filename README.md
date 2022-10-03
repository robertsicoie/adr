# Architectural Decision Records

## Content

* [Decision template](docs/templates/template.md)
* [Sample decisions](docs/decisions/)
* [Decisions index.](docs/decisions/index.md)
* [Sample markdownlint configuration file.](.markdownlint.json)

## Install

To use this sample repo install depencies by running `npm install`

## How to create new ADR

1. Create a copy of the template file:
```cp docs/templates/template.md docs/decisions/NNNN-decision-title.md```
1. Add details.
1. Run adr-log to regenerate index.
```cd docs/decisions && adr-log -i```

## Linting

`markdownlint docs/decisions`

## Links

* [Homepage of the ADR GitHub organization](https://adr.github.io/)
