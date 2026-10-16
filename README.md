<table>
  <tr>
    <td width="220" align="center" style="border: none;">
      <img src="./assets/go-dead-ahead-zombie-warfare.gif" width="200" alt="Go Dead Ahead Zombie Warfare" />
    </td>
    <td style="border: none;" valign="middle">
      <h1>Привет!</h1>
      <h2>Я Даниил (<code>pyromeowww</code>)</h2>
      <p><b>Junior Go (Golang) Backend Developer</b></p>
      <p><i>«Чистый код, чистая совесть, ноль технического долга»</i> 🕊️</p>
    </td>
  </tr>
</table>

<p align="left">
  <a href="https://t.me/pyromeowww"><img src="https://img.shields.io/badge/Telegram-2CA5E0?style=for-the-badge&logo=telegram&logoColor=white" /></a>
  <a href="mailto:daniilackov21@gmail.com"><img src="https://img.shields.io/badge/Gmail-D14836?style=for-the-badge&logo=gmail&logoColor=white" /></a>
  <a href="https://github.com/pyromeowww"><img src="https://img.shields.io/badge/GitHub-100000?style=for-the-badge&logo=github&logoColor=white" /></a>
</p>

<div data-importer="profile-views" align="left">
  <img data-importer="profile-views" src="https://visitor-badge.laobi.icu/badge?page_id=pyromeowww.pyromeowww&left_color=midnightblue" height="30" />
</div>

---

### 💻 Стек и технологии

* **Язык & Core:** Go (Golang), RESTful API, JSON.
* **Стандартная библиотека:** `net/http`, `database/sql`, `encoding/json`, `time`, `os`, `context`, `strconv`, `fmt`, `log`, `testing`.
* **Базы данных:** SQLite (`modernc.org/sqlite`), проектирование реляционных схем, индексация.
* **Инфраструктура & Tools:** Docker (`Dockerfile`), Linux / Bash, Git, Go Modules (`go.mod`).
* **Архитектурные подходы:** Clean Package Structure (`pkg/`), Unit-тестирование, Graceful Shutdown.

---

### 🚀 Флагманский проект

#### 📌 [Task Scheduler](https://github.com/pyromeowww/task-scheduler)
*REST API сервис для автоматического планирования и расчёта повторения задач.*

* **Архитектура:** Разделение модулей на логику БД (`pkg/db`) и HTTP-обработчики (`pkg/server`).
* **Бизнес-логика:** Кастомный алгоритм расчета правил повторения (дни, месяцы, года) на базе пакета `time`, полностью покрытый Unit-тестами.
* **Хранилище:** Схема БД SQLite с индексацией по дате для мгновенных выборок и автоинициализацией.
* **Окружение:** Конфигурация через переменные окружения (`os.Getenv`), сборка в минимальный Docker-образ.

---

### 📊 Статистика активности

<p align="left">
  <img src="https://github-readme-stats.vercel.app/api?username=pyromeowww&show_icons=true&theme=vue-dark&hide_border=true&count_private=true" height="165" />
  <img src="https://github-readme-stats.vercel.app/api/top-langs/?username=pyromeowww&layout=compact&theme=vue-dark&hide_border=true" height="165" />
</p>
