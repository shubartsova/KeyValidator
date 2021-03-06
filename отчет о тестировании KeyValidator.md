
# Отчёт о тестировании приложения KeyValidator

## Краткое описание

29.11.2020  было проведено функциональное тестирование приложения KeyValidator

В результате тестирования выявлены следующие дефекты документации: перепутаны валидные и невалидные ключи в руководстве использования https://github.com/shubartsova/KeyValidator/issues/1

## Описание процесса тестирования

В процессе тестирования использовались следующие артефакты:

* GIT CMD
* создать Git репозиторий.
* добавить файл KeyValidator.class
* запустить приложение при помощи команды java KeyValidator <ключи через пробел>
* получить ответ о статусе ключей. 

В качестве тестовых данных использовались данные из руководства использования  [KeyValidator](https://github.com/netology-code/javaqa-homeworks/blob/master/intro/user-manual.md#%D1%80%D1%83%D0%BA%D0%BE%D0%B2%D0%BE%D0%B4%D1%81%D1%82%D0%B2%D0%BE-%D0%B8%D1%81%D0%BF%D0%BE%D0%BB%D1%8C%D0%B7%D0%BE%D0%B2%D0%B0%D0%BD%D0%B8%D1%8F-keyvalidator)

### Ожидаемый результат: приложение запускается и определяет статус ключа. Фактический результат совпадает с ожидаемым.
# Документация
* Инструкция по установке OpenJDK11 работает под ОС Windows 7
* Приложение запускается и совместимо с Java 11

Тестирование производилось в следующем окружении:
* Windows 7
* Java 11

