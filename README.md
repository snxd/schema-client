## DIRECT Client Schemas

These schemas define valid workflow, app config, and window config documents. They can be used to valid documents in either JSON or YAML formats.

* [Application Configuration](app.json)
* [Window Configuration](window.json)
* [Workflow](workflow.json)

## Usage

To use YAML schemas with Visual Studio Code:

* First install the _YAML Extension_
* Add the following comment with the correct URL to the top of your document:

**Application Configuration**
```yaml
# yaml-language-server: $schema=https://raw.githubusercontent.com/snxd/schema-client/<version>/app.json
```

**Window Configuration**
```yaml
# yaml-language-server: $schema=https://raw.githubusercontent.com/snxd/schema-client/<version>/window.json
```
**Workflow**
```yaml
# yaml-language-server: $schema=https://raw.githubusercontent.com/snxd/schema-client/<version>/workflow.json
```

* Replace the `<version>` in the URL with the version of the DIRECT client you are using.
* To view validations problems show the Problems tool pane.
* To activate auto-complete press CTRL+Space in your YAML file.
