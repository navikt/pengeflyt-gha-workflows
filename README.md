# pengeflyt-gha-workflows

Repoet inneholder GitHub Actions workflows som kan gjenbrukes på tvers av flere repositorier.
Dette lar oss sentralisere og standardisere CI/CD-logikk, slik at vi kan vedlikeholde denne logikken på ett sted.

## Utvikling og endringer

For å teste endringer før de merges inn i main må du gjøre følgende:

1. Gjøre workflow-endringene på en branch `branch-navn` i dette github actions repoet.
2. I repositoriet du ønsker å teste workflow-endringene branchen, bruker du: `uses: ...@branch-navn` istedenfor `@main`.

# Henvendelser

Spørsmål knyttet til koden eller prosjektet kan stilles på Slack i kanalen [#utbetaling](https://nav-it.slack.com/archives/CKZADNFBP)
