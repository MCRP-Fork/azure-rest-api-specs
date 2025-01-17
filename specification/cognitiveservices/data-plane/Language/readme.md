# Cognitive Services Language SDK

This is the AutoRest configuration file the Cognitive Services Language SDK.

> see https://aka.ms/autorest

## Releases

The current preview release is 2021-05-01-preview

```yaml
tag: release_2021_05_01_preview
add-credentials: true
clear-output-folder: true
```

### Release 2021-05-01-preview

These settings apply only when `--tag=elease_2021_05_01_preview` is specified on the command line.

``` yaml $(tag) == 'release_2021_05_01_preview'
input-file:
- preview/2021-05-01-preview/questionanswering.json
- preview/2021-05-01-preview/questionanswering-authoring.json
title:
  Microsoft Cognitive Language Service
modelerfour:
  lenient-model-deduplication: true
```

## Swagger to SDK

This section describes what SDK should be generated by the automatic system.
This is not used by Autorest itself.

``` yaml $(swagger-to-sdk)
swagger-to-sdk:
  - repo: azure-sdk-for-net
  - repo: azure-sdk-for-python
```
