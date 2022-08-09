# GitHub Label Sync Configuration
Synchronize our favourite labels to our GitHub repositories. All colours are WCAG compliant.

## Requirements
You'll need [GitHub Label Sync](https://github.com/Financial-Times/github-label-sync) installed.

## Run
Run GitHub Label Sync on a repo (reading label data from a local `labels.yml`):
```sh
github-label-sync --access-token ACCESS_TOKEN --labels labels.yml --allow-added-labels org/repository
```
