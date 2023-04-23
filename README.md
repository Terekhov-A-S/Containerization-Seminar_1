# Контейнеризация (семинары)


![picture for containerization](https://github.com/Terekhov-A-S/Containerization-Seminar_1/blob/main/containerization.jpg?raw=true)

## Урок 1. Механизмы пространства имен

### **Информация о проекте**

Необходимо написать проект, содержащий функционал работы с заметками. Программа должна уметь создавать заметку, сохранять её, читать список заметок, редактировать заметку, удалять заметку.

### **Как сдавать проект** 

Для сдачи проекта необходимо создать отдельный общедоступный репозиторий (Github, gitlub, или Bitbucket). Разработку вести в этом репозитории. Программа должна запускаться и работать, ошибок при выполнении программы быть не должно.


**Задание**

* Запустим Bash в новом пространстве имен командой (так как еоманда требует привилегии суперпользователя, то выполняем через sudo):
```
sudo unshare -pf -n --mount-proc bash
```
![sudo unshare -pf -n --mount-proc bash](https://github.com/Terekhov-A-S/Containerization-Seminar_1/blob/main/containerization.jpg?raw=true)


*Подготовил студент Geek Brains* [**`Терехов Александр`**](https://gb.ru/users/7696463), containerization-Seminar_1
