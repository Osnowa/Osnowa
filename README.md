<div align="center">

<img src="https://readme-typing-svg.demolab.com?font=Fira+Code&size=24&pause=1000&color=2E9EF7&center=true&vCenter=true&width=600&lines=QA+Engineer+%2F+AQA;Backend+%7C+Python+%7C+FastAPI;Linux+%7C+SysAdmin;%D0%9C%D0%BE%D1%81%D0%BA%D0%B2%D0%B0%2C+%D0%A0%D0%BE%D1%81%D1%81%D0%B8%D1%8F" alt="Typing SVG" />

### <a href="#ru">🇷🇺 Русский</a>&nbsp;&nbsp;|&nbsp;&nbsp;<a href="#en">🇬🇧 English</a>

</div>

---

<a name="ru"></a>

## 🇷🇺 Илья Савин

**QA Engineer / AQA** с сильной практической базой в Python-разработке — тестирую, но пишу свой собственный backend, разворачиваю его в Docker и покрываю тестами.

📍 Москва &nbsp;•&nbsp; ✉️ ilja.savin18@yandex.ru &nbsp;•&nbsp; 💬 Telegram: *[добавь свой @username]*

Захожу в IT через тестирование — но за плечами уже полноценный опыт backend-разработки (FastAPI, PostgreSQL, Docker, CI/CD) и системного администрирования Linux. Дальше — QA/AQA с прицелом на автоматизацию и, в перспективе, backend.

---

### 🧰 Стек и инструменты

**Тестирование / QA**
<img src="https://skillicons.dev/icons?i=postman&theme=dark" height="32"/> &nbsp;
<img alt="Jira" width="32" src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/jira/jira-original.svg"/> &nbsp;
<img alt="Figma" width="32" src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/figma/figma-original.svg"/> &nbsp;
<img alt="pytest" width="32" src="https://raw.githubusercontent.com/pytest-dev/pytest/main/doc/en/img/pytest_logo_curves.svg"/>

`Test IT` · `TestRail` · `Postman` (REST + SOAP) · `Charles Proxy` · `Chrome DevTools` · `pytest / mock / testcontainers`

**Backend**
<img src="https://skillicons.dev/icons?i=python,fastapi,docker&theme=dark" height="32"/>

`Python 3.11+` · `FastAPI` · `SQLAlchemy (Async)` · `Alembic` · `Pydantic` · `JWT / RBAC` · `Aiogram 3`

**Базы данных**
<img src="https://skillicons.dev/icons?i=postgres,mysql,mongodb,redis,sqlite&theme=dark" height="32"/>

**DevOps / Linux**
<img src="https://skillicons.dev/icons?i=linux,bash,docker,nginx,git,github,githubactions&theme=dark" height="32"/>

`systemd` · `cron` · `ufw` · `SSH` · `сети (OSI/TCP-IP, NAT, маршрутизация)` · `GitHub Actions CI/CD` · `VPS-деплой`

**Инструменты**
<img src="https://skillicons.dev/icons?i=vscode,pycharm&theme=dark" height="32"/>

---

### 🚀 Проекты

#### 📋 Task Manager API + Telegram Bot — флагманский pet-проект
REST API (FastAPI) + Telegram-бот (Aiogram 3) как единое приложение — не учебный CRUD, а полноценная многосервисная архитектура.

`FastAPI` `SQLAlchemy` `Alembic` `JWT` `Redis (токены + FSM)` `Docker Compose` `pytest/httpx` `GitHub Actions` `Ruff`

- JWT-авторизация + middleware
- Полностью асинхронное приложение и работа с БД
- Telegram FSM на Redis Storage
- Unit/Integration-тесты, CI, линтинг
- Отдельные конфиги для dev и prod (`docker-compose.dev.yml`)

🔗 *[ссылка на репозиторий]*

#### 🔁 DNF — серия учебных проектов (прогресс от версии к версии)
Один и тот же учебный backend, последовательно усложняемый — хорошо показывает рост от простого CRUD до продакшн-практик.

| Версия | Что добавлено | Стек |
|---|---|---|
| [Docker_Nginx_FastAPI](https://github.com/Osnowa/Docker_Ngnix_FastAPI.git) | Базовый FastAPI + SQLite + Docker + Nginx (reverse proxy) | FastAPI, aiosqlite, Docker |
| [Docker_Nginx_FastAPI_V2](https://github.com/Osnowa/Docker_Ngnix_FastAPI_V2.git) | + ORM, скрипт наполнения БД | + SQLAlchemy |
| [DNF_V3](https://github.com/Osnowa/DNF_V3.git) | CRUD, роутеры/схемы/репозитории, интеграционные тесты | + PostgreSQL, Alembic, pytest/httpx |
| [DNF_V4](https://github.com/Osnowa/DNF_V4.git) | Регистрация/логин, JWT, роли (RBAC), покрытие тестами 93% | + JWT auth |
| [DNF_V5](https://github.com/Osnowa/DNF_V5.git) | Переход на MongoDB, полный CI/CD (GitHub Actions → GHCR → деплой на VPS по SSH) | + MongoDB, Beanie, Testcontainers |
| [DNF_V6](https://github.com/Osnowa/DNF_V6.git) | Redis-кэширование (Cache-Aside, TTL, инвалидация) | + Redis |

#### 🎮 Telegram-боты
| Проект | Описание | Стек |
|---|---|---|
| [Bot_roll_dice](https://github.com/Osnowa/Bot_roll_dice.git) | Кости против бота, лидерборд, слоистая архитектура (Handlers → Services → Repository → DB) | Aiogram 3, PostgreSQL, SQLAlchemy Async, Redis, Docker, GitHub Actions CI |
| [Bot_QN](https://github.com/Osnowa/Bot_QN.git) | «Угадай число» — FSM, игровые сессии | Aiogram 3, PostgreSQL, Redis, Docker |
| [Bot_RP](https://github.com/Osnowa/Bot_RP.git) | «Камень-ножницы-бумага» с суперсилой ONE PUNCH MAN, юнит-тесты | Aiogram 3, SQLite, pytest/mock |

---

### 🧪 Тестовые артефакты

Портфолио ручного и AQA-тестирования: тест-планы, чек-листы, тест-кейсы (Test IT), баг-репорты (Jira), Postman-коллекции (REST + SOAP).

- 📱 Тестирование мобильного приложения — тест-кейсы + баг-репорты в Jira (валидация ввода, GUI-баги)
- 🛒 Тестирование веб-магазина (demoshopping.ru) — сверка с Figma-макетом, баги вёрстки, сортировки, авторизации
- 🔌 API-тестирование — Postman-коллекции: REST (DemoShopping) и SOAP (CountryInfoService, WSDL)
- 📚 Тест-дизайн — эквивалентное разбиение, таблицы принятия решений, чек-листы

🔗 *[ссылка на репозиторий с тестовой документацией]*

---

### 📈 Активность и обучение

**Stepik** — [профиль](https://stepik.org/users/588511871/profile) · 9 253 решённые задачи · 271 репутация · 9.2K знаний · макс. серия 167 дней

Пройдено 24+ курса, включая: `Python-разработчик` · `"Поколение Python"` (начальный/продвинутый/для профессионалов/ООП) · `Асинхронный Python` · `SQL с нуля до PRO` · `Django, потанцуем?` · `Знакомство с Docker` · `Терминал Linux` · `Тестирование ПО` (2 курса) · `Основы Git и GitHub` · `Go — первое знакомство`

**LeetCode** — *[ссылка на профиль]*

---
<br>

<a name="en"></a>

## 🇬🇧 Ilya Savin

**QA Engineer / AQA** with a strong hands-on background in Python development — I test software, but I also build my own backends, containerize them with Docker, and cover them with tests.

📍 Moscow &nbsp;•&nbsp; ✉️ ilja.savin18@yandex.ru &nbsp;•&nbsp; 💬 Telegram: *[add your @username]*

Entering IT through QA/testing — backed by real backend development experience (FastAPI, PostgreSQL, Docker, CI/CD) and Linux system administration. Currently focused on QA/AQA with an eye toward automation and, longer-term, backend work.

---

### 🧰 Stack & Tools

**Testing / QA:** Test IT, TestRail, Postman (REST + SOAP), Jira, Figma, Charles Proxy, Chrome DevTools, pytest/mock/testcontainers

**Backend:** Python 3.11+, FastAPI, SQLAlchemy (Async), Alembic, Pydantic, JWT/RBAC, Aiogram 3

**Databases:** PostgreSQL, MySQL, MongoDB, Redis, SQLite

**DevOps / Linux:** Docker, Docker Compose, Nginx, systemd, cron, ufw, SSH, networking (OSI/TCP-IP, NAT, routing), GitHub Actions CI/CD, VPS deployment

**Tools:** VS Code, PyCharm, Git/GitHub

---

### 🚀 Projects

#### 📋 Task Manager API + Telegram Bot — flagship pet project
A REST API (FastAPI) and a Telegram bot (Aiogram 3) working together as one application — not a tutorial CRUD, but a real multi-service architecture.

`FastAPI` `SQLAlchemy` `Alembic` `JWT` `Redis (tokens + FSM)` `Docker Compose` `pytest/httpx` `GitHub Actions` `Ruff`

- JWT auth with middleware, fully async app and DB layer
- Telegram FSM backed by Redis storage
- Unit/integration tests, CI, linting
- Separate dev/prod Docker Compose configs

🔗 *[repository link]*

#### 🔁 DNF series — iterative learning project
The same backend, progressively extended — a clear line from basic CRUD to production-style practices.

| Version | What's new | Stack |
|---|---|---|
| [Docker_Nginx_FastAPI](https://github.com/Osnowa/Docker_Ngnix_FastAPI.git) | Base FastAPI + SQLite + Docker + Nginx reverse proxy | FastAPI, aiosqlite, Docker |
| [Docker_Nginx_FastAPI_V2](https://github.com/Osnowa/Docker_Ngnix_FastAPI_V2.git) | + ORM, seed script | + SQLAlchemy |
| [DNF_V3](https://github.com/Osnowa/DNF_V3.git) | CRUD, routers/schemas/repositories, integration tests | + PostgreSQL, Alembic, pytest/httpx |
| [DNF_V4](https://github.com/Osnowa/DNF_V4.git) | Registration/login, JWT, roles (RBAC), 93% test coverage | + JWT auth |
| [DNF_V5](https://github.com/Osnowa/DNF_V5.git) | Switched to MongoDB, full CI/CD (GitHub Actions → GHCR → SSH deploy to VPS) | + MongoDB, Beanie, Testcontainers |
| [DNF_V6](https://github.com/Osnowa/DNF_V6.git) | Redis caching (Cache-Aside, TTL, invalidation) | + Redis |

#### 🎮 Telegram bots
| Project | Description | Stack |
|---|---|---|
| [Bot_roll_dice](https://github.com/Osnowa/Bot_roll_dice.git) | Dice game vs bot, leaderboard, layered architecture (Handlers → Services → Repository → DB) | Aiogram 3, PostgreSQL, SQLAlchemy Async, Redis, Docker, GitHub Actions CI |
| [Bot_QN](https://github.com/Osnowa/Bot_QN.git) | Number-guessing game — FSM, game sessions | Aiogram 3, PostgreSQL, Redis, Docker |
| [Bot_RP](https://github.com/Osnowa/Bot_RP.git) | Rock-Paper-Scissors with a ONE PUNCH MAN superpower, unit-tested | Aiogram 3, SQLite, pytest/mock |

---

### 🧪 Testing Artifacts

Manual & AQA testing portfolio: test plans, checklists, test cases (Test IT), bug reports (Jira), Postman collections (REST + SOAP).

- 📱 Mobile app testing — test cases + Jira bug reports (input validation, GUI bugs)
- 🛒 Web shop testing (demoshopping.ru) — Figma design comparison, layout/sorting/auth bugs
- 🔌 API testing — Postman collections: REST (DemoShopping) and SOAP (CountryInfoService, WSDL)
- 📚 Test design — equivalence partitioning, decision tables, checklists

🔗 *[link to testing documentation repository]*

---

### 📈 Learning & Activity

**Stepik** — [profile](https://stepik.org/users/588511871/profile) · 9,253 problems solved · 271 reputation · 9.2K knowledge points · 167-day max streak

24+ completed courses, including: `Python Developer` · `"Python Generation"` series (basic/advanced/professional/OOP) · `Async Python` · `SQL from Zero to PRO` · `Django` · `Docker Basics` · `Linux Terminal` · `Software Testing` (2 courses) · `Git & GitHub Basics` · `Go — First Steps`

**LeetCode** — *[profile link]*

</div>
