# InnoSetupAction

This action can be used to create installer for any application in the workflow.

It bassed on InnoSetup, which is Inno Setup is a free installer for Windows programs by Jordan Russell and Martijn Laan...[more](https://jrsoftware.org/isinfo.php)

### Inputs
#### `filepath`
**Required**
**Description** - Path for ISS file

### Usage
First, you need to create InstallerScript.iss and insert it into the source code.
after that you use it in your workflow.

```
- uses: zhangt58/InnoSetupAction@v6.4.3
  with:
    filepath: '<filepath for the .iss>'
```
