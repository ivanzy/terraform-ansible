# terraform-ansible

Esse repositório contém o código desenvolvido durante o treinamento de Cloud da Grande Porte para criar duas instâncias t2.micro na AWS com IPs públicos. Iremos as utilizar para fazer aprender Ansible. 

## Instalação

Faça o download do repósitório
``` console
$ git clone https://github.com/ivanzy/terraform-ansible 
$ cd terraform-ansible\
```

Antes de executar o código - i.e., terraform apply -, altere as seguintes configurações no arquivo terraform.tfvar:

```
chave_pub = "<sua chave ssh pública>"
access_key = "<sua chave da aws>"
secret_key = "<sua chave secreta da aws>"
```
