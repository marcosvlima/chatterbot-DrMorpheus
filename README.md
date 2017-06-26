# DrWostraus
Um Chatterbot para tirar dúvidas sobre Inteligência Artificial

Este Chatterbot faz parte do trabalho de Inteligência Artificial do curso de
Ciência da Computação da Universidade Regional Integrada (URI) Campus Erechim.

Autor: Marcos Vinicius de Moura Lima
Orientador: Prof Marcos A. Lucas

Este chatterbot deverá ser executado em sistemas Linux com a versão do Python 2.7

## Instalar Python versão 2.7
- Dependencias python
udo apt-get install build-essential checkinstall
sudo apt-get install libreadline-gplv2-dev libncursesw5-dev libssl-dev libsqlite3-dev tk-dev libgdbm-dev libc6-dev libbz2-dev

- Obtenha a versão 2.7.13
cd ~/Downloads/
wget https://www.python.org/ftp/python/2.7.13/Python-2.7.13.tgz

- Extraia e vá para o diretório
tar -xvf Python-$version.tgz
cd Python-$version

- Instale o Python com estes comandos
./configure
make
sudo checkinstall

## Instalar dependencias do projeto
  sudo apt install python-pip
  pip install aiml

## Para instalar baixa esse projeto você deve digitar o seguinte comando no seu terminal
git clone https://github.com/marcosvlima/DrWostraus.git

## Para executar o chatterbot rode a seguinte linha de comando:
  sudo python wostraus.py

## Algumas considerações:

- Não digite as perguntas com ? (ponto de interrogação);
- Se você ficar perdido digite ajuda, que será retornado uma lista
de comandos disponíveis para utilizar.

OBS: Este projeto é um protótipo, melhorias futuras podem ser implementadas,
qualquer sugestão ou crítica mande um email para marcoslima.xv@gmail.com
