# vote-analyzer
Программа для анализа данных о голосовании из XML файлов

## Описание
vote-analyzer — это Java приложение для анализа и обработки больших XML-файлов, содержащих данные о голосующих. Программа читает XML файлы, анализирует данные о голосовании, и сохраняет их в базу данных для последующего анализа дубликатов голосов и статистики голосования. Разработано с использованием JDBC для работы с базой данных MySQL.

## Начало работы

### Предварительные требования
- Установленная Java JDK 8 или выше.
- Установленный и настроенный MySQL сервер.
- Настроенная база данных с таблицей для сохранения данных о голосующих.

### Установка и запуск
1. Клонируйте репозиторий на локальную машину:
   ```bash
   git clone https://github.com/19Dmitry91/vote-analyzer
2. Перейдите в директорию проекта:
   ```bash
   cd vote-analyzer


3. Откройте файл DBConnection.java и настройте параметры подключения к вашей базе данных в переменных URL, USER и PASSWORD.
   Запустите программу:
   ```bash
   java -jar vote-analyzer.jar

4. Конфигурация
   Для изменения пути к анализируемому XML файлу отредактируйте переменную FILE_NAME в классе Loader.

