# COMP3850 Group 23 Ant posture tracking

## Contribution guide

1. Clone this repository to your local machine.
2. Create a new personal branch from the main branch.
3. Make all of your changes to your personal branch.
4. When your changes are ready to merge with the main branch,
    1. Push your changes to the remote repository.
    2. Open a pull request to merge your personal branch into the main branch.
    3. Notify the repository owner to accept the pull request.
5. Make sure to pull into your local repository regularly.

## Directory structure

/datasets - labelled datasets  
/models - trained models  
/notebooks - Jupyter notebooks  
/docs - documents replicated from Google Docs

## Instructions
### Creating a SLEAP environment

    mamba create -y -n sleap -c conda-forge -c nvidia -c sleap -c anaconda sleap=1.3.3
    mamba activate sleap
    sleap-label

### Creating a Jupyter Notebook environment with SLEAP

    mamba create -n jupyter -c conda-forge -c anaconda -c nvidia -c sleap sleap=1.3.3 jupyterlab
    mamba activate jupyter
    jupyter notebook
