

### Set-up


#### 1a) Install Environment:
conda create -n poke python=3  
conda activate poke
conda install anaconda

Add 'poke' kernel to jupyter
conda install ipykernel
python -m ipykernel install --user --name poke
(poke)$
You can then start Jupyter by running

(poke)$ jupyter notebook
When starting a new notebook in Jupyter, you should select "Kernel -> Change Kernel -> "poke" before running.


(option)
#### 1b) Use existing Environment: 
pip install -r requirements.txt

(switch kernel to your kernel of choice) 




#### 2) make sure to move the 'DS_pokemon_trainer_application_data.csv' to the local directory
