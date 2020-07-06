# Ministry of Justice Analytical Services GitHub Workflows
This repositiory is used to store standardised Workflow templates and associated configuration files for use in moj-analytical-services projects.

## Using moj-analytical-services Workflow Templates
- You can select a GitHub Workflow to use in your own project by navitagting to the Actions tab.
- If you're repository already contains Workflow files, select `New Workflow`, otherwise you can ignore this step.
- You'll then see will an option to add "Workflows created by MoJ Analytical Services".

## Adding Templates and Configs
This is a publicly visable repository so be considerate of adding sensitive or confidential material.
- If you want to add a Workflow template for your team,
    - create a folder in the `workflow-templates` directory using your team name,
    - add the Workflow template and the required metadata,
      - instructions on what is needed for the metadata can be found [here](https://docs.github.com/en/actions/configuring-and-managing-workflows/sharing-workflow-templates-within-your-organization#creating-a-workflow-template).

- Package configurations can be added to the repository and the associated GitHub Pages URL used to reference the configuration in a Worklow template.

## URL Format
The GitHub Pages URL for this repo is:

`https://moj-analytical-services.github.io/.github/`

You can navigate using teh following URL format:

`https://moj-analytical-services.github.io/.github/[workflow-templates]/[team_name]/[file_name]`
