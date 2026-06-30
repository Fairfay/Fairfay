# Тычин Денис — Python Разработчик

> Здесь собраны проекты за время обучения и работы.

---

## 📌 О себе

Привет! Я Python Разработчик: да-да, Бэкенд Разработчик с большой буквы.
Я прошел большой путь, побывал в роли Fullstack и решил развиваться в направлении Backend.

<details>
<summary><h2>Опыт работы 4+ года:</h2></summary>
  <h4>
    <a href="https://noones.com" target="_blank" rel="noopener noreferrer">
      <span">NoOnes (Fintech - Wallet team)</span>
    </a>
  </h4>
  <div>
    <span>Python Software Engineer</span>
    <span>Июнь 2025 — По настоящее время</span>
  </div>
  <div>
    <h4>Обязанности:</h4>
      <br>Разрабатывал и поддерживал отказоустойчивые интеграции с различными платежными провайдерами.
      <br>Оптимизировал ключевой платежный модуль, успешно обрабатывающий более $100 000 в день.
      <br>Реализовал безопасное взаимодействие с API (REST, вебхуки), проверку цифровых подписей и шифрование данных в соответствии со стандартами финтеха.
      <br>Работаю в составе команды над обеспечением атомарности транзакций, синхронизации балансов и механизмов отката (rollback) в случае ошибок.
  </div>

  
  <h4>
    <a href="https://incasecorp.ru" target="_blank" rel="noopener noreferrer">
      <span">ООО "ИНКЕЙС КОРП"</span>
    </a>
  </h4>
  <div>
    <span>Python Разработчик</span>
    <span>Июнь 2025 — Июнь 2026</span>
  </div>
  <div>
    <h4>Обязанности:</h4>
      <br><strong>Разработка системы мультиканального трекинга задач и напоминаний с AI-аналитикой и интеграцией с мессенджерами (MVP - Telegram MiniApp).</strong>
      <br>Цель - создать гибкий инструмент для компаний, который объединяет трекинг задач, аналитику загрузки сотрудников и интеграцию с AI для автоматизации планирования и анализа трудозатрат.
          <br><br><strong>1. Архитектура и проектирование</strong>
          <br>- Разработал архитектуру системы с нуля, включающую микросервисную структуру с независимыми каналами (Telegram, VK и др.), что обеспечивает отказоустойчивость - сбой одного канала не влияет на работу всей системы.
          <br>- Спроектировал ядро на Django + PostgreSQL + Redis + Celery + RabbitMQ, обеспечив надёжное хранение, кэширование и асинхронную обработку уведомлений.
          <br>- Реализовал гибкое API-ядро, независимое от конкретного мессенджера, что позволило закладывать масштабирование под другие каналы без переработки backend-логики.
          <br><br><strong>2. Разработка функционала</strong>
          <br>- Создал MiniApp-интерфейс в Telegram для работы с задачами, уведомлениями и статистикой в реальном времени.
          <br>- Внедрил систему ролей и авторизации (исполнитель, наблюдатель, админ, РП) с единым профилем и связкой Yandex ID + Telegram ID, что упростило онбординг пользователей.
          <br>- Разработал функционал AI-интеграции, включающий:
              <br>1. Генерацию задач из транскрибаций встреч;
              <br>2. Формирование аналитических отчётов и кратких сводок;
              <br>3. Прогнозирование перегрузки сотрудников;
              <br>4. Расчёт окупаемости проектов.
          <br>- Интегрировал Яндекс Трекер для двусторонней синхронизации задач.
          <br><br><strong>3. Уведомления и автоматизация</strong>
          <br>- Реализовал интеллектуальный чат-бот, который автоматически уведомляет пользователей о дедлайнах, изменениях в задачах и необходимости списания часов.
          <br>- Добавил систему умных напоминаний по локальному времени, что снизило количество просроченных задач более чем на 25%.
          <br>- Настроил автоматическую отправку стека ошибок в Telegram-канал разработчика, что сократило время реакции на критические инциденты с часов до минут.
          <br><br><strong>4. Производительность и надёжность</strong>
          <br>- Настроил профилирование N+1 запросов и оптимизацию ORM-взаимодействия, что снизило среднее время отклика API на 40%.
          <br>- Добавил healthcheck-эндпоинты и централизованный мониторинг через Sentry, обеспечив SLA-уровень 99.9%.
          <br><br><strong>5. DevOps и инфраструктура</strong>
          <br>- Настроил контейнеризацию через Docker, оркестрацию и CI/CD-конвейер для автоматических выкатов и изолированных окружений.
          <br>- Использовал Nginx в роли API-gateway, обеспечив безопасность и балансировку трафика.
          <br><br><strong>6. Аналитика и визуализация</strong>
          <br>- Реализовал метрики загрузки и трудозатрат по сотрудникам и проектам с AI-оценкой эффективности.
          <br>- Добавил визуальную панель статистики - процент задач "в работе", просроченных, среднее время выполнения, прогноз окупаемости.
          <br><strong>7. Эффект</strong>
           <br>- Сформировал основу корпоративного SaaS-решения, готового к масштабированию и коммерциализации.
           <br>- Система успешно прошла пилотное внедрение в компании, сократив время реакции на задачи и коммуникацию между сотрудниками.
          <br>------------------------------------
          <br>------------------------------------
          <br><strong>Разработка cистемы автоматизации электронного документооборота для крупного заказчика - Маревен Фуд Сэнтрал.</strong>
          <br>Цель: перевести документооборот компании с бумажного формата в полностью электронный, обеспечить интеграцию с корпоративными и внешними системами, снизить затраты на обработку документов и ускорить бизнес-процессы.
          <br><br><strong>1. Быстрая адаптация и включение в проект</strong>
          <br>- Быстро влился в крупный корпоративный проект, оперативно погрузился в архитектуру и процессы, взял на себя ключевые задачи по backend-разработке, стал флагманским разработчиком проекта.
          <br>- С первых недель участвовал в решении критичных задач и взаимодействии с представителями заказчика, показав высокую скорость адаптации и техническую инициативу.
          <br><br><strong>2. Разработка и интеграции</strong>
          <br>- Разработал backend-логику системы документооборота на C# и SQL Server, реализовав стабильное API для внутренних и внешних сервисов.
          <br>- Настроил интеграции с SAP API, Diadoc API и Контур API, обеспечив автоматическую синхронизацию документов и статусов между системами.
          <br>- Создал механизмы валидации и маршрутизации документов, что позволило сократить количество ручных ошибок при обработке данных.
          <br><br><strong>3. Архитектура и взаимодействие</strong>
          <br>- Разработал систему контроля версий и журналирования изменений, обеспечив полную трассировку действий пользователей и прозрачность документооборота.
          <br>- Оптимизировал SQL-запросы и процедуры, что снизило время отклика системы при большом объёме данных.
          <br><br><strong>4. Продакшн и внедрение</strong>
          <br>- Руководил первым продакшн-деплоем системы, обеспечив бесшовный переход пользователей с бумажных документов на электронные без остановки бизнес-процессов.
          <br>- Подготовил и провёл тестирование функционала, включая интеграции и сценарии пользовательских ролей.
          <br><br><strong>5. Эффект</strong>
          <br>- Обеспечил переход документооборота компании в электронный формат, что значительно ускорило согласование документов и снизило административные затраты.
          <br>- Система позволила автоматизировать более 80% операций по обработке документов, повысив скорость документооборота и точность данных.
  </div>
  <h4>
    <a href="https://mirit42.ru " target="_blank" rel="noopener noreferrer">
      <span">ООО "МИРИТ"</span>
    </a>
  </h4>
  <div>
    <span>Fullstack разработчик</span>
    <span>Февраль 2023 — Июнь 2025</span>
  </div>
  <div>
    <h4>Обязанности:</h4>
    <br><strong>Проект - Yourtask:</strong>
    <br>Корпоративная система управления проектами и задачами (аналог YouGile, Trello, Jira).
    <br>Роль: Fullstack-разработчик (основной упор - backend).
    <br>Результат: проект вошёл в реестр отечественного ПО и используется в муниципальных и коммерческих организациях Кузбасса.
    <br><br><strong>1. Проектирование и архитектура</strong>
    <br>- Разработал архитектуру системы с нуля, выбрав микросервисный подход и внедрив WebSocket (Django Channels) для работы в реальном времени.
    <br>- Спроектировал базу данных на PostgreSQL и реализовал схему распределения данных между сервисами, что позволило ускорить доступ к данным на ~35%.
    <br>- Определил технологический стек (Django, React, Docker, Redis, Celery) и стандарты разработки, что обеспечило единообразие кода и упростило масштабирование команды.
    <br><br><strong>2. Разработка функционала</strong>
    <br>- Создал core-функционал управления проектами, задачами и спринтами (Agile-доски, диаграмма Ганта, уведомления, история изменений).
    <br>- Интегрировал Telegram-бот (@SmarTaskBot) и email-уведомления, что сократило время реакции пользователей на события в системе.
    <br>- Реализовал вход через Yandex ID и Telegram Auth (OAuth2), обеспечив рост конверсии регистрации на 20%.
    <br>- Разработал модуль работы с облачным хранилищем AWS S3 (Ростелеком) и GitLab API для версионирования документов.
    <br><br><strong>3. DevOps и CI/CD</strong>
    <br>- Настроил Docker-контейнеризацию и автоматизированный деплой через GitLab CI/CD и Container Registry, сократив время выката новой версии с 30 до 5 минут.
    <br>- Реализовал мониторинг ошибок через Sentry и систему healthcheck, повысив стабильность продакшена.
    <br>- Реализовал уведомления в Telegram при критических ошибках деплоя.
    <br><br><strong>4. Безопасность</strong>
    <br>- Внедрил JWT-аутентификацию, защиту от брутфорса через django-axes и шифрование данных.
    <br>- Обеспечил соответствие требованиям реестра российского ПО (локализация данных, политика безопасности).
    <br><br><strong>5. Интеграции и реальное время</strong>
    <br>- Реализовал поддержку WebSocket и Service Workers, обеспечив обновление данных без перезагрузки страниц.
    <br>- Интегрировал внешние API (Telegram, Yandex, AWS S3) и использовал Nginx как reverse-proxy.
    <br>- Реализовал автоматизированные мгновенные уведомления в Telegram при ошибках полученных пользователями, приходят с полным стек трейсом, отображением места ошибки, id пользователя.
    <br><br><strong>6. Тестирование и документация</strong>
    <br>- Написал unit и интеграционные тесты (pytest, unittest) с покрытием более 80%.
    <br>- Задокументировал API через Swagger/OpenAPI, упростив onboarding новых разработчиков.
    <br><br><strong>7. Управление процессом разработки</strong>
    <br>- Организовал процесс по Agile-принципам, внедрив систему управления задачами, аналогичную YouGile и Jira.
    <br>- Курировал полный цикл - от проектирования до поддержки продакшена.
    <br><br><strong>8. Эффект</strong>
    <br>- Система успешно внедрена в муниципальные предприятия и частные компании Кузбасса, используется в ежедневной работе.
    <br><br><strong>Решение признано отечественным ПО и прошло процедуру сертификации.</strong>
  </div>
  <h4>
    <a href="https://l.tinkoff.ru/career.and.vacancies " target="_blank" rel="noopener noreferrer">
      <span">АО "Т-Банк"</span>
    </a>
  </h4>
  <div>
    <span>Специалист технической поддержки</span>
    <span>Июнь 2022 — Август 2022</span>
  </div>
  <div>
    <h4>Обязанности:</h4>
    <ul>
      <li>Поддержка клиентов.</li>
    </ul>
  </div>
  <div>
    <h4>Команда:</h4>
    <ul>
      <li><strong>Специалист технической поддержки</strong></li>
      <li>Руководитель</li>
    </ul>
  </div>
  <h4>
    <a href="http://www.sibset.ru/ " target="_blank" rel="noopener noreferrer">
      <span">ООО "СибирскиеСети"</span>
    </a>
  </h4>
  <div>
    <span>Специалист по продажам</span>
    <span>Июнь 2021 — Август 2021</span>
  </div>
  <div>
    <h4>Обязанности:</h4>
    <ul>
      <li>Продвижение компании за счет холодных продаж, в виде телефонного разговора с клиентами.</li>
    </ul>
  </div>
  <div>
    <h4>Команда:</h4>
    <ul>
      <li><strong>Специалист по продажам</strong></li>
      <li>Руководитель</li>
    </ul>
  </div>
</details>

## Ниже представлены мои навыки и проекты.

### Веб-фреймворки и серверы
![Django](https://img.shields.io/badge/Django-0C4B33?logo=django&logoColor=white) * ![FastAPI](https://img.shields.io/badge/FastAPI-009588?logo=fastapi&logoColor=white) * 
![Flask](https://img.shields.io/badge/Flask-black?logo=flask&logoColor=white) * ![Scrapy](https://img.shields.io/badge/Scrapy-14b8a6?logo=scrapy&logoColor=white) * 
![Uvicorn](https://img.shields.io/badge/Uvicorn-2094f3?logo=uvicorn&logoColor=white) * ![Gunicorn](https://img.shields.io/badge/Gunicorn-298729?logo=gunicorn&logoColor=white) * 
![Django REST Framework](https://img.shields.io/badge/Django%20REST%20Framework-2C2C2C?logo=data:image/png;base64,iVBORw0KGgoAAAANSUhEUgAAABwAAAAcCAYAAAByDd+UAAAAmElEQVR4AWJwL/AhCS8GtFsHGADDMABFe4SepHLkniR36Um6gJoYEn8Iig+YZ1sbaa2/yz6fQcRSa7vUkigexeYH5JsHhaBYO5gA8LydJkC1OgV3pgh4wZXAFgAPOhLg+OseKjqhDmSowzDo0OH+6bKGxzjIh3c1EHzS+oeGXwsOCrj4VUcbGN4XrLJigCWq/poIFuGSw/sBXaqQ6KtKmjwAAAAASUVORK5CYII=&logoColor=white)

### Тестирование и CI/CD
![Pytest](https://img.shields.io/badge/Pytest-FF4500?logo=pytest&logoColor=white) * ![Unittest](https://img.shields.io/badge/Unittest-3776AB?logo=python&logoColor=white) * 
![Selenium](https://img.shields.io/badge/Selenium-43b02a?logo=selenium&logoColor=white) * ![Swagger](https://img.shields.io/badge/Swagger-white?logo=swagger&logoColor=black) * 
![OpenAPI](https://img.shields.io/badge/OpenAPI-2560D7?logo=swagger&logoColor=white) * ![Pydantic](https://img.shields.io/badge/Pydantic-e92063?logo=pydantic&logoColor=white) * 
![Postman](https://img.shields.io/badge/Postman-E0531F?logo=postman&logoColor=white) * ![GitLab CI/CD](https://img.shields.io/badge/GitLab%20CI/CD-FC6D26?logo=gitlab&logoColor=white) * 
![GitHub Actions](https://img.shields.io/badge/GitHub%20Actions-278cff?logo=githubactions&logoColor=white) * ![ReDoc](https://img.shields.io/badge/ReDoc-white?logo=redoc&logoColor=black)

### Базы данных и кэширование
![PostgreSQL](https://img.shields.io/badge/PostgreSQL-396c94?logo=postgresql&logoColor=white) * ![Redis](https://img.shields.io/badge/Redis-d93327?logo=redis&logoColor=red) * 
![SQLAlchemy](https://img.shields.io/badge/SQLAlchemy-B00?logo=sqlalchemy&logoColor=white) * ![Alembic](https://img.shields.io/badge/Alembic-2E85BA?logo=alembic&logoColor=white) * 
![SQLite](https://img.shields.io/badge/SQLite-044a64?logo=sqlite&logoColor=white) * ![MS SQL](https://img.shields.io/badge/MS%20SQL%20Server-CC2929?logo=microsoftsqlserver&logoColor=white) * 
![MySQL](https://img.shields.io/badge/MySQL-3E6E93?logo=mysql&logoColor=white)

### Асинхронность и задачи
![Celery](https://img.shields.io/badge/Celery-348613?logo=celery&logoColor=white) * ![Flower](https://img.shields.io/badge/Flower-348613?logo=flower&logoColor=white) * 
![AsyncIO](https://img.shields.io/badge/AsyncIO-3776AB?logo=python&logoColor=white) * ![Django Channels (WebSockets)](https://img.shields.io/badge/Django%20Channels%20(WebSockets)-0C4B33?logo=django&logoColor=white) * 
![Aiogoogle](https://img.shields.io/badge/Aiogoogle-2560D7?logo=aiogoogle&logoColor=white)

### Облачные сервисы и хранение
![AWS S3](https://img.shields.io/badge/AWS%20S3-232f3e?logo=aws&logoColor=white) * ![Yandex Cloud](https://img.shields.io/badge/Yandex%20Cloud-4e79eb?logo=yandexcloud&logoColor=white) * 
![Yandex Object Storage](https://img.shields.io/badge/Yandex%20Object%20Storage-4e79eb?logo=yandexcloud&logoColor=white) * ![S3 Ростелеком](https://img.shields.io/badge/S3%20Ростелеком-7700ff?logo=rostelecom&logoColor=white) * 
![Sentry](https://img.shields.io/badge/Sentry-32243e?logo=sentry&logoColor=white) * ![S3 Minio](https://img.shields.io/badge/S3%20Minio-cf163e?logo=minio&logoColor=white) * 
![Safety CLI](https://img.shields.io/badge/Safety%20CLI-3e63dd?logo=safetycli&logoColor=white)  

### Контейнеризация и оркестрация
![Docker](https://img.shields.io/badge/Docker-00084d?logo=docker&logoColor=white) * ![Docker Compose](https://img.shields.io/badge/Docker%20Compose-00084d?logo=docker&logoColor=white) * 
![Docker Compose Override](https://img.shields.io/badge/Docker%20Compose%20Override-00084d?logo=docker&logoColor=white) * ![GitLab Container Registry](https://img.shields.io/badge/GitLab%20Container%20Registry-FC6D26?logo=gitlab&logoColor=white) * 
![DockerHub](https://img.shields.io/badge/DockerHub-00084d?logo=docker&logoColor=white)

### Фронтенд и интеграции
![React](https://img.shields.io/badge/React-404756?logo=react&logoColor=61DAFB) * ![Redux](https://img.shields.io/badge/Redux-764abc?logo=redux&logoColor=white) * 
![Webpack](https://img.shields.io/badge/Webpack-2b3a42?logo=webpack&logoColor=white) * ![PWA](https://img.shields.io/badge/PWA-3885E9?logo=pwa&logoColor=white) * 
![Axios](https://img.shields.io/badge/Axios-6e24e1?logo=axios&logoColor=white) * ![Ajax](https://img.shields.io/badge/Ajax-3885E9?logo=ajax&logoColor=white) * 
![D3.js](https://img.shields.io/badge/D3.js-dd7e53?logo=d3&logoColor=white) * ![CKEditor5](https://img.shields.io/badge/CKEditor5-743ccd?logo=ckeditor&logoColor=white) * 
![Chart.js](https://img.shields.io/badge/Chart.js-FF6384?logo=chartdotjs&logoColor=white) * ![DHTMLX](https://img.shields.io/badge/DHTMLX-2095f3?logo=dhtmlx&logoColor=white)

### Авторизация и безопасность
![JWT](https://img.shields.io/badge/JWT-black?logo=jsonwebtokens&logoColor=white) * ![OAuth](https://img.shields.io/badge/OAuth-black?logo=oauth&logoColor=white) * 
![API Gateway(Nginx)](https://img.shields.io/badge/API%20Gateway(Nginx)-00B140?logo=nginx&logoColor=white) * ![Safety CLI](https://img.shields.io/badge/Safety%20CLI-3e63dd?logo=safetycli&logoColor=white) * 
![OAuth 2.0](https://img.shields.io/badge/OAuth%202.0-black?logo=oauth&logoColor=white) * ![django axes](https://img.shields.io/badge/django%20axes-3885E9?logo=django&logoColor=white)

### Языки и утилиты
![Python](https://img.shields.io/badge/Python-2b5b84?logo=python&logoColor=white) * ![C#](https://img.shields.io/badge/C%23-ac99ea?logo=csharp&logoColor=white) * 
![Go](https://img.shields.io/badge/Go-007d9cbf?logo=go&logoColor=white) * ![TypeScript](https://img.shields.io/badge/TypeScript-3178c6?logo=typescript&logoColor=white) * 
![JavaScript](https://img.shields.io/badge/JavaScript-f7e025?logo=javascript&logoColor=white) * ![ООП](https://img.shields.io/badge/ООП-black?logo=oop&logoColor=white) * 
![Bash](https://img.shields.io/badge/Bash-a32d2a?logo=gnubash&logoColor=white) * ![Tmux](https://img.shields.io/badge/Tmux-1bb91f?logo=tmux&logoColor=white) *
![HTML](https://img.shields.io/badge/HTML-04AA6D?logo=html5&logoColor=white) * ![CSS](https://img.shields.io/badge/CSS-04AA6D?logo=css&logoColor=white) * 
![Jinja2](https://img.shields.io/badge/Jinja2-a00?logo=jinja&logoColor=white) * ![Makefile](https://img.shields.io/badge/Makefile-3178C6?logo=makefile&logoColor=white)

### Сторонние API
![Telegram API](https://img.shields.io/badge/Telegram%20API-54a9eb?logo=telegram&logoColor=white) * ![Yandex API](https://img.shields.io/badge/Yandex%20API-f8604a?logo=yandex&logoColor=white) * 
![Google API](https://img.shields.io/badge/Google%20API-4889f4?logo=googleapis&logoColor=white) * ![Dropbox](https://img.shields.io/badge/Dropbox-0061fe?logo=dropbox&logoColor=white) * 
![Google Sheets API](https://img.shields.io/badge/Google%20Sheets%20API-24a767?logo=googleapis&logoColor=white)

### Системы контроля версий
![GitHub](https://img.shields.io/badge/GitHub-white?logo=github&logoColor=black) * ![GitLab](https://img.shields.io/badge/GitLab-FC6D26?logo=gitlab&logoColor=white) * 
![GitTea](https://img.shields.io/badge/GitTea-609926?logo=gittea&logoColor=white)

### Инструменты и практики
![Poetry](https://img.shields.io/badge/Poetry-1d5193?logo=poetry&logoColor=white) * ![Linux](https://img.shields.io/badge/Linux-f9cb09?logo=linux&logoColor=black) * 
![Nginx](https://img.shields.io/badge/Nginx-00B140?logo=nginx&logoColor=white) * ![REST API](https://img.shields.io/badge/REST%20API-2E85BA?logo=restapi&logoColor=white) * 
![Threading](https://img.shields.io/badge/Threading-2b5b84?logo=python&logoColor=white) * ![Multiprocessing](https://img.shields.io/badge/Multiprocessing-2b5b84?logo=python&logoColor=white) * 
![GIL](https://img.shields.io/badge/GIL-2b5b84?logo=python&logoColor=white) * ![Postman](https://img.shields.io/badge/Postman-E0531F?logo=postman&logoColor=white) * 
![YAML](https://img.shields.io/badge/YAML-009639?logo=yaml&logoColor=white) * ![Requests](https://img.shields.io/badge/Requests-2b5b84?logo=python&logoColor=white)


---

## 🧩 Мои проекты

### 1. [Yourtask](https://yourtask.ru)
**Описание:**
Проект создавался как замена ушедшим из России сервисам по типу - Trello(Atlassian), Youtrack, YouGile, Kaiten.

**Возможности:** 
Гибкая настройка прав доступа, управление организациями, классические Agile доски, списки задач, диаграмма ганта, календарь событий,
комментарии с функцией онлайн чата, история каждого действия, уведомления в телеграмм, на почту и push в браузер, отображение изменения задач в реальном времени,
статистика по сотрудникам, возможность настройки профиля, смена темы, приглашение пользователя по временной ссылке, бесшовный вход с Яндекс ID и Telegram, MiniApp, поддержка мобильной web версии и PWA.

🛠 Технологии: `Django`, `Django REST Framework`, `Oauth`, `Uvicorn`, `Poetry`, `Pytest`, `Unittest`, `Django channel(Websocket)`, `Postgres`, `Redis`, `Celery`, `Flower`, `JWT`, `Nginx`,
`AWS S3 - Ростелеком`, `Telegram API`, `Yandex API`, `Swagger`, `Docker`, `Docker Compose`, `GitLab`, `React`, `webpack`, `Redux`, `D3.js`, `Chart.js`, `Ckeditor5`, `Dhtmlx`, `Axios`, `Makefile`,
`GitLab`, `GitLab Container Registry`, `GitLab CI/CD`.

Главная страница "Мои доски"
![Главная страница "Мои доски"](https://raw.githubusercontent.com/Fairfay/Yourtask_promo/refs/heads/main/yourtask_main_boards.png)

<details>
<summary><h3>Остальные страницы проекта</h3></summary>

Страница "Внутри доски"
![Страница "Внутри доски"](https://raw.githubusercontent.com/Fairfay/Yourtask_promo/refs/heads/main/yourtask_inside_board.png)

Страница "Список задач"
![Страница "Список задач"](https://raw.githubusercontent.com/Fairfay/Yourtask_promo/refs/heads/main/yourtask_tasks_list.png)

Страница "Задача"
![Страница "Задача"](https://raw.githubusercontent.com/Fairfay/Yourtask_promo/refs/heads/main/yourtask_inside_task.png)

Страница "Профиль"
![Страница "Профиль"](https://raw.githubusercontent.com/Fairfay/Yourtask_promo/refs/heads/main/yourtask_user_profile.png)

Страница "Cтатистика по сотрудникам"
![Страница "Cтатистика по сотрудникам"](https://raw.githubusercontent.com/Fairfay/Yourtask_promo/refs/heads/main/yourtask_details_by_employees.png)

Страница настроек активная кнопка "Создать роль"
![Страница настроек активная кнопка "Создать роль"](https://raw.githubusercontent.com/Fairfay/Yourtask_promo/refs/heads/main/yourtask_settings_role.png)

Страница "Мои задачи"
![Страница "Мои задачи"](https://raw.githubusercontent.com/Fairfay/Yourtask_promo/refs/heads/main/yourtask_info_user.png)

Мобильный дизайн
![Страница "Мобильный дизайн - Профиль"](https://raw.githubusercontent.com/Fairfay/Yourtask_promo/refs/heads/main/yourtask_mobile_info_user.png)
![Страница "Мобильный дизайн - Доска, внутри Доски"](https://raw.githubusercontent.com/Fairfay/Yourtask_promo/refs/heads/main/yourtask_mobile.png)
![Страница "Мобильный дизайн - Фильтры внутри доски, Внутри задачи"](https://github.com/Fairfay/Yourtask_promo/blob/main/yourtask_mobile_inside_board_and_task.png)
![Страница "Мобильный дизайн - Фильтры Список задач, Внутри задачи"](https://raw.githubusercontent.com/Fairfay/Yourtask_promo/refs/heads/main/yourtask_mobile_inside_task_and_filter.png)

Некоторые модальные окна

![Страница "Заметки"](https://raw.githubusercontent.com/Fairfay/Yourtask_promo/refs/heads/main/yourtask_modal_window_notes.png)
![Страница "Различне настройки"](https://raw.githubusercontent.com/Fairfay/Yourtask_promo/refs/heads/main/yourtask_modal_windows.png)
</details>

**Детали:**  
- **Как я это сделал?**
Проект был разработан с нуля, начиная от построения архитектуры и проектирования БД до микросервисной архитектуры и поддержки websocket.
Все начиналось с дипломного проекта, который превратился в огромную систему управления проектами.

- **Какой эффект достигнут?**
Системой пользуются муниципальные предприятия Кузбасса, рестораны Ивана Печерского, планируется выход в правительство Кузбасса. 
Проект входит в реестр Отечественного ПО.

- **Компания:** ООО "МИРИТ"
- **Команда:**
Teamlid - Алексей, 
Fullstack Developer - Тычин Денис Александрович, 
UI/UX Designer - Ксения

---

### 2. Blog-api-with-caching
**Описание:**
Проектирование и реализация API для блога с кешированием постов

**Возможности:** 
REST API сервис для управления блогами с кешированием постов через redis.

🛠 Технологии: `Django`, `Django REST Framework`, `Gunicorn`, `Poetry`, `Redis`, `Postgres`, `Swagger`, `Nginx`, `Docker`, `Docker Compose`, `Makefile`, `GitHub`,
`nplusone`, `drf-standardized-errors`, `django-health-check`, `pytest`.

🔗 [Исходники backend](https://github.com/Fairfay/Blog-api-with-caching)

**Детали:**
- **Какой эффект достигнут?**
Отличные отзывы и получение оффера в tech компанию
- **Команда:**
Python Backend Developer - Тычин Денис Александрович

---

### 3. rest_api_task_management_service
**Описание:**
Небольшой REST-сервис для управления запросами на выплаты. Каждый запрос создается через API и обрабатывается асинхронно с помощью Celery.

**Возможности:** 
REST API сервис для управления заявками на выплату средств с асинхронной обработкой через Celery и Redis.
Более подробно в репозитории.

🛠 Технологии: `Django`, `Django REST Framework`, `Gunicorn`, `Poetry`, `Redis`, `Celery`, `Flower`, `Postgres`, `Swagger`, `Telegram API`, `Nginx`, `Docker`, `Docker Compose`, `Makefile`, `GitHub`,
`nplusone`, `drf-standardized-errors`, `django-health-check`, `pytest`.

🔗 [Исходники backend](https://github.com/Fairfay/rest_api_task_management_service)

**Детали:**
- **Какой эффект достигнут?**
Украли приложение как скелет для построения системы.
- **Команда:**
Python Backend Developer - Тычин Денис Александрович

---

### 4. ReportTask
**Описание:**
Мобильное и веб-приложение для создания и учета доставок. 

**Возможности:** 
Вход по логину и паролю(jwt), справочник, выбор из справочника, ввод времени отправки и доставки, указание дистанции в км, загрузка медиафайлов, выбор услуги, упаковки, статуса, технического состояния, возможность редактировать, удалить, провести доставку.
Просмотр статистики доставок с фильтрами на адаптивном графике, таблице доставок.
Более подробно в репозиториях.

🛠 Технологии: `Django`, `Django REST Framework`, `JWT`, `Gunicorn`, `Poetry`, `Pytest`, `Unittest`, `Postgres`, `React`, `Webpack`,
`Redux`, `D3.js`, `Swagger`, `Telegram API`, `Nginx`, `Docker`, `Docker Compose`, `Makefile`, `Axios`, `PWA`, `GitHub`, `DockerHub`.

🔗 [Исходники backend](https://github.com/Fairfay/report_task_backend)

🔗 [Исходники frontend](https://github.com/Fairfay/report_task_frontend)

🔗 [Исходники mobile](https://github.com/Fairfay/report_task_mobile)

**Детали:**
- **Какой эффект достигнут?**
Успешно выполненное тестовое задание с отзывами: "У тебя строгий код".
Получение нового опыта в разработке мобильных приложений.
- **Компания:** ООО "Абсолют ПОС"
- **Команда:**
Fullstack Developer - Тычин Денис Александрович

---

### 5. Foodgram
**Описание:** онлайн-платформа, где пользователи могут публиковать рецепты, просматривать рецепты других авторов, добавлять их в избранное, подписываться на любимых авторов и формировать список покупок для приготовления блюд.

🛠 Технологии: `Django`, `Django REST Framework`, `JWT`, `Djoser`, `Pillow`, `Pytest`, `Unittest`, `Postgres`, `React`, `Gunicorn`,
`Swagger`, `Nginx(gateway)`, `Docker`, `Docker Compose`, `Decouple`, `Axios`, `SPA`, `GitHub`, `DockerHub`, `Git Actions`, `CI/CD`.

🔗 [Исходники](https://github.com/Fairfay/foodgram)

**Детали:**
- **Какой эффект достигнут?**
Обучение и новый Pet  проект на Гите.
- **Компания:** АНО ДПО "Образовательные технологии Яндекса"
- **Команда:** Backend Developer - Тычин Денис Александрович

---

### 6. BS4ParserPEP
**Описание:** проект предназначен для парсинга официальной документации Python и PEP-документов с сайта peps.python.org. Парсер позволяет собирать и анализировать информацию о PEP, их статусах, а также получать другие полезные данные из документации Python.

🛠 Технологии: `BeautifulSoup4`, `PrettyTable`, `LXML`, `Pytest`, `tqdm`, `Request`, `GitHub`.

🔗 [Исходники](https://github.com/Fairfay/bs4_parser_pep)

**Детали:**
- **Какой эффект достигнут?**
Обучение и новый Pet проект на Гите.
- **Компания:** АНО ДПО "Образовательные технологии Яндекса"
- **Команда:** Backend Developer - Тычин Денис Александрович

---

### 7. YAcut
**Описание:** Сервис укорачивания ссылок. Его назначение — ассоциировать длинную пользовательскую ссылку с короткой, которую предлагает сам пользователь или предоставляет сервис. 

🛠 Технологии: `Flask`, `WTForms`, `Jinja2`, `Alembic`, `SQlAlchemy`, `Pytest`, `GitHub`.

🔗 [Исходники](https://github.com/Fairfay/yacut)

**Детали:**
- **Какой эффект достигнут?**
Обучение и новый Pet проект на Гите.
- **Компания:** АНО ДПО "Образовательные технологии Яндекса"
- **Команда:** Backend Developer - Тычин Денис Александрович

---

### 8. TaskForSecunda
**Описание:** REST API приложения для справочника Организаций, Зданий, Деятельности.

🛠 Технологии: `FastAPI`, `Uvicorn`, `SQlAlchemy`, `Alembic`, `FastAPIUsers`, `Pydantic`, `GitHub`, `Pytest`, `Asyncio`, `Postgres`, `asyncpg`, `aiosqlite`, `poetry`, `Docker`,
`Docker Compose`, `Makefile`, `JWT`, `Swagger`, `ReDoc`, `Static API KEY`.

🔗 [Исходники](https://github.com/Fairfay/test_task_for_secunda)

**Детали:**
- **Какой эффект достигнут?**
Получение опыта в разработке приложений на FastApi.
- **Компания:** ООО Секунда
- **Команда:** Backend Developer - Тычин Денис Александрович

---

### 9. ScrapyParserPep
**Описание:** веб-скрейпер, написанный на Scrapy, который собирает информацию о статусах PEP (Python Enhancement Proposals). Он парсит данные с официального сайта, анализирует статусы PEP и сохраняет результаты в CSV-файлы.

🛠 Технологии: `Scrapy`, `lxml`, `pytest`, `python`, `csv`.

🔗 [Исходники](https://github.com/Fairfay/scrapy_parser_pep)

**Детали:**
- **Какой эффект достигнут?**
Обучение и новый Pet проект на Гите.
- **Компания:** АНО ДПО "Образовательные технологии Яндекса"
- **Команда:** Backend Developer - Тычин Денис Александрович

### 10. Kittygram
**Описание:** социальная сеть для обмена фотографиями любимых питомцев. Это полностью рабочий проект, который состоит из бэкенд-приложения на Django и фронтенд-приложения на React.

🛠 Технологии: `Django`, `React`, `pytest`, `python`, `JWT`, `Djoser`, `Gunicorn`, `CI/CD`, `Postgres`, `psycopg2`, `Yaml`, `Telegram API`, `Docker`, `Docker Compose`, `Nginx(gateway)`,
`Axios`, `Git Actions`, `Django REST Framework`.

🔗 [Исходники](https://github.com/Fairfay/kittygram_final)

**Детали:**
- **Какой эффект достигнут?**
Обучение и новый Pet проект на Гите.
- **Компания:** АНО ДПО "Образовательные технологии Яндекса"
- **Команда:** Backend Developer - Тычин Денис Александрович

### 11. taskiDocker
**Описание:** приложение для планирования задач. Задачи можно добавлять, изменять, удалять и переводить из группы "незавершённые" в "завершённые". Деплой на удаленный сервер.

🛠 Технологии: `Django`, `React`, `pytest`, `python`, `JWT`, `Djoser`, `Gunicorn`, `CI/CD`, `Postgres`, `psycopg2`, `Yaml`, `Telegram API`, `Docker`, `Docker Compose`, `Nginx(gateway)`,
`Axios`, `Git Actions`, `Django REST Framework`.

🔗 [Исходники](https://github.com/Fairfay/taski-docker)

**Детали:**
- **Какой эффект достигнут?**
Обучение Docker, деплой на удаленный сервер и новый pet проект на Гите.
- **Компания:** АНО ДПО "Образовательные технологии Яндекса"
- **Команда:** Backend Developer - Тычин Денис Александрович



## 📈 Сертификаты
- [Диплом о профессиональной переподготовке по программе «Python-разработчик. Расширенный»](https://disk.yandex.ru/d/8t1hlWIhDqeRvg)
2025
- [Certificate of Completion of the Professional Training Course "Python Developer: Extended Program"](https://disk.yandex.ru/i/JsCZmhmEiT1rSw)
2025

- [Национальная система оценки ИТ - компетенций (PostgreSQL)](https://disk.yandex.ru/i/iXMnKAM72Y4jlQ)
2025

- [Национальная система оценки ИТ - компетенций (Linux)](https://disk.yandex.ru/i/Fjx9IkeBPdHoDA)
2025

- [Национальная система оценки ИТ - компетенций (Git)](https://disk.yandex.ru/i/86OmAAIDLgj4og)
2025

- [Национальная система оценки ИТ - компетенций (API)](https://disk.yandex.ru/i/CME2fqJxpy9Tdg)
2025

- [Национальная система оценки ИТ - компетенций (Docker)](https://disk.yandex.ru/d/tW5jf7Zdl7vihQ)
2025

- [Национальная система оценки ИТ - компетенций (ООП)](https://disk.yandex.ru/i/Qq5IFkcYo2fPUQ)
2025

- [Python Essentials:технологии разработки и Data-science: программирование нейросетей](https://certificate.2035.university/platform/151d1519-9488-4f8d-b5a8-fb146baef4a6.pdf?_ga=2.91036314.1878761641.1722759752-244255147.1716978652)
2024

- [Демонстрационный экзамен](https://pk.dp.firpo.ru/c/4d03dc6b-0b5b-47ec-ab1d-a22c96842b4c)
2024

- [Модуль 1: Python: Продвинутые стратегии и передовые практики](https://tsu-future-code-flow-prod-private.s3.yandexcloud.net/e1301f46-cec3-439d-9cb7-ae131901b813?AWSAccessKeyId=YCAJEOtCKEBq8QBrOtOL49DUY&Expires=1722762158&response-content-disposition=inline%3B%20filename%3D%221356404-7392-%D0%9C1.pdf%22&Signature=jU6dm1WGHm1vF1h89dwY%2FK91a9o%3D)
2024

- [Модуль 2: Работа с данными в Python](https://tsu-future-code-flow-prod-private.s3.yandexcloud.net/773a99ba-3242-4d05-b0b6-f5723752cf4d?AWSAccessKeyId=YCAJEOtCKEBq8QBrOtOL49DUY&Expires=1722762211&response-content-disposition=inline%3B%20filename%3D%221356404-7392-%D0%9C2.pdf%22&Signature=QEF%2F7uYA9CYaHvfZI%2FAETzL8Rqg%3D)
2024

- [Модуль 3: Работа с библиотеками Python](https://tsu-future-code-flow-prod-private.s3.yandexcloud.net/5e0c6543-4d54-45ce-b8cc-3a74777396d5?AWSAccessKeyId=YCAJEOtCKEBq8QBrOtOL49DUY&Expires=1722762231&response-content-disposition=inline%3B%20filename%3D%221356404-7392-%D0%9C3.pdf%22&Signature=XSFF0o00TScahoFzQA7KCL%2F89V8%3D)
2024

- [Модуль 4: Разработка приложений на Python](https://tsu-future-code-flow-prod-private.s3.yandexcloud.net/080ecedb-bc54-4af3-80b7-6ac96f2a11a1?AWSAccessKeyId=YCAJEOtCKEBq8QBrOtOL49DUY&Expires=1722762248&response-content-disposition=inline%3B%20filename%3D%221356404-7392-%D0%9C4.pdf%22&Signature=YItzify%2BrhzamCHuKuLWOx0tZcc%3D)
2024

- [«Профразвитие» АНО «Россия - страна возможностей»](https://rsv-testing.hb.bizmrg.com/reporting/%D0%A1%D0%B5%D1%80%D1%82%D0%B8%D1%84%D0%B8%D0%BA%D0%B0%D1%82%20%D1%83%D1%87%D0%B0%D1%81%D1%82%D0%BD%D0%B8%D0%BA%D0%B0%20%D0%BF%D1%80%D0%BE%D0%B5%D0%BA%D1%82%D0%B0%20%22%D0%9F%D1%80%D0%BE%D1%84%D1%80%D0%B0%D0%B7%D0%B2%D0%B8%D1%82%D0%B8%D0%B5%22%202023_62a14ad3-263d-4a0d-89a3-037fbe962b40.pdf)
2023

- [Разработка мобильных приложений](https://challenge.braim.org/certificates/bc719867-6226-4fbe-88fe-64c34cee1ba9)
2023

---

## 📬 Связь со мной
Email: tycindenis@gmail.com 
Telegram: @fairfay
Tenchat: https://tenchat.ru/4820355
Habr: https://career.habr.com/fairfay

---

## 📚 Полезные ссылки
- [Всегда актуальное резюме на HH](https://kemerovo.hh.ru/resume/bdd60bfcff0c2487160039ed1f447a6d306563)
- [Резюме Яндекс Диск](https://disk.yandex.ru/i/xtpzvtr3FQlf8Q)   
