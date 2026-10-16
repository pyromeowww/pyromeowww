<table>
  <tr>
    <td width="220" align="center" style="border: none;">
      <img src="./assets/go-dead-ahead-zombie-warfare.gif" width="200" alt="Go Dead Ahead Zombie Warfare" />
    </td>
    <td style="border: none;" valign="middle">
      <h1>Привет!</h1>
      <h2>Я Даниил (<code>pyromeowww</code>)</h2>
      <p><b>Junior Go (Golang) Backend Developer</b></p>
      <p><i>«Чистый код, чистая совесть, ноль технического долга»</i></p>
    </td>
  </tr>
</table>

<p align="left">
  <img src="https://img.shields.io/badge/Role-Junior%20Go%20Developer-00ADD8?style=flat-square&logo=go&logoColor=white" />
  <img src="https://img.shields.io/badge/Location-Kazan%2C%20Russia-red?style=flat-square" />
  <img src="https://img.shields.io/badge/Status-Open%20for%20opportunities-brightgreen?style=flat-square" />
</p>

---

### 🛠️ Мои инструменты и стек

#### 💻 Языки программирования & Тестирование
<p align="left">
  <img src="https://img.shields.io/badge/Go-00ADD8?style=for-the-badge&logo=go&logoColor=white" alt="Go" />
  <img src="https://img.shields.io/badge/Unit_Tests-C21325?style=for-the-badge&logo=testinglibrary&logoColor=white" alt="Unit Tests" />
  <img src="https://img.shields.io/badge/Bash-4EAA25?style=for-the-badge&logo=gnu-bash&logoColor=white" alt="Bash" />
</p>

#### 🗄️ Базы данных & Хранилища
<p align="left">
  <img src="https://img.shields.io/badge/SQLite-07405e?style=for-the-badge&logo=sqlite&logoColor=white" alt="SQLite" />
</p>

#### ⚙️ Бэкенд & API
<p align="left">
  <img src="https://img.shields.io/badge/REST_API-005571?style=for-the-badge&logo=postman&logoColor=white" alt="REST API" />
  <img src="https://img.shields.io/badge/Standard_Library-00ADD8?style=for-the-badge&logo=go&logoColor=white" alt="Standard Library" />
  <img src="https://img.shields.io/badge/Postman-FF6C37?style=for-the-badge&logo=postman&logoColor=white" alt="Postman" />
</p>

#### 🐳 Инфраструктура & Инструменты
<p align="left">
  <img src="https://img.shields.io/badge/Docker-2496ED?style=for-the-badge&logo=docker&logoColor=white" alt="Docker" />
  <img src="https://img.shields.io/badge/Git-F05032?style=for-the-badge&logo=git&logoColor=white" alt="Git" />
  <img src="https://img.shields.io/badge/Linux-FCC624?style=for-the-badge&logo=linux&logoColor=black" alt="Linux" />
  <img src="https://img.shields.io/badge/GitHub-100000?style=for-the-badge&logo=github&logoColor=white" alt="GitHub" />
</p>

---

### 🚀 Флагманский проект

#### 📌 [Task Scheduler](https://github.com/pyromeowww/task-scheduler)
*Автономный REST API сервис для гибкого автоматического планирования и расчёта повторения задач.*

<p align="left">
  <img src="https://img.shields.io/badge/Go-00ADD8?style=flat-square&logo=go&logoColor=white" />
  <img src="https://img.shields.io/badge/SQLite-07405e?style=flat-square&logo=sqlite&logoColor=white" />
  <img src="https://img.shields.io/badge/REST_API-005571?style=flat-square&logo=postman&logoColor=white" />
  <img src="https://img.shields.io/badge/Docker-2496ED?style=flat-square&logo=docker&logoColor=white" />
  <img src="https://img.shields.io/badge/Unit_Tests-100%25-brightgreen?style=flat-square&logo=testinglibrary&logoColor=white" />
</p>

* ⚡ **Чистая архитектура:** Чёткое разделение модулей на слой бизнес-логики БД (`pkg/db`) и HTTP-обработчики (`pkg/server`).
* 🗓️ **Бизнес-логика:** Кастомный алгоритм расчета правил повторения (дни, месяцы, года) на базе пакета `time`, полностью покрытый **Unit-тестами**.
* 📊 **Хранилище:** Реляционная схема SQLite с индексацией по дате для мгновенных выборок и автоинициализацией.
* 🐳 **Окружение:** Конфигурация через переменные окружения (`os.Getenv`), сборка в минимальный Docker-образ и локальное тестирование через Postman.

##### 💡 Инженерные решения & Особенности реализации:
* 🎯 **Обработка edge-cases в календаре:** Алгоритм вычисления даты `NextDate` корректно обрабатывает переходы через высокосные года, разное количество дней в месяцах и границы часовых поясов.
* ⚡ **Индексация для быстрых выборок:** Таблица задач содержит B-Tree индекс по полю `date`, что обеспечивает мгновенную выборку актуальных задач ($O(\log N)$) даже при росте объема данных.
* 🛡️ **Zero-CGO SQLite:** Использование CGO-free драйвера `modernc.org/sqlite` позволило собрать полностью статический и легкий бинарник Go без внешних C-зависимостей.
* 🔄 **Fail-safe инициализация:** Автоматическая проверка и накатывание схемы БД при старте приложения с дефолтным фоллбэком пути к файлу базы.

<p align="left">
  <a href="https://github.com/pyromeowww/task-scheduler">
    <img src="https://img.shields.io/badge/View_Repository-100000?style=for-the-badge&logo=github&logoColor=white" />
  </a>
</p>

---

### 📬 Контакты для связи

<p align="left">
  <a href="https://t.me/pyromeowww"><img src="https://img.shields.io/badge/Telegram-pyromeowww-2CA5E0?style=for-the-badge&logo=telegram&logoColor=white" /></a>
  <a href="mailto:daniilackov21@gmail.com"><img src="https://img.shields.io/badge/Gmail-daniilackov21-D14836?style=for-the-badge&logo=gmail&logoColor=white" /></a>
  <a href="https://github.com/pyromeowww"><img src="https://img.shields.io/badge/GitHub-pyromeowww-100000?style=for-the-badge&logo=github&logoColor=white" /></a>
</p>

---
### 📊 Статистика активности

<p align="left">
  <img src="https://github-readme-stats.vercel.app/api?username=pyromeowww&show_icons=true&theme=vue-dark&hide_border=true&count_private=true" height="165" />
  <img src="https://github-readme-stats.vercel.app/api/top-langs/?username=pyromeowww&layout=compact&theme=vue-dark&hide_border=true" height="165" />
</p>

<div data-importer="profile-views" align="left">
  <img data-importer="profile-views" src="https://visitor-badge.laobi.icu/badge?page_id=pyromeowww.pyromeowww&left_color=midnightblue" height="150" />
</div>
