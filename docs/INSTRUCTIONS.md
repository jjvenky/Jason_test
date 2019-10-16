# Project Template Repository

This repository is designed to serve as a template for the curation and maintenance of data within a specific project. Projects may items such as a thesis chapter or a manuscript publication. 

## Minimum metadata requirements

All repositories should also contain a `README.md` file which details the following metadata, as appropriate:

1. Project title
2. Lead HQP
3. Other HQP
4. Lead PI
5. Other PI
6. Data sources
7. Funding sources

## Project structure
All project repos are named according to the associated grant and labelled with a short informative tag for the project (e.g. grant_projectname'). In addition, they contain the following folders:

1. **data |** will contain separate folders for `raw_data`, `clean_data`, and `processed_data`, as well as data from databases incorporated as submodules. For more information related to reading in and using submodules, see `docs/using_ubmodules.md`.
2. **code |** scripts and other code for processing and analyzing project information
3. **docs |** project notes, etc.
4. **output |** saved outputs (e.g. figures and tables) from analysis


## Creating a new project for storage from the GitHub website

1. Go to [GitHub's importer](https://github.com/new/import).

2. Paste the url of this repo as the old repository to clone: https://github.com/biogeochem/project_template

3. Select the owner for your new repository. (This will be the `biogeochem` organization since you want it to be integrated within the organization. It would be you as an individual user *only* if you want to use this template for something outside of the lab group.)

4. Choose a name for your new repository in the format of surname_projectname.

5. Fork the new repo from the lab group website https://github.com/biogeochem to your user account. Open your new repository and click `fork`at the top right.

6. Clone the repo from your user account. After forking the repo you will be forward to your own fork. Click `Clone or download`, copy the URL and use software such as [GitKraken](https://www.gitkraken.com/) or [SourceTree](https://www.sourcetreeapp.com/) or the command line (`git clone https://github.com/USERNAME/surname_projectname.git`).


## Creating a new project for storage from the command line

1. Create new, empty repo on the lab group website: https://github.com/biogeochem, e.g. surname_projectname
2. Clone --bare the project_template into a folder and give it a new name, e.g. project_fun. Note the .git extension. `git clone --bare https://github.com/biogeochem/project_template.git surname_projectname.git`
3. Push the new template-based repo to github. `cd surname_projectname.git && git push --mirror https://github.com/biogeochem/surname_projectname.git`
4. Remove the clone --bare folder, e.g. project_fun.git. `cd .. && rm -Rf ./surname_projectname.git`
5. Fork the new repo from the lab group website: https://github.com/biogeochem to your user account.
6. Clone the repo from your user account. `git clone https://github.com/USERNAME/surname_projectname.git`

See also https://help.github.com/articles/duplicating-a-repository/.

## Naming and formatting conventions
All files should follow the standardized naming convention outlined below:

- Dates: YYYY-MM-DD
- Text: UTF-8 encoding
- File names: descriptive and searchable


## Repository use
Students or collaborators wishing to use data from a repo must abide by the following guidelines.

*For more information about project maintenance, please contact **Kateri Salk** at krsalkgu@uwaterloo.ca or **Megan Larsen** at mlarsen@wlu.ca or  **Jason Venkiteswaran** at jvenkiteswaran@wlu.ca.*

