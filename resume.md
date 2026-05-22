# Александр — AI Engineer | LLM Applications | RAG Systems | AI Agents

## 👤 Контакты
- **Telegram:** [@Tinkywinkyyyyy](https://t.me/Tinkywinkyyyyy)
- **GitHub:** {{github}}
- **Email:** {{email}}
- **Локация:** Georgia (open to remote / relocation)
- **Языки:** English (Upper-Intermediate), Russian (Native)

## 💡 О себе
Senior Full-Stack Developer (5.5+ лет) с переходом в AI Engineer. Строю production-grade LLM-приложения: мультимодальный RAG с OCR-пайплайном (Node.js + LangChain + LanceDB) и агентный RAG (FastAPI + LangGraph). Глубокая экспертиза в RAG-пайплайнах, Multi-Agent Systems, AI Agents с tool calling, мультимодальном инжесте, векторных базах и гибридном cloud/local деплое.

## 🛠️ Навыки

### AI / ML
Multi-Agent Systems, LLM (OpenAI, DeepSeek, Claude, Ollama), Prompt Engineering, RAG (Multimodal RAG, OCR pipelines), LangChain, LangGraph, CrewAI, AI Agents, Function Calling / Tool Use, Vector Databases (LanceDB, ChromaDB), Embeddings, FTS5, Structured Outputs, Hybrid cloud/local deployment

### Backend
Python (FastAPI, asyncio, Pydantic, pytest), Node.js (Express, TypeScript strict), PostgreSQL, SQLite (FTS5), Redis, MongoDB, REST API, GraphQL, Sequelize, Streaming (SSE)

### Frontend
Angular 21 (Signals, standalone components), Angular 2–15, TypeScript, Tailwind CSS 4, RxJS, Nx, Storybook, Vanilla JS, JavaScript (ES6+), HTML5/CSS, Next.js, React (personal)

### DevOps
Linux, Docker, docker-compose, VPS, nginx, systemd, SSH tunnels, Git, Pino observability

### Методологии
TDD (pytest), Agile, Kanban, Claude Design

## 🤖 AI & LLM проекты (2026)

### ContractAI — Multi-Agent Contract Intelligence (v0.5.0)
- 5 CrewAI агентов (extract, risk, compliance, negotiate, summarize) с 3-фазным параллельным пайплайном
- LangChain-лоадеры (PyPDF, DOCX, TXT), SQLite-персистентность, Swiss-brutalist дашборд
- DeepSeek V4 Pro LLM, Prometheus-метрики (persistent SQLite), always-on auth
- TDD с первого дня: 146 тестов, ruff clean, production-ready hardening
- **Стек:** Python 3.11+, CrewAI, LangChain, FastAPI, Pydantic v2, SQLite, DeepSeek, Docker, TDD

### Multimodal RAG CN Service — AI Engineer (Pet / Production-like)
- Полный мультимодальный ingestion pipeline (Markdown/Text + Images)
- OCR-архитектура: Vision LLM (primary) + tesseract.js (fallback), препроцессинг изображений (sharp), quality scoring
- Retrieval pipeline: RecursiveCharacterTextSplitter → embeddings → LanceDB с source attribution и score filtering
- Multi-turn чат с history-based retrieval и поддержкой контекста изображений
- Runtime model routing (OpenAI-compatible / DeepSeek / Ollama) и гибридные cloud/local профили
- Production Docker multi-stage image с healthchecks
- **Стек:** Node.js 20, TypeScript (strict), LangChain, LanceDB, Ollama, tesseract.js, sharp, Zod, Express, Pino, Docker

### AI Support Assistant (ai-python-bootcamp) — AI Engineer (Pet / Production-like)
- End-to-end RAG pipeline: document ingestion → chunking → embeddings (sentence-transformers) → ChromaDB
- LangGraph ReAct agent с tool calling (knowledge base search + ticket workflow)
- Streaming API (SSE), fallback to retrieval-only mode
- Typed configuration (pydantic-settings), strict typing (mypy), ruff linting
- Минимальный операторский фронтенд для real-time indexing и мониторинга чата
- **Стек:** Python 3.12, FastAPI, LangGraph, LangChain, ChromaDB, SentenceTransformers, PyTorch, CUDA, Docker, SSE

## 🚀 Featured проекты

### Product Launcher AI — Multi-Agent System
Мультиагентная система: 11 специализированных агентов, PM-оркестратор, live-дашборд. Полный пайплайн от брошюры/входа до готового контента на 4 платформах.
- **Стек:** Python, Hermes Agent, SQLite, Kanban workflow

### AI Knowledge Base
База знаний на 2000+ постов из Telegram AI-каналов. Полнотекстовый поиск SQLite FTS5 — в 10 раз быстрее стандартных LIKE-запросов.

### Angular CV — Premium Portfolio Website
Современное портфолио на Angular 21: 9 standalone-компонентов, glassmorphism, тёмная/светлая тема, PDF-экспорт. Бандл: 211 KB (56 KB gzipped).

## 💼 Опыт работы

### JS Full-Stack Developer — Georgia USA information aggregator (Team of 6)
*06/2020 – Present*
- Разработка продвинутых UI-компонентов для динамической визуализации данных → значительный рост вовлечённости пользователей
- Инновационные архитектурные решения → +30% масштабируемости системы
- Оптимизация производительности → -25% времени загрузки
- Лидирование bug-fixing инициатив → радикальное снижение даунтайма и повышение надёжности

### JS Full-Stack Developer — Sunmait, Minsk
*05/2019 – 06/2020*
- **Japan Tobacco International:** админ-панель + бэкенд мобильного приложения → +40% эффективности администрирования, +50% быстрее запросы
- **Sfera:** высоконагруженный магазин одежды → фичи, принесшие +20% трафика и продаж, 99.9% uptime
- **Web Manufacturer Platform:** управление заказами и отслеживание статусов → +35% операционной эффективности

### Frontend Developer — AOT, Minsk
*09/2018 – 05/2019*
- Портал Федерального агентства: ключевые frontend-фичи + рефакторинг легаси-кода
- IT Events Hosting Website: full-stack фичи → +30% вовлечённости пользователей

## 🎓 Образование
- **Master of Information Technologies** — Belarusian State University of Informatics and Radioelectronics, Minsk (2021)
- **Programmer Economist** — Belarusian State University of Informatics and Radioelectronics, Minsk (2019)

## 📚 Что я изучил (авто-обновляется ежедневно)

*Последнее обновление: 2026-05-21*

- **2026-05-21** — ContractAI v0.5.0: 5 CrewAI агентов, 3-фазный параллельный пайплайн, LangChain-лоадеры, 146 тестов TDD, production-ready hardening (auth, Prometheus, i18n)
- **2026-05-12** — Angular 21 (standalone-компоненты, Signals), Tailwind CSS 4, TypeScript, Claude Design методология (design system, anti-slop rules, motion study), html2pdf.js
- **2026-05-11** — Multi-Agent Hermes IT-команда: 5 профилей (orchestrator, developer, researcher, qa, designer), SOUL.md, Kanban-оркестрация
- **2026-05-09** — Multi-Agent система Product Launcher AI: 11 агентов, PM-оркестратор, Kanban, live-дашборд

## 🎯 Цель
Позиции AI Engineer, ML Engineer, LLM Applications Engineer в компаниях, создающих AI-продукты. Интересны RAG-системы, мультиагентные архитектуры и production-grade AI-решения.
