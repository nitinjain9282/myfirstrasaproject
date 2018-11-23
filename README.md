# myfirstrasaproject
first rasa working project

You can read this guide or follow steps as listed here: https://rasa.com/docs/get_started_step2/  

Prerequistes:
1- install rasa_core and rasa_nlu python libraries. 

pip install -U rasa_core
pip install rasa_nlu[tensorflow]

2- Extract this zip to your local or clone your git repo

git clone https://github.com/nitinjain9282/myfirstrasaproject.git

3- create folder models/dialogue in your working directory

python -m rasa_core.run -d models/dialogue -u models/current/nlu

