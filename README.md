# Thyroid-Function-Test

Thyroid Function Test (M2) - PH664

## Requirements

[Docker](https://docs.docker.com/install/) and [CWLTool](https://github.com/common-workflow-language/cwltool#install)

## Configuration

Specify data source credentials in [js/read-potential-cases-fhir.js](js/read-potential-cases-fhir.js).

## Usage

Run: `cwltool Thyroid-Function-Test.cwl Thyroid-Function-Test-inputs.yml`

***

### Based on original definition developed by S Jill Stocks, Evangelos Kontopantelis, Artur Akbarov, Sarah Rodgers, Anthony J Avery, Darren M Aschroft
### Generated by [Phenoflow](https://kclhi.org/phenoflow).
