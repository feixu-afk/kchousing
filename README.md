# kchousing

GitHub Site: https://github.com/feixu-afk/kchousing

Development workflows
=======================

Create new project
----------------------

```bash
cookiecutter gh:feixu-afk/cookiecutter-datascience-simple
```

Put project under version control
---------------------------------

```bash
git init
git add *.py
git add *.ipynb
git add .gitignore
git add *.html
git add docs/*.md
git commit -m "Initial commit"
```

Data files are not tracked.
For the remote repository, I made a GitHub repository named kchousing.

```bash
git remote add origin git@github.com:feixu-afk/kchousing.git
git branch -M main
```

Then, I used GitHub Desktop to push my local commit up to GitHub.


Folder structure
-----------------

Here's the folder structure that gets created by `cookiecutter-datascience-simple`:

	├── kchousing	<- Your notebooks and scripts will live in the main project folder
		│   .gitignore					<- Common file types for git to ignore
		│   README.md					<- The top-level README for developers (you) using this project
		│   template-nb.ipynb			<- A Jupyter notebook template
		│
		├───data						<- Final and intermediate data
		│   └───raw						<- The original, immutable data dump
		│
		├───docs
		│       notes.md				<- Simple markdown template for project notes
		│
		└───output
				readme.md				<- Guidance for using this folder

After adding files, my folder structure looks like:

	├──kchousing
        |   .gitignore
        |   aap_hw1_s26_sklearn.ipynb
        |   hw1_sklearn_dataprep.ipynb
        |   kchousing.ipynb
        |   kchousing.html
        |   README.md
        |
        ├───data
        |   |   kc_house_data_classification.csv
        |   |   kc_house_data_regression.csv
        |   |
        |   └───raw
        |           .gitkeep
        |           kc_house_data_original.csv
        |
        ├───docs
        |       notes.md
        |
        └───output
                pandas_profiling_report.html
                readme.md
                sweetviz_report.html
                

Documentation
--------------

- `kchousing.ipynb`
  Contains the main analysis. (Both of the automated EDA tools, ydata-profiling and SweetViz, work fine in Jupyter Lab)






