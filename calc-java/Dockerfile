# Используем базовый образ Java
FROM openjdk:alpine
# Устанавливаем рабочую директорию
WORKDIR /dir/calc
# Копируем содержимое текущей директории в контейнер
COPY . /dir/calc
# Компилируем Java приложение
RUN javac calc.java
# Запускаем приложение при старте контейнера
CMD [ "java" , "calc" ]