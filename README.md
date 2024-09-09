# Лабораторная работа №1. Реализация удаленного импорта собственного пакета
### 1. Создадим файл myremo  temodule.py, который будет импортироваться, разместим его в каталоге, который далее будет "корнем сервера", и назовем его rootserver. Напишем код.
![image](https://github.com/user-attachments/assets/f0a2936d-491f-4570-a1c3-6fbc9cdba1f5)

### 2. Создадим файл Python с содержимым функций url_hook и классов URLLoader, URLFinder из текста конспекта лекции со всеми необходимыми библиотеками и назовем: activation_script.py.
![image](https://github.com/user-attachments/assets/1bd91329-d196-4d73-af76-8a5ed295aee7)

### 3. Далее, чтобы продемонстрировать работу импорта из удаленного каталога, запустим сервер http так, чтобы наш желаемый для импорта модуль "лежал" на сервере (например, в корневой директории сервера). Откроем каталог rootserver с файлом myremotemodule.py и запустим там сервер:
![image](https://github.com/user-attachments/assets/6aa387c7-b287-42d0-8028-3d4b1c3461b7)
![image](https://github.com/user-attachments/assets/2ed6554e-b7f1-4a06-b209-22af61bf0d63)

### 4. После этого мы запустили файл, в котором содержится код. python3 -i activation_script.py. Выполнили код: sys.path.append("http://localhost:8000")

![image](https://github.com/user-attachments/assets/507dcf7e-16ac-4d5a-9a80-08dab18cd6a4)


### Ссылка на код: 
[Код](https://github.com/Daniyarsick/Prog5_LB1)
