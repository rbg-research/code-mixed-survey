# Clone Repo
```commandline
git clone https://github.com/rbg-ai/code-mixed-survey.git
cd code-mixed-survey
```

# Python Installation
```commandline
sudo add-apt-repository ppa:deadsnakes/ppa -y
sudo apt-get update
sudo apt-get install python3.10
sudo apt-get install python3.10-dev
```

# PIP Installation
```commandline
wget https://bootstrap.pypa.io/get-pip.py
python3.10 get-pip.py
rm -r get-pip.py
nano .bashrc
export PATH="$HOME/.local/bin:$PATH"
source .bashrc
pip3.10 install -U pip
```

# Create Virtual Environment
```
mkdir $HOME/environments
pip3.8 install -U virtualenv
virtualenv ~/environments/cms
source ~/environments/cms/bin/activate
pip install -r requirements.txt
```

# Add Kernel to Jupyter
```
pip install ipykernel
python -m ipykernel install --user --name=cms
```

# MISC
```
sudo apt install ffmpeg
```
