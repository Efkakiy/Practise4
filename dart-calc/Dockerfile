# Используем образ Dart
FROM google/dart AS build
# Устанавливаем рабочую директорию
WORKDIR /app
# Копируем содержимое текущей директории в контейнер
COPY . /app
# Устанавливаем команду для запуска Dart приложения
CMD ["dart", "calc.dart"]
