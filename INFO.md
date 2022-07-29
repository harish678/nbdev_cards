## nbdev commands

```
nbdev_bump_version              Increment version in settings.ini by one
nbdev_clean                     Clean all notebooks in `fname` to avoid merge conflicts
nbdev_conda                     Create and upload a conda package
nbdev_create_config             Create a config file
nbdev_deploy                    Deploy docs to GitHub Pages
nbdev_docs                      Generate docs
nbdev_export                    Export notebooks in `path` to Python modules
nbdev_filter                    A notebook filter for Quarto
nbdev_fix                       Create working notebook from conflicted notebook `nbname`
nbdev_ghp_deploy                Deploy docs in `doc_path` from settings.ini to GitHub Pages
nbdev_help                      Show help for all console scripts
nbdev_install                   Install Quarto and the current library
nbdev_install_hooks             Install git hooks to clean and trust notebooks automatically
nbdev_install_quarto            Install latest Quarto on macOS or Linux, prints instructions for Windows
nbdev_migrate_directives        Convert all directives in `fname` from v1 to v2
nbdev_new                       Create a new project from the current git repo
nbdev_prepare                   Export, test, and clean notebooks
nbdev_preview                   Start a local docs webserver
nbdev_pypi                      Create and upload Python package to PyPI
nbdev_quarto                    Create Quarto docs and README.md
nbdev_release                   Release both conda and PyPI packages
nbdev_sidebar                   Create sidebar.yml
nbdev_test                      Test in parallel notebooks matching `fname`, passing along `flags`
nbdev_trust                     Trust notebooks matching `fname`
nbdev_update                    Propagate change in modules matching `fname` to notebooks that created them
```

## test package locally

Once the notebooks has been exported using `nbdev_export` command, the package will be created in the present working directory.

Run the command `pip install -e .` to install the generated package to install locally.
