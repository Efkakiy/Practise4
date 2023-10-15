# Используем базовый образ Python
FROM python:alpine
# Устанавливаем рабочую директорию внутри контейнера
WORKDIR /dir/rpsgame
# Копируем содержимоей текущей директории внутрь контейнера
COPY . /dir/rpsgame
# Задаем команду для выполнения при запуске контейнера
CMD [ "python" , "RockPaperScissorsGame.py" ]