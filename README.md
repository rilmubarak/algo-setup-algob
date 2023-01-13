# algo-setup-algob
Algorand Node Environment Setup - SDK

1. yarn init
2. yarn add @algo-builder/algob@3.2.0
3. yarn run algob init .
4. pipenv -> to install project environment
5. pipenv shell -> to run virtual environment

Install python VSCode extension:
1. Install python vs code extension from microsoft 
2. press ctrl-shift-p to select python interpreter
3. select Python with python3 source

Install pyyaml:
- pip3 install pyyaml

after environment is set up:
1. yarn run algob deploy -> to deploy the contracts (dont forget to adjust the add & mnemonic)