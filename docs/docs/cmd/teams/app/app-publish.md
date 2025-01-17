# teams app publish

Publishes Teams app to the organization's app catalog

## Usage

```sh
m365 teams app publish [options]
```

## Options

`-p, --filePath <filePath>`
: Absolute or relative path to the Teams manifest zip file to add to the app catalog

--8<-- "docs/cmd/_global.md"

## Remarks

You can only publish a Teams app as a global administrator.

## Examples

Add the _teams-manifest.zip_ file to the organization's app catalog

```sh
m365 teams app publish --filePath ./teams-manifest.zip
```

## Response

=== "JSON"

    ```json
    "fbdfd207-83ee-45d8-9c98-5039a1a01207"
    ```

=== "Text"

    ```text
    fbdfd207-83ee-45d8-9c98-5039a1a01207
    ```

=== "CSV"

    ```csv
    fbdfd207-83ee-45d8-9c98-5039a1a01207
    ```
