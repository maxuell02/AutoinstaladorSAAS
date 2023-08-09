---------------------------------------------------------------------------------------------------------------------------------------------------

SELECIONE E COPIE (TECLA "Ctrl" + A TECLA "C") O CODIGO ABAIXO E NO TERMINAL DE UM CLIQUE COM O BOTAO DIREITO QUE O CODIGO JA APARECE NO TERMINAL, APOS ISSO APERTE A TECLA "ENTER"
```bash
sudo apt-get update && sudo apt-get upgrade -y
```

FAZENDO DOWNLOAD DO INSTALADOR & INICIANDO A PRIMEIRA INSTALAÇÃO (USAR SOMENTE PARA PRIMEIRA INSTALAÇÃO):

```bash
sudo apt install -y git && git clone https://github.com/maxuell02/AutoinstaladorSAAS.git install_whaticket && sudo chmod -R 777 install_whaticket  && cd install_whaticket  && sudo ./install_primaria
```

ACESSANDO DIRETORIO DO INSTALADOR & INICIANDO INSTALAÇÕES ADICIONAIS (USAR ESTE COMANDO PARA SEGUNDA OU MAIS INSTALAÇÃO:
```bash
cd && cd ./install && sudo ./install_instancia
```

