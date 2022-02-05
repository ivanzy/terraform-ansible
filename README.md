# Terraform-Ansible - Infraestrutura como Código

Esse repositório contém o código desenvolvido durante o treinamento de Cloud da Grande Porte para criar duas instâncias t2.micro na AWS com IPs públicos. Iremos as utilizar para fazer aprender Ansible. 

## Execução

1. Faça o download do repósitório:
``` console
$ git clone https://github.com/ivanzy/terraform-ansible 
$ cd terraform-ansible\
```

2. Antes de executar o código - i.e., terraform apply -, altere as seguintes configurações no arquivo [terraform.tfvars](terraform.tfvars):

```
chave_pub = "<sua chave ssh pública>"
access_key = "<sua chave da aws>"
secret_key = "<sua chave secreta da aws>"
```

3. Provisione a infraestrutura com o Terraform:
``` console
$ terraform plan
$ terraform apply
```

4. Copiei os IPs públicos que serão printados no terminal e os adicione no arquivo host do ansible

