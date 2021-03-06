# udata-schema-gouvfr

This udata plugin provides an integration with [schema.data.gouv.fr](https://schema.data.gouv.fr)

## Features

- Adds a schema button to resources with a schema
- Displays a modal when clicking this button providing links to documentation and validation


## Usage

Install the plugin package in your udata environement:

```bash
pip install udata-schema-gouvfr
```

Then activate it in your `udata.cfg`:

```python
PLUGINS = ['schema-gouvfr']
```

## Configuration

You can control this plugin behavior with the following `udata.cfg` parameters:

- **`SCHEMA_GOUVFR_VALIDATA_URL`**: the URL to your [Validata](https://validata.fr/) instance (without trailing slash). **ex:** `https://validata.etalab.studio`
