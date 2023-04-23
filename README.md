# Контейнеризация (семинары)


![picture for containerization](https://github.com/Terekhov-A-S/Containerization-Seminar_1/blob/main/containerization.jpg)

## Урок 1. Механизмы пространства имен

### **Информация о проекте**

Необходимо написать проект, содержащий функционал работы с заметками. Программа должна уметь создавать заметку, сохранять её, читать список заметок, редактировать заметку, удалять заметку.

### **Как сдавать проект** 

Для сдачи проекта необходимо создать отдельный общедоступный репозиторий (Github, gitlub, или Bitbucket). Разработку вести в этом репозитории. Программа должна запускаться и работать, ошибок при выполнении программы быть не должно.


**Задание**

* Запустим Bash в новом пространстве имен командой (так как команда требует привилегии суперпользователя, то выполняем через sudo):
```
sudo unshare -pf -n --mount-proc bash
```
![sudo unshare -pf -n --mount-proc bash](https://raw.githubusercontent.com/Terekhov-A-S/Containerization-Seminar_1/main/source/19-21-02.png)


* В параллельном терминале смотрим, что произошло (наглядно):
```
ps -afx
```
![ps -afx](https://raw.githubusercontent.com/Terekhov-A-S/Containerization-Seminar_1/main/source/19-23-13.png)
![ps -afx](https://raw.githubusercontent.com/Terekhov-A-S/Containerization-Seminar_1/main/source/19-22-19.png)



* 


*Подготовил студент Geek Brains* [**`Терехов Александр`**](https://gb.ru/users/7696463), containerization-Seminar_1
