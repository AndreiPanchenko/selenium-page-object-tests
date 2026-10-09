# Stepik Selenium Page Object

Учебный проект с автотестами для интернет-магазина [selenium1py](http://selenium1py.pythonanywhere.com/).

## Структура

- `pages/` — Page Object классы
- `conftest.py` — фикстура браузера с параметром `--language`
- `test_main_page.py` — тесты главной страницы
- `test_product_page.py` — тесты страницы товара

## Запуск

```bash
pytest -v --language=en
