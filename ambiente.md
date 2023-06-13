# Terraform
Abaixo encontra-se as maneiras para se instalar o Terraform nos sistemas operacionais Ubuntu, MacOs e Windows.
### Ubuntu

Para instalar no Ubuntu, utilize o comando abaixo:

```wget -O- https://apt.releases.hashicorp.com/gpg | gpg --dearmor | sudo tee /usr/share/keyrings/hashicorp-archive-keyring.gpg
echo "deb [signed-by=/usr/share/keyrings/hashicorp-archive-keyring.gpg] https://apt.releases.hashicorp.com $(lsb_release -cs) main" | sudo tee /etc/apt/sources.list.d/hashicorp.list
sudo apt update && sudo apt install terraform
```
### MacOS

Para instalar no MacOS, instale através do brew com o comando abaixo:
```
brew tap hashicorp/tap
brew install hashicorp/tap/terraform
```
### Windows

Para instalar no Windows existem 2 possibilidades:

#### Chocolatey
```
choco install terraform
```
#### Instalação manual

Basta ir até a página de download, selecionar se qual a versão a ser baixada, dando preferência para 64-bit, extrair o arquivo e instalá-lo.

## Python
Caso você ainda não tenha instalado o Python, segue um pequeno tutorial de como fazê-lo.

### Ubuntu
Para instalar no Ubuntu, utilize o comando abaixo:
```
sudo apt install python3
```
### MacOS
Para instalar no MacOS, instale através do brew com o comando abaixo:
```
brew install python3
```
### Windows
Para instalar no Windows existem 2 possibilidades:

#### Chocolatey
```
choco install python
```
#### Instalação manual

Basta ir até a página de download, selecionar se qual a versão a ser baixada, extrair o arquivo e instalá-lo.

## Ansible
Caso você ainda não tenha instalado o Ansible, segue um pequeno tutorial de como fazê-lo.

### Ubuntu
Para instalar no Ubuntu, utilize o comando abaixo:
```
sudo apt update
sudo apt install software-properties-common
sudo add-apt-repository --yes --update ppa:ansible/ansible
sudo apt-get install ansible
```
### MacOS
Para instalar no MacOS, instale através do brew com o comando abaixo:
```
brew install ansible
```
### Windows
O Ansible não tem suporte nativo para Windows, porém é possível utilizar o pacote para Python para executá-lo.
```
python -m pip install --user ansible
python -m pip install --user paramiko
```
## AWS CLI
Caso você ainda não tenha instalado a AWS CLI, basta ir a página da AWS CLI e seguir os procedimentos para o seu sistema operacional.

Depois de instalado você pode configurar a AWS usando o comando aws configure onde será requisitado a chave secreta (secret key) que pode ser criada nessa pagina clicando em “criar chave de acesso” na aba “credenciais do AWS IAM”.

