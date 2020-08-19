# Отчёт о тестировании приложения KeyValidator

## Тестирование установки OpenJDK11 в Windows по предъявленной инструкции для дальнейшей работы с приложением KeyValidator
  
### Краткое описание

18.08.2020 - было проведено тестирование документации по установки OpenJDK11 в ОС Windows.

На тестирование затрачено: 1ч

В результате тестирования дефектов не выявлено, OpenJDK11 в ОС Windows устанавливается согласно инструкции.

### Описание процесса тестирования

В процессе тестирования использовались следующие артефакты:
* [инструкция по установки OpenJDK11](https://github.com/netology-code/javaqa-homeworks/blob/master/intro/openjdk11-manual.md)

Тестирование производилось в следующем окружении:
* Microsoft Windows [Version 10.0.18363.1016]
(c) Корпорация Майкрософт (Microsoft Corporation), 2019.

## Тестирование запуска приложения KeyValidator и совместимости с Java 11

### Краткое описание

18.08.2020 - было проведено тестирование запуска приложения KeyValidator.class из командной строки в ОС Windows.

На тестирование затрачено: 1ч

В результате тестирования дефектов не выявлено. Запуск осуществляется, как описано в руководстве использования KeyValidator. Приложение KeyValidator совместимо с Java 11.

### Описание процесса тестирования

В процессе тестирования использовались следующие артефакты:
* [руководство использования KeyValidator](https://github.com/netology-code/javaqa-homeworks/blob/master/intro/user-manual.md)

Тестирование производилось в следующем окружении:
* Microsoft Windows [Version 10.0.18363.1016]
(c) Корпорация Майкрософт (Microsoft Corporation), 2019.
* Java 11
openjdk version "11.0.8" 2020-07-14
OpenJDK Runtime Environment AdoptOpenJDK (build 11.0.8+10)
OpenJDK 64-Bit Server VM AdoptOpenJDK (build 11.0.8+10, mixed mode)


## Тестирование работы приложения KeyValidator согласно руководству использования

### Краткое описание

19.08.2020 - было проведено тестирование методом черного ящика работы приложения KeyValidator.class согласно представленному руководству использования.

На тестирование затрачено: 1ч

В результате тестирования выявлены следующие дефекты:
* (https://github.com/OlgaLetkova/hwJava-1.1/issues/1)
* (https://github.com/OlgaLetkova/hwJava-1.1/issues/2)
* (https://github.com/OlgaLetkova/hwJava-1.1/issues/3)
* (https://github.com/OlgaLetkova/hwJava-1.1/issues/4)

### Описание процесса тестирования

В процессе тестирования использовались следующие артефакты:
* [руководство использования KeyValidator](https://github.com/netology-code/javaqa-homeworks/blob/master/intro/user-manual.md)

В качестве тестовых данных использовались ключи для проверки из [руководство использования KeyValidator](https://github.com/netology-code/javaqa-homeworks/blob/master/intro/user-manual.md):

Валидные ключи:
* 8f05e6a7-70e9-33d7-bfe7-b19eae0d8998
* 80b427f8-92cd-3aae-ba04-3927fbe17c6
* b295bc63-9f03-3b4b-af80-969b39f8c262
* 387eedc6-12e9-3b32-9881-63b6b5e85317
* c19a8cf9-5c3a-37c5-b7f3-d16d38a0c180

Невалидные ключи:
* 18252235-78e0-44a5-8720-556f0c7da17a
* e66075b6-ddad-445e-baf6-161b3289522b
* b6d53250-f07e-4352-a293-6102ddf7f1ca
* c2bc778a-1cb9-46c6-b435-0489649d2a42
* 2fb98b44-93e7-3bdd-a2ad-79347bfe4ad1

Для валидных ключей Result: OK
Для невалидных ключей Result: FAIL

Тестирование производилось в следующем окружении:

* Microsoft Windows [Version 10.0.18363.1016]
(c) Корпорация Майкрософт (Microsoft Corporation), 2019.
* Java 11
openjdk version "11.0.8" 2020-07-14
OpenJDK Runtime Environment AdoptOpenJDK (build 11.0.8+10)
OpenJDK 64-Bit Server VM AdoptOpenJDK (build 11.0.8+10, mixed mode)
