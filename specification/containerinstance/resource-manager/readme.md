# ContainerInstance

> see https://aka.ms/autorest

This is the AutoRest configuration file for ContainerInstance.

---

## Getting Started

To build the SDK for ContainerInstance, simply [Install AutoRest](https://aka.ms/autorest/install) and in this folder, run:

> `autorest`

To see additional help and options, run:

> `autorest --help`

---

## Configuration

### Basic Information

These are the global settings for the ContainerInstance API.

``` yaml
openapi-type: arm
tag: package-preview-2024-11
```

### Tag: package-preview-2024-11

These settings apply only when `--tag=package-preview-2024-11` is specified on the command line.

```yaml $(tag) == 'package-preview-2024-11'
input-file:
  - Microsoft.ContainerInstance/preview/2024-11-01-preview/containerInstance.json
```

### Tag: package-preview-2024-10

These settings apply only when `--tag=package-preview-2024-10` is specified on the command line.

```yaml $(tag) == 'package-preview-2024-10'
input-file:
  - Microsoft.ContainerInstance/preview/2024-10-01-preview/containerInstance.json
```

### Tag: package-preview-2024-09

These settings apply only when `--tag=package-preview-2024-09` is specified on the command line.

```yaml $(tag) == 'package-preview-2024-09'
input-file:
  - Microsoft.ContainerInstance/preview/2024-09-01-preview/containerInstance.json
```

### Tag: package-preview-2024-05

These settings apply only when `--tag=package-preview-2024-05` is specified on the command line.

```yaml $(tag) == 'package-preview-2024-05'
input-file:
  - Microsoft.ContainerInstance/preview/2024-05-01-preview/containerInstance.json
```

### Tag: package-2023-05

These settings apply only when `--tag=package-2023-05` is specified on the command line.

```yaml $(tag) == 'package-2023-05'
input-file:
  - Microsoft.ContainerInstance/stable/2023-05-01/containerInstance.json
```

### Tag: package-preview-2023-02

These settings apply only when `--tag=package-preview-2023-02` is specified on the command line.

```yaml $(tag) == 'package-preview-2023-02'
input-file:
  - Microsoft.ContainerInstance/preview/2023-02-01-preview/containerInstance.json
```

### Tag: package-preview-2022-10

These settings apply only when `--tag=package-preview-2022-10` is specified on the command line.

``` yaml $(tag) == 'package-preview-2022-10'
input-file:
  - Microsoft.ContainerInstance/preview/2022-10-01-preview/containerInstance.json
```

### Tag: package-2022-09

These settings apply only when `--tag=package-2022-09` is specified on the command line.

``` yaml $(tag) == 'package-2022-09'
input-file:
  - Microsoft.ContainerInstance/stable/2022-09-01/containerInstance.json
```

### Tag: package-2021-10

These settings apply only when `--tag=package-2021-10` is specified on the command line.

``` yaml $(tag) == 'package-2021-10'
input-file:
  - Microsoft.ContainerInstance/stable/2021-10-01/containerInstance.json
```

### Tag: package-2021-09

These settings apply only when `--tag=package-2021-09` is specified on the command line.

``` yaml $(tag) == 'package-2021-09'
input-file:
  - Microsoft.ContainerInstance/stable/2021-09-01/containerInstance.json
```

### Tag: package-2021-07

These settings apply only when `--tag=package-2021-07` is specified on the command line.

``` yaml $(tag) == 'package-2021-07'
input-file:
  - Microsoft.ContainerInstance/stable/2021-07-01/containerInstance.json
```

### Tag: package-2021-03

These settings apply only when `--tag=package-2021-03` is specified on the command line.

``` yaml $(tag) == 'package-2021-03'
input-file:
  - Microsoft.ContainerInstance/stable/2021-03-01/containerInstance.json
```

### Tag: package-2020-11

These settings apply only when `--tag=package-2020-11` is specified on the command line.

``` yaml $(tag) == 'package-2020-11'
input-file:
  - Microsoft.ContainerInstance/stable/2020-11-01/containerInstance.json
```

### Tag: package-2019-12

These settings apply only when `--tag=package-2019-12` is specified on the command line.

``` yaml $(tag) == 'package-2019-12'
input-file:
  - Microsoft.ContainerInstance/stable/2019-12-01/containerInstance.json
```

### Tag: package-2018-10

These settings apply only when `--tag=package-2018-10` is specified on the command line.

``` yaml $(tag) == 'package-2018-10'
input-file:
- Microsoft.ContainerInstance/stable/2018-10-01/containerInstance.json
```

### Tag: package-2018-09

These settings apply only when `--tag=package-2018-09` is specified on the command line.

``` yaml $(tag) == 'package-2018-09'
input-file:
- Microsoft.ContainerInstance/stable/2018-09-01/containerInstance.json
```

### Tag: package-2018-06

These settings apply only when `--tag=package-2018-06` is specified on the command line.

``` yaml $(tag) == 'package-2018-06'
input-file:
- Microsoft.ContainerInstance/stable/2018-06-01/containerInstance.json
```

### Tag: package-2018-04

These settings apply only when `--tag=package-2018-04` is specified on the command line.

``` yaml $(tag) == 'package-2018-04'
input-file:
- Microsoft.ContainerInstance/stable/2018-04-01/containerInstance.json
```

### Tag: package-2018-02-preview

These settings apply only when `--tag=package-2018-02-preview` is specified on the command line.

``` yaml $(tag) == 'package-2018-02-preview'
input-file:
- Microsoft.ContainerInstance/preview/2018-02-01-preview/containerInstance.json
```

### Tag: package-2017-12-preview

These settings apply only when `--tag=package-2017-12-preview` is specified on the command line.

``` yaml $(tag) == 'package-2017-12-preview'
input-file:
- Microsoft.ContainerInstance/preview/2017-12-01-preview/containerInstance.json
```

### Tag: package-2017-10-preview

These settings apply only when `--tag=package-2017-10-preview` is specified on the command line.

``` yaml $(tag) == 'package-2017-10-preview'
input-file:
- Microsoft.ContainerInstance/preview/2017-10-01-preview/containerInstance.json
```

### Tag: package-2017-08-preview

These settings apply only when `--tag=package-2017-08-preview` is specified on the command line.

``` yaml $(tag) == 'package-2017-08-preview'
input-file:
- Microsoft.ContainerInstance/preview/2017-08-01-preview/containerInstance.json
```

## Suppression

``` yaml
directive:
  - suppress: UniqueResourcePaths
    from: containerInstance.json
    reason: false positive, see https://github.com/Azure/azure-openapi-validator/issues/176
suppressions:
  - code: AvoidAdditionalProperties
    reason: Using additionalProperties type as the object is user-defined and not subject to any validations at RP level.
    from:
      - containerInstance.json
    where:
      - $.definitions.ConfigMap.properties.keyValuePairs
  - code: AvoidAdditionalProperties
    reason: additional feature addition to existing secretVolumes which is defined as a dictionary
    from:
      - containerInstance.json
    where:
      - $.definitions.SecretReferenceVolume
  - code: GetCollectionResponseSchema
    reason: We do not return the instanceView property in our List operation, we just return this 
            property for our Get operations. This change has been part of our stable api versions for a couple of years
    from:
      - containerInstance.json
    where:
      - $.paths["/subscriptions/{subscriptionId}/providers/Microsoft.ContainerInstance/containerGroups"]
```

---

# Code Generation

## Swagger to SDK

This section describes what SDK should be generated by the automatic system.
This is not used by Autorest itself.

``` yaml $(swagger-to-sdk)
swagger-to-sdk:
  - repo: azure-sdk-for-net
  - repo: azure-sdk-for-python
  - repo: azure-sdk-for-java
  - repo: azure-sdk-for-go
  - repo: azure-sdk-for-js
  - repo: azure-sdk-for-node
  - repo: azure-sdk-for-ruby
    after_scripts:
      - bundle install && rake arm:regen_all_profiles['azure_mgmt_container_instance']
  - repo: azure-resource-manager-schemas
  - repo: azure-powershell
```

## C#

See configuration in [readme.csharp.md](./readme.csharp.md)

## Go

See configuration in [readme.go.md](./readme.go.md)

## Java

See configuration in [readme.java.md](./readme.java.md)

## Node.js

See configuration in [readme.nodejs.md](./readme.nodejs.md)

## Python

See configuration in [readme.python.md](./readme.python.md)

## Ruby

See configuration in [readme.ruby.md](./readme.ruby.md)

## TypeScript

See configuration in [readme.typescript.md](./readme.typescript.md)
