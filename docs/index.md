# Estudo do Ansible

## Sobre o projeto
<p> Repositório destinado ao estudo da ferramenta Ansible, é uma ferramenta de provisionamento de software de código aberto, gerenciamento de configuração e ferramenta de implantação de aplicativos que habilita a infraestrutura como código.
</p>

## 0. Instalação 
<p> Para execução desse projeto , primeiramente, necessário a instalação dos seguintes programas: 
</p>

* <a href = "https://docs.ansible.com/ansible/latest/installation_guide/intro_installation.html?extIdCarryOver=true&sc_cid=701f2000001OH7YAAW" > Ansible. </a>

* <a href = "https://www.virtualbox.org/wiki/Downloads" > Virtualbox. </a>

* <a href = "https://www.vagrantup.com/downloads" > Vagrant. </a>


## 1. Mini-Projeto

<p> O primeiro mini projeto consiste no desenvolvimento de um servidor virtualizado pelo virtualbox+vagrant(172.17.177.40) que tem banco de dados mysql, apache e wordpress.
</p>

<p> Passo a passo para execução:
</p>

~~~
vagrant up
~~~

~~~
ansible-playbook provisioning.yml -u vagrant -i hosts --private-key .vagrant/machines/wordpress/virtualbox/private_key
~~~

