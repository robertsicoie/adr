# Architectural Decision Records

## Content

* [docs/templates/template.md] (Decision template)
* [docs/decisions/] (Sample decisions)
* [docs/decisions/index.md] (Decisions index.)
* [.markdownlint.json] (Sample markdownlint configuration file.)

## Install

To use this sample repo install depencies by running `npm install`

## How to create new ADR

1. Create a copy of the template file:
```cp docs/templates/template.md docs/decisions/NNNN-decide-to```
1. Add details.
1. Run adr-log to regenerate index.
```cd docs/decisions && adr-log -i```

## Linting

`markdownlint docs/decisions`

## Links

* [https://adr.github.io/] (Homepage of the ADR GitHub organization)
