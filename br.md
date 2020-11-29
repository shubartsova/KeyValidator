# Перепутвны валидные/невалидные ключи в руководстве использования KeyValidator

## 1. Шаги для воспроизведения
     1.1 Добавить файл KeyValidator.class в репозиторий.
     1.2 Запустить программу командой java KeyValidator <указать ключи через пробел>
## 2. Ожидаемый результат: вводим ключи из руководства, получаем статус OK/FAIL согласно руководству использования.
### Команда для ввода валидных ключей, ожидаемый статус ОК:
    java KeyValidator 8f05e6a7-70e9-33d7-bfe7-b19eae0d8998 80b427f8-92cd-3aae-ba04-3927fbe17c6 b295bc63-9f03-3b4b-af80-969b39f8c262 387eedc6-12e9-3b32-9881-63b6b5e85317 c19a8cf9-5c3a-37c5-b7f3-d16d38a0c180
## Фактический результат валидные ключи:
* 8f05e6a7-70e9-33d7-bfe7-b19eae0d8998: OK
* 80b427f8-92cd-3aae-ba04-03927fbe17c6: FAIL
* b295bc63-9f03-3b4b-af80-969b39f8c262: OK
* 387eedc6-12e9-3b32-9881-63b6b5e85317: FAIL
* c19a8cf9-5c3a-37c5-b7f3-d16d38a0c180: OK

### Команда для ввода невалидных ключей, ожидаемый статус FAIL:
java KeyValidator 5-78e0-44a5-8720-556f0c7da17a e66075b6-ddad-445e-baf6-161b3289522b b6d53250-f07e-4352-a293-6102ddf7f1ca c2bc778a-1cb9-46c6-b435-0489649d2a42 2fb98b44-93e7-3bdd-a2ad-79347bfe4ad1

## Фактический результат невалидные ключи:
* 18252235-78e0-44a5-8720-556f0c7da17a: FAIL
* e66075b6-ddad-445e-baf6-161b3289522b: FAIL
* b6d53250-f07e-4352-a293-6102ddf7f1ca: FAIL
* c2bc778a-1cb9-46c6-b435-0489649d2a42: FAIL
* 2fb98b44-93e7-3bdd-a2ad-79347bfe4ad1: OK
## 3. Окружение:
        * Windows 7; 64
        * Java 11
## 4. Скриншот
![](https://github.com/shubartsova/KeyValidator/blob/master/%D0%9A%D0%BB%D1%8E%D1%87%D0%B8%20%D0%B2%D0%B0%D0%BB%D0%B8%D0%B4%D0%BD%D1%8B%D0%B5%20%D0%B8%20%D0%BD%D0%B5%D0%B2%D0%B0%D0%BB%D0%B8%D0%B4%D0%BD%D1%8B%D0%B5.png?raw=true.png)
