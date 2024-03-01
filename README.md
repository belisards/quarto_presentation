# Quarto presentation template

Boilerplate code for Quarto presentations integrated with GitHub Actions.

You can check the presentation template here: [https://belisards.github.io/quarto_presentation/](https://belisards.github.io/quarto_presentation/)

This demo presentation was copied from [Quarto website](https://quarto.org/docs/presentations/).

# Files

`.github/workflows/publish.yaml`: Render the Quarto document after every push to the repository. The HTML files are exported to the `gh-pages` branch.

`index.qmd`: The main Quarto document. This is the file you should edit.

# Instructions

1. Fork this repository.

2. Edit the file `index.qmd`. Tip: you can press dot (`.`) to edit the repository on Github using a web-based version of VS Code.

3. Click "Settings" in your repository, then choose "Actions" in the menu. Set "Workflow permissions" to "Read and write permissions".

4. Now, choose "Github Pages" and check if "Source" is set to "Deploy from branch" and "Branch" to "gh-pages" and "Root".

5. The site should now be available at <your_username>.github.io/<your_repository>.
