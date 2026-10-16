# 👋 Привет, я Даниил (`pyromeowww`)

> *Чистый код, чистая совесть, ноль долгов, ревью доволен* 🕊️

<p align="left">
  <img src="https://img.shields.io/badge/Role-Junior%20Go%20Developer-00ADD8?style=flat-square&logo=go&logoColor=white" />
  <img src="https://img.shields.io/badge/Location-Kazan%2C%20Russia-red?style=flat-square" />
  <img src="https://img.shields.io/badge/Status-Open%20for%20opportunities-brightgreen?style=flat-square" />
</p>

Backend-разработчик на **Go**. Специализируюсь на проектировании REST API, проектировании схем реляционных баз данных и написании чистых, поддерживаемых сервисов.

---

### 💻 Основной стек
<p>
  <img src="https://img.shields.io/badge/Go-00ADD8?style=flat-square&logo=go&logoColor=white" />
  <img src="https://img.shields.io/badge/REST_API-005571?style=flat-square" />
  <img src="https://img.shields.io/badge/JSON-000000?style=flat-square&logo=json&logoColor=white" />
  <img src="https://img.shields.io/badge/SQLite-003B57?style=flat-square&logo=sqlite&logoColor=white" />
</p>

* **Стандартная библиотека:** `net/http`, `encoding/json`, `database/sql`, `time`, `os`, `testing`
* **Архитектура & Подходы:** Clean Package Structure (`pkg/`), Unit-тестирование, Graceful Shutdown
* **Базы данных:** SQLite (`modernc.org/sqlite`), проектирование схем, индексация полей и управление соединениями

### 🧰 Дополнительные навыки и инструменты
<p>
  <img src="https://img.shields.io/badge/Docker-2496ED?style=flat-square&logo=docker&logoColor=white" />
  <img src="https://img.shields.io/badge/Git-F05032?style=flat-square&logo=git&logoColor=white" />
  <img src="https://img.shields.io/badge/Linux-FCC624?style=flat-square&logo=linux&logoColor=black" />
  <img src="https://img.shields.io/badge/Bash-4EAA25?style=flat-square&logo=gnu-bash&logoColor=white" />
</p>

* **Инструменты & Сборка:** Docker, Git, Linux / Bash, Go Modules (`go.mod`)
* **Конфигурация:** Переменные окружения (`os.Getenv`) с фолбэками по умолчанию

---

### 🚀 Флагманский проект

#### 📅 [Task Scheduler](https://github.com/pyromeowww/task-scheduler)
*REST API сервис для автоматического планирования и расчёта повторения задач.*

* **Стек:** Go (`net/http`), SQLite (`modernc.org/sqlite`), Docker.
* **Инженерные решения:**
  * Разделил архитектуру на модули: изолировал логику работы с БД (`pkg/db`) и HTTP-обработчики (`pkg/server`).
  * Реализовал RESTful API эндпоинты с парсингом JSON-запросов и корректной обработкой HTTP-ошибок.
  * Написал кастомный алгоритм расчета правил повторения задач (дни, месяцы, года) с помощью пакета `time` и покрыл его тестами.
  * Спроектировал схему БД SQLite с индексацией по дате для быстрых выборок и автоматической инициализацией при старте.
  * Настроил конфигурацию сервиса через переменные окружения (`os.Getenv`).

---

### 📬 Контакты для связи

* **Telegram:** [@pyromeowww](https://t.me/pyromeowww)
* **Email:** `daniilackov21@gmail.com`
* **GitHub:** [pyromeowww](https://github.com/pyromeowww)
