Репозиторий содержит механизмы для автоматизации развёртывания инфраструктуры CI (непрерывной интеграции) для платформы 1С на основе Packer, Vagrant, Ubuntu и Jenkins.

Имеет особенности:
* Возможность выбора дистрибутивов платформы 1С, сервера PostgreSQL и версии Ubuntu для сборки образа.
* Возможность настройки сети из виртуальных машин.
* Ориентированность на одновременное тестирование нескольких закладок в хранилище 1С.

Подробное описание механизмов представлено в виде цикла публикаций "Многопоточный CI-контур для 1С" на портале Инфостарт:

1)  Описание системы и обзор инструментария: https://infostart.ru/public/1198035
2)  Сборка образа виртуальной машины с PostgreSQL и платформой 1С: https://infostart.ru/public/1201632
3)  Развёртывание узлов CI через Vagrant, объединение виртуальных машин в сеть: https://infostart.ru/public/1205450
4)  Конфигурирование Jenkins и подключение к нему виртуальных машин: https://infostart.ru/public/1209079


Связанный репозиторий, обеспечивающий наполнение CI исполняемым кодом и механизмами тестирования на основе Jenkins:

* на GitLab: https://gitlab.com/vladimirlitvinenko84/ci-for-1c-based-on-jenkins
* на GitHub: https://github.com/VladimirLitvinenko84/ci-for-1c-based-on-jenkins
