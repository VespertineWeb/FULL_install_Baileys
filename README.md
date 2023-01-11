
```bash
sudo apt -y update && apt -y upgrade
```
```bash
adduser deploy
```
usermod -aG sudo deploy

FAZENDO DOWNLOAD DO INSTALADOR & INICIANDO A PRIMEIRA INSTALAÇÃO:

```bash
sudo apt install -y git && git clone https://github.com/VespertineWeb/FULL_install_Baileys.git && sudo chmod -R 777 FULL_install_Baileys && cd FULL_install_Baileys && sudo ./install_primaria
```

ACESSANDO DIRETORIO DO INSTALADOR & INICIANDO INSTALAÇÕES ADICIONAIS:
```bash
cd ./FULL_install_Baileys && sudo ./install_instancia
```

