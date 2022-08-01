# BibTeX helper

BibTeX helper is an extension for Visual Studio Code that provides a collection of simple snippets for BibTeX files.
For more information on entry types and a list of keywords read the [BibTeX documentation](https://ctan.joethei.xyz/biblio/bibtex/base/btxdoc.pdf).

## Features

BibTeX helper features the following entry types:
| Description | Entry Type |
| ----------- | ----------- |
| Article | `article` |
| Book | `book` |
| Multi-volume Book | `mvbook` |
| Inbook | `inbook` |
| Book in Book | `bookinbook` |
| Supplemental Material in Book | `suppbook` |
| Booklet | `booklet` |
| Collection | `collection` |
| Multi-volume Collection | `mvcollection` |
| In Collection | `incollection` |
| Supplemental Material in Collection | `suppcollection` |
| Manual | `manual` |
| Miscellaneous | `misc` |
| Online Resource | `online`, `www` |
| Electronic Resource | `electronic` |
| Patent | `patent` |
| Periodical | `periodical` |
| Supplemental Material in Periodical | `suppperiodical` |
| Proceedings | `proceedings` |
| Multi-volume Proceedings | `mvproceedings` |
| Article in Conference Proceeding | `inproceedings` |
| Reference | `reference` |
| Multi-volume Reference | `mvreference` |
| In Reference | `inreference` |
| Report | `report` |
| Thesis | `thesis` |
| Master's Thesis | `mastersthesis ` |
| PhD Thesis | `phdthesis` |
| Technical Report | `techreport` |
| Unpublished | `unpublished` |
| Conference | `conference` |

## Usage

Open a BibTeX file in VS Code and either type in the name of the BibTeX entry or use Ctrl+Space to show a list of all available snippets.


## Requirements

This extension does not require any additional extensions to be installed.

## Extension Settings

Although this extension does not have any settings, you may need to add the following setting to your `.vscode/settings.json` file to use the extension:

```json
"[bibtex]": {
    "editor.quickSuggestions": {
        "other": "on",
        "comments": "on"
    }
}
```
---

## Release Notes

### 1.0.0

Initial release of the BibTeX helper extension.
##### Features
- BibTeX snippets for all entry types


