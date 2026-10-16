# :wave: Привет, я Даниил (`pyromeowww`)

> *Чистый код, чистая совесть, ноль долгов, ревью доволен* 🕊️

<p align="left">
  <img src="https://img.shields.io/badge/Role-Junior%20Go%20Developer-00ADD8?style=flat-square&logo=go&logoColor=white" />
  <img src="https://img.shields.io/badge/Location-Kazan%2C%20Russia-red?style=flat-square" />
  <img src="https://img.shields.io/badge/Status-Open%20for%20opportunities-brightgreen?style=flat-square" />
</p>

---

### :boy: О себе

Я backend-разработчик на **Go**. Мне нравится проектировать предсказуемые и устойчивые **REST API**, разбираться с реляционными базами данных и писать чистый, поддерживаемый код с понятной архитектурой.

* :laptop: **Фокус разработки:** Построение надёжной бизнес-логики, обработка ошибок, работа с JSON и оптимизация запросов к БД.
* :bullseye: **Мой подход:** Писать понятную структуру пакетов (`pkg/`), покрывать ключевой функционал unit-тестами и не усложнять архитектуру без необходимости (KISS).
* :books: **Текущие задачи:** Погружение в глубокие нюансы конкурентности Go (goroutines/channels) и проектирование микросервисных архитектур.

---

### :desktop_computer: Основной стек
<p>
  <img src="https://img.shields.io/badge/Go-00ADD8?style=flat-square&logo=go&logoColor=white" />
  <img src="https://img.shields.io/badge/REST_API-005571?style=flat-square" />
  <img src="https://img.shields.io/badge/JSON-000000?style=flat-square&logo=json&logoColor=white" />
  <img src="https://img.shields.io/badge/SQLite-003B57?style=flat-square&logo=sqlite&logoColor=white" />
</p>

* **Язык & REST API:** Go (Golang), проектирование RESTful эндпоинтов, обработка JSON
* **Стандартная библиотека:** `net/http`, `encoding/json`, `database/sql`, `time`, `os`, `context`, `strconv`, `fmt`, `log`, `testing`
* **Архитектура & Подходы:** Clean Package Structure (`pkg/`), Unit-тестирование, Graceful Shutdown
* **Базы данных:** SQLite (`modernc.org/sqlite`), проектирование схем, индексация полей и управление соединениями

### :toolbox: Дополнительные навыки и инструменты
<p>
  <img src="https://img.shields.io/badge/Docker-2496ED?style=flat-square&logo=docker&logoColor=white" />
  <img src="https://img.shields.io/badge/Git-F05032?style=flat-square&logo=git&logoColor=white" />
  <img src="https://img.shields.io/badge/Linux-FCC624?style=flat-square&logo=linux&logoColor=black" />
  <img src="https://img.shields.io/badge/Bash-4EAA25?style=flat-square&logo=gnu-bash&logoColor=white" />
</p>

* **Контейнеризация:** `Docker` (написание `Dockerfile` для сборки минимальных образов Go-приложений)
* **Окружение & Модули:** `Linux / Bash`, переменные окружения (`os.Getenv`), управление зависимостями через `go.mod`
* **Контроль версий:** `Git` (ветки, коммиты, работа с GitHub)

---

### :rocket: Флагманский проект

#### :calendar: [Task Scheduler](https://github.com/pyromeowww/task-scheduler)
*REST API сервис для автоматического планирования и расчёта повторения задач.*

* **Стек:** Go (`net/http`), SQLite (`modernc.org/sqlite`), Docker.
* **Инженерные решения:**
  * Разделил архитектуру на модули: изолировал логику работы с БД (`pkg/db`) и HTTP-обработчики (`pkg/server`).
  * Реализовал RESTful API эндпоинты с парсингом JSON-запросов и корректной обработкой HTTP-ошибок.
  * Написал кастомный алгоритм расчета правил повторения задач (дни, месяцы, года) с помощью пакета `time` и покрыл его тестами.
  * Спроектировал схему БД SQLite с индексацией по дате для быстрых выборок и автоматической инициализацией при старте.
  * Настроил конфигурацию сервиса через переменные окружения (`os.Getenv`).

---

### :mailbox_with_mail: Контакты для связи

* **Telegram:** [@pyromeowww](https://t.me/pyromeowww)
* **Email:** `daniilackov21@gmail.com`
* **GitHub:** [pyromeowww](https://github.com/pyromeowww)
