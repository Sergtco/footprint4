# Практика 4
## Практика 1: Копирование данных с одного диска на другой
Для копирования данных с одного диска на другой используем команду: 
```bash
dd if=/dev/sda of=/dev/sdb bs=4M status=progress
```
![image](https://github.com/user-attachments/assets/8bbab27d-b841-4441-b18e-aade39717d17)

## Практика 2: Создание образа диска
```bash
sduo dd if=/dev/sda of=sda_image.img bs=4M status=progress
```
![image](https://github.com/user-attachments/assets/4260d568-1362-4285-8216-159d88857036)

## Практическая работа 3: Клонирование USB-флешки
![image](https://github.com/user-attachments/assets/53c9c17e-ff1c-4ee5-baf9-ac60c8899426)

## Практическая работа 4: Запись образа на диск или флешку
