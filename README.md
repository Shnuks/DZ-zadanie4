# Домашнее задание к занятию 4
<h1>Задача 1</h1>
<h3>Решение</h3>
Результат установки docker и docker compose plugin
<img width="1068" height="385" alt="Аннотация 2026-05-07 145028" src="https://github.com/user-attachments/assets/90548a2a-dbee-4aa9-807f-8a9c5d563af4" />

Проверка после запуска контейнера 

<img width="527" height="138" alt="image" src="https://github.com/user-attachments/assets/67a8912c-75f3-4cbd-8475-59e09d87c6f8" />

<h4> Ссылка на dockerhub </h4>
<pre> https://hub.docker.com/r/shnuk/custom-nginx </pre>

<h1>Задача 2</h1>
<h4> Ответ </h4>
<img width="1844" height="278" alt="image" src="https://github.com/user-attachments/assets/ed7ea24d-3da7-45e2-ab33-da24fac36c7a" />

<h1>Задача 3</h1>

<img width="1077" height="177" alt="image" src="https://github.com/user-attachments/assets/47a0a245-ee08-42a4-a013-60a38c21b833" />

<h4>В режиме docker attach основной процесс Nginx, поэтому при нажатии Ctrl-C он получает сигнал прервать процесс и т.к. контейнер не имеет больше процессов, то он завершает работу</h4>
<img width="739" height="651" alt="image" src="https://github.com/user-attachments/assets/f9377eaa-1afb-48a8-bf3d-55008a5f4471" />
__________________________________________________________________________________________________________

<img width="791" height="393" alt="image" src="https://github.com/user-attachments/assets/29eb3fda-cd9d-4964-8ccc-105b38b937c3" />

<h4>Ошибка возникает из-за того что Nginx внутри контейнера стал слушать 81 порт, а не 80</h4>


<h1>Задача 4</h1>

<img width="923" height="262" alt="image" src="https://github.com/user-attachments/assets/63b03b37-ec25-4854-8213-4f54050c7b2d" />
.
.
.
<img width="726" height="213" alt="image" src="https://github.com/user-attachments/assets/7a13895d-cbf8-4c29-aeaa-d2875986d4c4" />


