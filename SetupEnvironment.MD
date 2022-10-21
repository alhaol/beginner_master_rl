In the video we are going to create a programming environment from the 'environment.yml' file included in the code repository. We will do it with the command:

`conda env create -n <environment name> -f environment.yml`

The command works on Windows, Mac and Linux. However, if you have any problems creating it this way, you have two alternatives:

1) Create it manually using Anaconda:

`conda env create -n <environment name> python=3.8`

`conda activate <environment name>`

`conda install pyopengl pytorch==1.6 matplotlib pandas numpy tqdm jupyter seaborn scikit-learn`

`pip install gym`

2) using another package management system (such as venv):

`pip install pyopengl pytorch==1.6 matplotlib pandas numpy tqdm jupyter seaborn scikit-learn gym`
