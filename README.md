# synXLIFF

The main purpose of this repo is to track issues for the latest version of synXLIFF.

Download link: https://www.synalis.de/synxliff/

If you encounter any problems regarding a translation of synXLIFF feel free to create a pull request.
We will then look into it.

Also if your language is still missing you can create a pull request with the translated xliff file.

### Changelog

#### Version 1.0.0.1

- fixed an issue with actions that were not shown
- fixed an error when importing file with "maxwidth" attribute

#### Version 1.0.1.0

- added support for files which where already translated before using Dynamics LCS
- synXLIFF now automatically checks for a new version on a daily base
  - the check is executed "OnOpenPage" on "synXLIFF Project List"
  - in the new setup table you can:
    - deactivate the automatic check
    - check manually for updates if you want to
  
