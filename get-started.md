# Get Started

## Organization

A few Jupyter Notebooks are made available in this website. You can view the notebooks, or you can run them interactively (so you can also follow the exercises).

## Run code interactively

Available options:
- In the cloud via `mybinder.org` (easiest)
- Locally

### Mybinder.org

Clicking [![Binder](https://mybinder.org/badge_logo.svg)](https://mybinder.org/v2/gh/UU-IMAU/xarray-UNECSS-2026/HEAD) will load a pre-configured Jupyter Lab interface with the notebooks for you to run. _You will have minimal computing resources and any changes you make will not be saved_, but its more than sufficient for this tutorial. Any page with executable content also has a {octicon}`rocket;2em` icon in the upper right that will launch an interactive session for that particular page.

### On your computer

Running tutorials on your computer requires some setup:

We recommend using [`pixi`](https://pixi.sh/latest/) to ensure a fully reproducible Python environment

```bash
git clone https://github.com/UU-IMAU/xarray-UNECSS-2026
cd xarray-UNECSS-2026
pixi run tutorial
```

If you prefer to use conda/mamba:

```
mamba env create -f .binder/environment.yml -n unecss-xarray
conda activate unecss-xarray
jupyter lab
```


<!-- 
#### GitHub Codespaces

This tutorial is available to run within [GitHub Codespaces](https://github.com/features/codespaces) - a preconfigured development environment running in Microsoft Azure.

[![Open in GitHub Codespaces](https://github.com/codespaces/badge.svg)](https://github.com/codespaces/new/xarray-contrib/xarray-tutorial)

☝️ Click the button above to go to options window to launch a GitHub codespace.

You can choose from a selection of virtual machine types: 2 cores - 8 GB RAM should be sufficient for all code examples in this repository.
Additionally, you are able to chose from various configurations for specific workshops (such as Scipy2024).
GitHub currently gives every user [120 vCPU hours per month for free](https://docs.github.com/en/billing/managing-billing-for-github-codespaces/about-billing-for-github-codespaces#monthly-included-storage-and-core-hours-for-personal-accounts), beyond that you must pay. **So be sure to explicitly stop your codespace when you are done by going to this page (https://github.com/codespaces).** You can also chose to fully delete your codespace when you're done exploring tutorial content.

```{tip}
By default Codespaces open VSCode in a browser window. But you can also launch a JupyterLab interface. Once you've launched a codespace, use the auto-generated name in the following URL: `https://github.com/codespaces/CODESPACE-NAME?editor=jupyter`
```

Using the GitHub CLI is another very convenient way to start a codespace:

```bash
gh codespace create -R xarray-contrib/xarray-tutorial
```

```bash
# Wait a few minutes for `gh codespace create` to finish, then run:
gh codespace jupyter
``` -->


