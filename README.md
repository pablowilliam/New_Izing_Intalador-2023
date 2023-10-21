Interactive CLI tool for installing and updating Izing.io

### download & setup

Primeiramente, você precisa fazer o download:


```bash
sudo apt -y update && apt -y upgrade
sudo apt install -y git
git clone https://github.com/pablowilliam/New_Izing_Intalador-2023.git


Agora, precisa dar as permissões:

```bash
sudo chmod +x ./New_Izing_Intalador-2023/izing
```

### usage

Após o download e as permissões estarem como executável, você precisa **navegar dentro** do diretório e **dar o comando com o sudo**:

```bash
cd ./New_Izing_Intalador-2023

```

```bash
sudo ./izing
```

### Ports Local
Instalacao Local usar IP:PORTA

API - 3000

Front - 3333

Admin - 3334


### Instalação Ubuntu 22.04 

editar o ARQUIVO  /etc/needrestart/needrestart.conf , alterando a linha:

#$nrconf{restart} = 'i';

para

$nrconf{restart} = 'a';



### Comments

redis and postgresql password: password
Rabbitmq password: guest / guest
User: Deploy Password: password

