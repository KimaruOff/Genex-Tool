### Genex Tool
![photo_2025-03-26_13-02-38.jpg](https://github.com/KimaruOff/-Genex_Tool/blob/main/photo_2025-03-26_13-02-38.jpg)
как использовать

## Для termux или Linux

**Установите Python и pip**  
   Убедитесь, что у вас установлен Python и pip. Если они не установлены, выполните следующую команду:
   - Для Linux:
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
   unzip "Genex - OSINT.zip"
   cd "Genex - OSINT"
   pip install -r requirements.txt
   python Genex-Tool.py
```
