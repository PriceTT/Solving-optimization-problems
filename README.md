# Solving optimization problems with Pyomo/Gekko

<p align="center">
  <img src="img.png">
</p>

## Current Features


## TODO



## Running locally 

### Prerequisites

* Install WSL 2: https://learn.microsoft.com/en-us/windows/wsl/install
* Install anaconda: https://www.hostinger.com/tutorials/how-to-install-anaconda-on-ubuntu/
* Install git: https://www.digitalocean.com/community/tutorials/how-to-install-git-on-ubuntu-20-04
* Create ssh key ```ssh-keygen```and add it to your git repo https://gitlab.nzcorp.net/-/profile/keys

### Set up ENV
These are the steps to get started with the app:
1. Clone the repository `git clone git@github.com:PriceTT/chat-assistant.git`.
2. Create the virtual environment using conda and poetry. The basic commads are as follows: 
    * Navigate to project folder and run the command below to the create conda environment which reads the environment.yml file.  
    ``` conda env create ```  
    * Activate the virtual environment  with
    ```conda activate opt-env```
    * Install the packages using poetry (retry if it fails)
    ``` poetry install -vvv  ```
    * To update the packages 
   ``` poetry update ```
    * To remove the env
   ``` conda env remove --name opt-env ```
   * The interpreter path can be found by tying  ```which python```

3. Once the environment is activated test with one of the notbooks.  

