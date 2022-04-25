# CERN openlab [![Made at CERN!](https://img.shields.io/badge/CERN-Open%20Source-%232980b9.svg)](https://home.cern) [![Made at CERN!](https://img.shields.io/badge/CERN-CERN%20openlab-brightgreen)](https://openlab.cern/)

This is the CERN openlab test page and here the instructions to get the best repository  ever!


## Project name, project webpage and project GitHub repository

- CERN Science for Open Data (CS4OD): [webpage](https://openlab.cern/index.php/project/cern-science-open-data/?target=_blank) and [repository](https://github.com/CERN/CS4OD/?target=_blank)


- [ ] Check if there already exists a respository associated to your project 

## Procedure to create a new remote repository in GitHub
  
- [ ] click on `new` 
- [ ] add Repository name
- [ ] add Description. Description must be the project's full name 
- [ ] be sure the repository is set to `Private`    
- [ ] flag `Add a README.md file`, 
- [ ] flag `Add .gitignore` and choose the desired programming language
- [ ] flag `Choose a license` and choose the desired license (choose MIT License if unknown)
- [ ] Create repository
- [ ] add repository topic: [procedure](https://docs.github.com/en/repositories/managing-your-repositorys-settings-and-features/customizing-your-repository/classifying-your-repository-with-topics). 
  Choose between:
  - [ ] ML (classical machine learning)
  - [ ] QML (quantum machine learning)
  - [ ] QTI (quantum technology initiative)
- [ ] use `main` branch for production-ready state only
- [ ] create `develop` branch for the latest delivered development changes for the next release
- [ ] create your development branch where each contributor works on a daily basis
 Use correct branching methods for a clean GitHub tree ([docs](https://gist.github.com/stuartsaunders/448036/5ae4e961f02e441e98528927d071f51bf082662f) and [example](https://nvie.com/posts/a-successful-git-branching-model/))
    
   
##  Requirements for the README
 Full description of the project
- [ ] Description of the project 
- [ ] How to install 
  - [ ] definition of virtual environment (anaconda/venv) used
  - [ ] instruction to install the package (requirements.txt or setup.cfg etc)
  - [ ] instruction how to run the code
- [ ] Quick start: minimal working example / tutorials / demos

##  Requirements for the CODE
- [ ] `requirements.txt` or `environment.yaml`(for conda) or `setup.cfg + pyproject.toml` or `setup.py`([setuptools](https://setuptools.pypa.io/en/latest/))
- [ ] `src/packagename` folder with source files
- [ ] formatting: production code must be formatted with [Black](https://github.com/psf/black)
- [ ] function annotations: augment all functions and modules with [dosctrings](https://sphinxcontrib-napoleon.readthedocs.io/en/latest/index.html)

##  Requirements before promoting the project from private to public
- [ ] `bibliography.md`: Zenodo link to external papers and datasets used
- [ ] Semantic versioning: comply with [semver.org](https://github.com/semver/semver/blob/master/semver.md) and [apache.org](https://apr.apache.org/versioning.html)
- [ ] documentation: using [readthedocs](https://docs.readthedocs.io/en/stable/tutorial/) and [simple formatting rules](https://hplgit.github.io/teamods/sphinx_api/html/sphinx_api.html). Please, use one of the following two standards: [Google's docstring](https://google.github.io/styleguide/pyguide.html) or [Numpy's docstring](https://numpydoc.readthedocs.io/en/latest/format.html#docstring-standard).
<!--
- [ ] [Sphynx](https://docs.readthedocs.io/en/stable/intro/getting-started-with-sphinx.html) with Napoleon theme and Autodoc, include it in `docs` folder
-->
- [ ] citation policy: how to use and cite the code (e.g. BibTex reference)




<!--

**Here are some ideas to get you started:**

🙋‍♀️ A short introduction - what is your organization all about?
🌈 Contribution guidelines - how can the community get involved?
👩‍💻 Useful resources - where can the community find your docs? Is there anything else the community should know?
🍿 Fun facts - what does your team eat for breakfast?
🧙 Remember, you can do mighty things with the power of [Markdown](https://docs.github.com/github/writing-on-github/getting-started-with-writing-and-formatting-on-github/basic-writing-and-formatting-syntax)

-->
