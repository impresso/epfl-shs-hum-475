# EPFL SHS HUM475 

A few instructions to start working with _impresso_ data exports in the context of the HUM-475 class.

### Working with noto

Noto is the EPFL’s JupyterLab centralized platform for education which allows teachers and students to use Jupyter notebooks online without having to install anything on their computer.

- clone this repository `git clone https://github.com/impresso/epfl-shs-hum-475.git`
- go to [https://noto.epfl.ch/](https://noto.epfl.ch/) and login with your gaspar credentials.
- upload the example notebook and your data.

### Setting up your working environment locally

#### Python environment

1. Download [Anaconda](https://www.anaconda.com/distribution/) in order to get the Conda environement manager.
2. Familiarize yourself with [Conda](https://conda.io/docs/user-guide/getting-started.html)
3. Open a terminal, go to your working repository and create an environement:
`conda create -n NAME python=3.6` where NAME is the name you want to give to the environement (e.g. digital-history)
4. Activate it:
`source activate NAME`
5. install dependencies with `pip install -r requirements.txt`

Useful commands (and more info [here](https://conda.io/docs/user-guide/tasks/manage-environments.html)):

```
conda info --envs => list your environments
source deactivate => deactivate an env
conda remove --name NAME --all => remove environment 'NAME'
```

#### Working with Jupyter notebook

What it is: see this [tutorial](https://www.datacamp.com/community/tutorials/tutorial-jupyter-notebook)

Conda already installs by default Jupyter when you create an environment.

To launch a notebook, just execute this in your activated env:
`jupyter notebook`

#### Starting working with the data

We've put a jupyter notebook in this repo ([explore_export.ipynb](https://github.com/impresso/epfl-shs-class-2021-2022/blob/main/notebooks/explore_export.ipynb)) where you can get an idea where to start.

If you want to use Iramuteq, you will have to isolate the textual parts and print them as specified [here](http://www.iramuteq.org/documentation/formatage-des-corpus-texte).


### Scripts developed by previous students

Contribution from previous years' groups who developed a script to process the data before importing into Iramuteq.
    
- Projet sur l'OPEP: [scripts](https://github.com/RPetitpierre/letemps_archive_opep), [rapport](https://wp.unil.ch/histoireparlesdonnees/de-la-creation-de-lopep-a-son-role-durant-la-deuxieme-crise-petroliere-le-point-de-vue-des-quotidiens-bourgeois-romands/).
- Projet sur le secret bancaire: [scripts](https://github.com/RomainMendez/Digital-Humanities-Project), [rapport](https://wp.unil.ch/histoireparlesdonnees/le-secret-bancaire-suisse-au-xxe-siecle-dans-le-journal-de-geneve-et-la-gazette-de-lausanne/).
- Projet sur la relation americano-soviétique: [scripts](https://github.com/AAA97AAA/Gorbi/blob/master/finalV2.ipynb), [rapport](https://wp.unil.ch/histoireparlesdonnees/de-la-relation-americano-sovietique-de-1981-a-1991/).
