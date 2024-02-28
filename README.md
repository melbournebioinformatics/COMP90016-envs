# COMP90016-envs
Environment settings for workshops in Computational Genomics

## Working with Gitpod

If working on this repo from a Gitpod workspace dependancies from the Dockerfile should be automatically installed 
and enabled in the base conda environment along with any packages listed in `requirements.txt`.

You will need to `conda install` any non-pip packages.

### Opening a Jupyter session from Gitpod

```bash
# Increase gitpod timeout setting
gp timeout set 6h

# Launch jupyter-lab
jupyter lab --NotebookApp.allow_origin='*' --NotebookApp.allow_remote_access=True --NotebookApp.token='' --NotebookApp.password='' --no-browser --port=8888

# or use jupyter-notebook
jupyter notebook --NotebookApp.allow_origin='*' --NotebookApp.allow_remote_access=True --NotebookApp.token='' --NotebookApp.password='' --no-browser --port=8888
```
The notebook will be available on port 8888 by default. You can open this port using the link in the `Ports` tab above the terminal.

**Note:** See other [gitpod settings](https://www.gitpod.io/docs/references/gitpod-cli#set) here.

## Binder
Open a [Binder](https://mybinder.org/v2/gh/melbournebioinformatics/COMP90016-envs/HEAD) session using the environment settings from this repo.
