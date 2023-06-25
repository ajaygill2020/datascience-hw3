# Homework 3

Information on using this cookiecutter. 

Development workflows
=======================

Create new project
----------------------

You've already done this if you are reading this file. You ran:

```bash
cookiecutter gh:ajaygill2020/cookiecutter-datascience-simple
```

Put project under version control
---------------------------------

Let's get version control set up. You don't absolutely have to do this, but you should. For the local repository, do;

```bash
git init
git add .
git commit -m "Initial commit"
```

For the remote repository, make a github repository named homework_3, then do;

```bash
git remote add origin git@github.com:ajaygill2020/homework_3.git
git branch -M main
git push -u origin main
```

Great. Using version control is good.


Folder structure
-----------------

Here's the folder structure that gets created by `cookiecutter-datascience-simple`:

	├── homework_3	<- Your notebooks and scripts will live in the main project folder
		│   .gitignore					<- Common file types for git to ignore
		│   README.md					<- This README file
		│   main_homework_file.ipynb			<- Jupyter notebook where the work is done.
		│
		├───data						<- Includes .png images of our models
		│
		└───output								<- Includes the logs as .csv files



Documentation
--------------

In this homework assignment, I will create a simple Airport simulation model using DES with Simpy. While three models are shown in the "main_homework_file.ipynb" notebook, the last model is the most complex out of the three.  



