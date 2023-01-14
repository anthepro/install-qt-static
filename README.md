# install-qt-static
Prepare a static build of Qt.

# Usage

See [action.yml](action.yml)

### Example

```yaml
steps:
    uses: anthepro/install-qt-static@v1
    with:
      version: 6.4.2
      configure-args: -opensource -opengl desktop
      submodules: qtbase,qtshadertools,qtdeclarative
```
