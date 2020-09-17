![alt text](assets/CAPP_Logo.png "CAPP Logo")<font size="8"><span style="color:maroon">  CAPP-API</span></font>



Repository for the development of the basic elements of an API for the CAPP Software

---

# Reference Files

The links below provide detail on installation, style, and content issues. The files can be found in the CAPP-API/docs folder. Initial installations should read through the links sequentially for oroper set-up.

File name | Description
----------  | ------------
[INSTALLATION.md](./docs/INSTALLATION.md) |  Set-up information for Anaconda, python, and various packages
[VERSION CONTROL.md](./docs/VERSION_CONTROL.md) |  Set-up for Git versioning and push/pull protocols
[STYLE GUIDE.md](./docs/STYLE_GUIDE.md) |  Accepted conventions for project set-up and coding
[README_TEMPLATE.md](./docs/README_TEMPLATE.md) | Template for README files for new projects

# Project Information
File name | Description 
----------  | ------------
[CAPP ORGANIZATION.md](./docs/CAPP_ORGANIZATION.md) | Data structure and class heirarchy
[CAPP TIMELINE.md](./docs/CAPP_TIMELINE.md) | Evolving timeline of project goals and deadlines


# Documentation Creation Utilities


## Installing Sphinx and Sphinx Markdown Builder
```bash
source activate occ
pip install sphinx sphinx-markdown-builder
```

## Usage
```bash
source activate occ
# cd to CAPP-API main directory
cd .../CAPP-API 
# Build .rst files of python documentation
sphinx-apidoc -o "docs/source" "API Testing"
# Build .html files 
make html
# Build .md files (optional)
make markdown
```
