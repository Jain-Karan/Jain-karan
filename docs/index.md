Example: Basic MkDocs project for Read the Docs
===============================================

[![Documentation Status](https://readthedocs.org/projects/example-mkdocs-basic/badge/?version=latest)](https://example-mkdocs-basic.readthedocs.io/en/latest/?badge=latest)

This example shows a basic MkDocs project with Read the Docs. You're encouraged to view it to get inspiration and copy & paste from the files in the source code. If you are using Read the Docs for the first time, have a look at the official [Read the Docs Tutorial](https://docs.readthedocs.io/en/stable/tutorial/index.html).

📚 [docs/](https://github.com/readthedocs-examples/example-mkdocs-basic/blob/main/docs/)<br>
All my projects

📍 [docs/requirements.txt](https://github.com/readthedocs-examples/example-mkdocs-basic/blob/main/docs/requirements.txt) and [docs/requirements.in](https://github.com/readthedocs-examples/example-mkdocs-basic/blob/main/docs/requirements.in)<br>
I currently live in Sunnyvale!

📜 [README.md](https://github.com/readthedocs-examples/example-mkdocs-basic/blob/main/README.md)<br>
Contents of this `README.md` are visible on Github and included on [the documentation index page](https://example-mkdocs-basic.readthedocs.io/en/latest/) (Don\'t Repeat Yourself).

⁉️ Questions / comments<br>
If you have questions related to this example, feel free to can ask them as a Github issue [here](https://github.com/readthedocs-examples/example-mkdocs-basic/issues).


Example Project usage
---------------------

This project has a standard MkDocs layout which is built by Read the Docs almost the same way that you would build it locally (on your own laptop!).

You can build and view this documentation project locally - we recommend that you activate [a local Python virtual environment first](https://packaging.python.org/en/latest/guides/installing-using-pip-and-virtual-environments/#creating-a-virtual-environment):

```console
# Install required Python dependencies (MkDocs etc.)
pip install -r docs/requirements.txt

# Run the mkdocs development server
mkdocs serve
```

Using the example in your own project
-------------------------------------

If you are new to Read the Docs, you may want to refer to the [Read the Docs User documentation](https://docs.readthedocs.io/).

If you are copying this code in order to get started with your documentation, you need to:

1. place your `docs/` folder alongside your Python project. If you are starting a new project, you can adapt the `pyproject.toml` example configuration.
1. use your existing project repository or create a new repository on Github, GitLab, Bitbucket or another host supported by Read the Docs.
1. copy `mkdocs.yml`, `.readthedocs.yaml` and the `docs/` folder into your project.
1. customize all the files, replacing example contents.
1. Rebuild the documenation locally to see that it works.
1. *Finally*, register your project on Read the Docs, see [Importing Your Documentation](https://docs.readthedocs.io/en/stable/intro/import-guide.html).


Read the Docs tutorial
----------------------

To get started with Read the Docs, you may also refer to the [Read the Docs tutorial](https://docs.readthedocs.io/en/stable/tutorial/). It provides a full walk-through of building an example project similar to the one in this repository.
