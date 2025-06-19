# Installation in a conda environment
conda create -n envisionsumschool python=3.9
conda activate envisionsumschool
pip install -r requirements.txt

# if not work try
conda create -n envisionsumschool python=3.9
conda activate envisionsumschool
pip cache purge
pip install -r requirements.txt