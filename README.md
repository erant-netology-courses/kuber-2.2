# kuber-2.2

## Задание 1

<img width="860" height="560" alt="image" src="https://github.com/erant-netology-courses/kuber-2.2/blob/main/1.jpg?raw=true" />


## Задание 2

Не очень понял:

> использующего созданный ранее PVC

Мы же не создавали PVC, это опечатка?

### 2.1, 2.2, 2.3

<img width="960" height="560" alt="image" src="https://github.com/erant-netology-courses/kuber-2.1/blob/main/2.1_2.2_2.3.jpg?raw=true" />

### 2.4
PVC был удален, а т.к. была политика `Retain` то сам PV остался и перешел в статус `Released`

По умолчанию в MicroK8s стоит теперь traefik, поэтому нотация не работает. Менять путь не захотел. Поэтому получаем 404 уже от мультитула внутри (поэтому ответ nginx).

<img width="960" height="560" alt="image" src="https://github.com/erant-netology-courses/kuber-2.1/blob/main/2.4.jpg?raw=true" />

### 2.5
Физически файл остался, удалился только объет PV из K8S. Причина: local + Retain policy.

<img width="960" height="1060" alt="image" src="https://github.com/erant-netology-courses/kuber-2.1/blob/main/2.5.jpg?raw=true" />

### Задание 3

Сделал с microk8s-hostpath

<img width="960" height="1260" alt="image" src="https://github.com/erant-netology-courses/kuber-2.1/blob/main/3.jpg?raw=true" />