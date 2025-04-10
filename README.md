# Стек технологий

- **[httpx](https://www.python-httpx.org/)** — асинхронный HTTP-клиент для Python. Быстрый и удобный инструмент для работы с HTTP-запросами.
- **[pydantic](https://pydantic-docs.helpmanual.io/)** — библиотека для валидации и работы с данными, которая позволяет легко управлять типами данных и проверками.
- **[python-dotenv](https://pypi.org/project/python-dotenv/)** — позволяет загружать переменные окружения из `.env` файла, что упрощает настройку проекта и работу с конфиденциальной информацией.
- **[uv](https://docs.astral.sh/uv/)** — быстрый и надёжный менеджер зависимостей, который упрощает установку и управление библиотеками Python. Аналог pip и poetry.

## Установка и активация виртуального окружения

uv venv
source .venv/Scripts/activate        # Windows
source .venv/bin/activate            # WSL / Git Bash / Linux / macOS
uv pip install

Запуск:
python -m antworker