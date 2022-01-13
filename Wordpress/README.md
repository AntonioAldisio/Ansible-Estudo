# Montagem de Wordpress em uma maquina virtual 

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

