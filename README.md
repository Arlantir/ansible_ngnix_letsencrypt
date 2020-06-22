# ASNLTA

Автоматическая установка и настройка **nginx**, **let'sencrypt** с помощью 
**ansible**

**Установка**

1. Установить [ansible][1] на сервер

**Настройка на localhost**

1.
```
git clone git@github.com:Arlantir/ansible_ngnix_letsencrypt.git
```
2. 

```
cd ansible_ngnix_letsencrypt
```
3. 

```
ansible-playbook  playbook_nginx.yml -e "domain_name=example.com host_name=example"
```

**domain_name** - доменное имя

**host_name** - чаще всего совпадает с доменным именем, но указывается без доменной зоны

[1]: https://docs.ansible.com/ansible/latest/installation_guide/intro_installation.html