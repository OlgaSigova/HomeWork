# Инструкция по пользованию GitHub
![GitHub](https://github.githubassets.com/images/modules/dashboard/onboarding/gh-desktop.png)

## Работа со своими репозиториями с GitHub

1. Создать аккаунт на Github.com: зайти на официальный сайт [GitHub](https://github.com/) и создать новую учетную запись.
2. Создать **свой локальный** репозиторий.
3. "Подружить" локальный и удаленный репозиторий. 
Github при создании нового репозитория покажет как это можно сделать
4. **Оправить (push)** локальный репозиторий в удаленный (на Github), при этом, возможно, нужно будет авторизироваться на удаленном репозитории.
5. Провести изменения "с другого компьютера"/с github.
6. **Выкачать (pull)** актуальное состояние из удаленного репозитория.

## Совместная работа в проекте. Создание запросов слияния.

1. Делаем **форк (fork)** интересующего нас репозитория.
2. Делаем **git clone для нашей** версии этого репозитория.
3. Создаем ветку с предлагаемыми изменениями.
4. Производим все изменения **только в этой ветке**.
5. Фиксируем изменения **(делаем коммиты)**.
6. Отправляем эти изменения на **свой аккаунт (push)**.
7. В окне на Github появляется возможность отправить **pull request**.

## Pull Request со стороны владельца программы.

Тут должны быть внесены изменения для провокации конфликта.
При подключении к работе сторонних специалистов может понадобиться функция запроса слияния (Pull Request). 

1. Открыть вкладку **Pull Request**.
2. Нажать на кнопку **Create Pull Request**.
3. Выбрать ветку, которую следует слить с основной.
4. Просмотреть внесенные кодером изменения.
5. После изучения информации созданный запрос на слияние подтверждается нажатием **Merge Pull Request**. 
6. Напишем ерунду для конфликта.

Новый код будет импортирован в основную ветку, а созданная сторонним исполнителем может спокойно удаляться.

## Отчеты об ошибках.

На вкладке *Issue* любой «тестировщик» может оставить сообщение о проблемах, с которыми ему пришлось столкнуться при использовании ПО.
1. Нажать кнопку **New issue**.
2. Внести заголовок и текст сообщения.

В результате, владелец ветки получает уведомления в личном кабинете или на электронную почту, указанную при регистрации.
