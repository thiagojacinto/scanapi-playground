# ScanAPI: a playground
Using ScanAPI testing tool to test open APIs 

## Install & Using

You may install the project dependencies by using the following command:
```sh
git clone https://github.com/thiagojacinto/scanapi-playground.git # clone this repository from GitHub

cd scanapi-playground # move to local repository directory

# it is recommended to use Python virtual enviroment
python3 -m venv .venv
source .venv/bin/activate

python -m pip install -r requirements.txt # read the dependencies and install the available versions
```

## APIs

Open APIs

### conexaoqa.heroku.app

Open API developed to be used as training ground to testers at the [Virada da Qualidade](https://iterasys.com.br/curso/virada-da-qualidade/) July 2021 event.

You can find its documentation [here](https://conexaoqa.herokuapp.com/api-docs/#/)

#### Running tests

To run tests, please procced with the installation of requirements, than you should be able to execute ScanAPI with the following commands:
```shell
scanapi run -c api-conexaoQA/scanapi.conf
```