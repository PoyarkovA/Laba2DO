# Отчёт по лабораторной работе №2

## Тема

Автоматизация сборки и деплоя Python Docker-приложений через Jenkins с интеграцией GitHub.

## Цель работы

Освоить практические навыки автоматизации процесса непрерывной интеграции и развертывания (CI/CD) с использованием Jenkins — мощного инструмента автоматизации сборки, а также наладить взаимодействие с удалённым репозиторием GitHub посредством webhook, обеспечивающим мгновенный запуск сборки при каждом изменении кода.

В рамках работы создадим собственный Jenkins job, используя готовый Pipeline скрипт (Jenkinsfile), освоим управление параметрами сборки, настройку вебхуков для инициирования автоматических сборок, запустим тесты в изолированном Docker-контейнере и развернем приложение с учётом индивидуальных параметров (порт, имя студента).

## Ход выполнения работы

### 1. Настройка Jenkins pipeline

<img width="1379" height="895" alt="image" src="https://github.com/user-attachments/assets/4dedc89c-c153-448f-af33-16c802a8f6df" />

### 2. Создание Webhook

<img width="1897" height="1057" alt="image" src="https://github.com/user-attachments/assets/087e4c02-18dc-41f9-877a-9b653a93cc7c" />


### 3. Сборка

<img width="1888" height="1050" alt="image" src="https://github.com/user-attachments/assets/9f78f7fd-be67-4c83-90c5-4db1f343a6f2" />


### 4. Страница

<img width="1915" height="1058" alt="image" src="https://github.com/user-attachments/assets/130838f5-f7ce-46cc-8628-dd33b5f45e62" />
