# django-ava
Ambiente virtual de aprendizado utilizando django para estudo

## Python
Utilizaremos o python 3.5.1 para nosso desenvolvimento, pois essa versão tem suporte nos serviços de hospedagem compartilhada Hostgator.

## Ambiente Virtual
Para rodar o projeto é necessário instalação de alguns pacotes. Uma das formas mais interessantes de se criar um ambiente virtual é com o `pyenv`. Para instalar o `pyenv` no seu Linux, siga o tutorial [nesse link](https://medium.com/data-hackers/guia-de-instala%C3%A7%C3%A3o-do-pyenv-no-ubuntu-16-04-18-04-33a33faa4d5). Após instalação, vamos criar um ambiente virtual para o nosso projeto, compatível com o ambiente da hospedagem.
```sh
cd pasta_do_projeto
pyenv install 3.5.1 # Instalamos na máquina o python 3.5.1
pyenv local 3.5.1 # Declaramos o python que queremos utilizar na pasta atual
pyenv virtualenv venv-django-ava # Criar um ambiente virtual com python 3.5.1 de nome venv-django-ava
pyenv local venv-django-ava
```
Repare que após esse comando um arquivo de nome `.python-version` foi criado na pasta do projeto. Ele é a instrução de que ambiente virtual ou verso do python você quer utilizar naquela pasta. No caso estará escrito `venv-django-ava`.

