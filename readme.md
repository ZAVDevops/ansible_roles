## Настроить /etc/ansible/hosts: 
указать ip адреса серверов, на которых будет установлен docker, собраны docker образы и запущены контейнеры с приложением boxfuse hello

## Запустить playbook:
```
ansible-playbook server_roles.yml
```

## Зайти на сайт:
http://<YOR_EXTERNAL_IP>:8080/hello-1.0/
