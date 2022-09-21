<div align="center">

<img src="icon.png" alt="icon" width=200 />

# Seabrook

An _aesthetically pleasing_ theme for Visual Studio Code.

<a href="https://vscode.dev/theme/sortbyfirstname.seabrook/Seabrook%20Dark">
    <img alt="Preview in vscode.dev" src="https://img.shields.io/badge/preview%20in-vscode.dev-blue">
</a>
<img alt="Visual Studio Marketplace Last Updated" src="https://img.shields.io/visual-studio-marketplace/last-updated/sortbyfirstname.seabrook">
<img alt="GitHub issues" src="https://img.shields.io/github/issues-raw/sortbyfirstname/seabrook-vscode-theme">

<br />

## __Light mode coming soon!__

<br />

</div>

### Seabrook Dark 

![Screenshot 1](static/screenshot1.png)

---

## Disabling italics
If you would like to disable italics, you can add the following to your [settings.json](https://code.visualstudio.com/docs/getstarted/settings#_settings-file-locations) file:
```json
"editor.tokenColorCustomizations": {
        "[Seabrook Dark]": {
            "textMateRules": [{
                "scope": [
                    "comment",
                    "invalid",
                    "keyword",
                    "entity.other.attribute-name"
                ],
                "settings": {
                    "fontStyle": ""
                }
            }]
        }
    }
```