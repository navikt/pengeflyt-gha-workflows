# mob-gha-workflows

Repoet inneholder gjenbrukbare GitHub Actions workflows. Det er en forhåndsdefinert workflow som kan gjenbrukes på
tvers av flere repositorier. Dette lar oss sentralisere og standardisere CI/CD-logikk,
slik at vi kan oppdatere, vedlikeholde og skalere denne logikken på ett sted.

## Utvikling og endringer

For å teste endringer før de merges inn i main må du gjøre følgende:

1. Du må lage en branch i dette github actions repoet.
2. Der du ønsker å bruke workflow fra branch i dette repoet bruker du: `@branch-navn-i-mob-gha-workflow-repo` istedenfor `@main`.

# Henvendelser

Spørsmål knyttet til koden eller prosjektet kan stilles som issues her på Github.
Interne henvendelser kan sendes via Slack i kanalen [#utbetaling](https://nav-it.slack.com/archives/CKZADNFBP)
