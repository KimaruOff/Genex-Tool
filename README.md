### Genex Tool
![photo_2025-03-26_21-56-55.jpg](https://github.com/KimaruOff/-Genex_Tool/blob/main/photo_2025-03-26_21-56-56.jpg)
#### как использовать

## Для termux или Linux

### Установите Git, если он не установлен

Если у вас еще не установлен Git, выполните следующую команду для его установки:

- Для **Linux** (Debian/Ubuntu):
  ```bash
  sudo apt-get update
  sudo apt-get install git

 - Для **Termux**
   ```bash
   pkg update
   pkg install git
   ``` 
**Установите Python и pip**  
   Убедитесь, что у вас установлен Python и pip. Если они не установлены, выполните следующую команду:
   - Для Linux (Debian/Ubuntu):
     ```bash
     sudo apt-get update
     sudo apt-get install python3 python3-pip
     ```
   - Для Termux:
     ```bash
     pkg update
     pkg install python
     ```
**Скачайте сам скрипт**
   ```bash
   git clone https://github.com/KimaruOff/Genex_Tool.git
   cd Genex_Tool
   ```
**Разархивируйте архив и запускайте скрипт**
   ```bash
   unzip "Genex 1.5 - OSINT.zip"
   cd "Genex 1.5 - OSINT"
   pip install -r requirements.txt
   python Genex-Tool.py
```
