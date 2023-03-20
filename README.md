
# Automation API Generator

This project has created to relieve work load as SDET or Automation Test Engineer. In moderation, automation API code able to write with only run the script and generate from Postman collection. You just export the collection, and run the Generator to write the automation code.

## Objectives

1. Generate Postman collection with JSON format into Mocha-Chai template scripts
2. Applying DDT (data-driven test) mechanism to request API with a lot of datas in body request
3. Applying POM (page-object model) mechanism to request the API so it can be reused to another test file
4. Have default verification for status code and json-schema
5. Create scripts that easy to maintain

## List of Contents:
- [Prerequisite](docs/prerequisite.md)
- [Installation](docs/installation.md)
- [Lifecycle of Mocha Framework](docs/lifecycle.md)
- [Folder Structure and Usage](docs/folder.md)
  - [/runner](docs/folder.md#runner)
  - [/tests/data](docs/folder.md#testsdata)
  - [/tests/helper](docs/folder.md#testshelper)
  - [/tests/pages](docs/folder.md#testspages)
  - [/tests/scenarios](docs/folder.md#scenarios.md)
  - [/tests/schema](docs/folder.md#testsschema)
- [Scenarios](docs/scenarios.md)
  - [Default templates](docs/scenarios.md#default-templates)
  - [Default templates with body request](docs/scenarios.md#default-templates-with-body-request)
- [Pages](docs/pages.md)
  - [Default templates](docs/pages.md#default-templates)
- [Implementation](docs/implementation.md)
- [Best Practices](docs/practice.md)
- [Common Error](docs/error.md)
