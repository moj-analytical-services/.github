# Ministry of Justice Analytical Services GitHub Workflows
This repositiory is used to store standardised workflow templates and associated configuration files for use in moj-analytical-services projects.

## Using moj-analytical-services Workflow Templates
- You can select a GitHub workflow to use in your own project by navitagting to the Actions tab on GitHub.
- If your repo already contains workflow files, select `New Workflow`, otherwise ignore this step.
- You'll then see an option to add "Workflows created by MoJ Analytical Services".

## Adding Templates and Configs
This is a publicly visable repo so be sure not add any sensitive or confidential material.
- If you want to add a workflow template for your team,
    - create a folder in the `workflow-templates` directory using your team name,
    - add the workflow template and the required metadata,
      - instructions about how to create the metadata file can be found [here](https://docs.github.com/en/actions/configuring-and-managing-workflows/sharing-workflow-templates-within-your-organization#creating-a-workflow-template).

- Package configurations can be added to the repository and the associated GitHub Pages URL used to reference the configuration in a Worklow template.

## URL Format
The GitHub Pages URL for this repo is:

`https://moj-analytical-services.github.io/.github/`.

You can navigate to a config file using the following URL format:

`https://moj-analytical-services.github.io/configs/<team-name>/<file-name>`.
