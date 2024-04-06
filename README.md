Build development environment using pixi
----------------------------------------

1. In Windows, use the following command to install pixi(used windows powershell):  

    iwr -useb https://pixi.sh/install.ps1 | iex

2. Use pixi command to ensure you got pixi setup:

    pixi

3. Initialize a new project:

    pixi init <project_name>

4. Copy the python file to the newly created project and navigate to project directory:

    cp <.\file.py> <.\project_name> 

    cd <.\project_name>

5. Use python add command to add dependencies for the project:

    pixi add python wandb numpy matplotlib scikit-learn optuna

6. Run the file:

    pixi run python <file.py>
