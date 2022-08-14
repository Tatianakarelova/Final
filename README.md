# Final

Финальный тестовый проект SkillFactory курса QAP

Автоматизированное тестирование UI сайта: https://market.yandex.ru/?utm_source_service=web&clid=703&src_pof=703&icookie=kH0ZqnEKOgESFZSmN0ysNkaW2G1vaqVP7nRAMKX0Azta4RC4PG910WAKt0i8lAWN85HqAILD7e9GWgp5k8l6CTodk4A%3D&baobab_event_id=l6t2f59xz8с использованием PyTest и Selenium.

С тест-кейсами можно ознакомиться по ссылке: https://docs.google.com/spreadsheets/d/1lSbJIRyfpjAPeLcxADUKU7Bgwi8yyOezF_JbeDqSkuc/edit?usp=sharing
В папке pages в файле base_page.py находится конструктор webdriver.
В папке pages в файлах cart_page.py, main_page.py, search_page.py находятся методы для тестируемых страниц.

В папке pages в файле "locators.py находятся все локаторы.

В корне проекта в файле conftest.py находится фикстура с функцией открытия и закрытия браузера.

В корне проекта в файле pytest.ini зарегистрированны метки маркеровок тестов.

В корне проекта в файлах test_cart_page.py, test_main_page.py, test_search_page.py находятся тесты. Все тесты помечены номером который совпадает с номером тест-кейса в файле:https://docs.google.com/spreadsheets/d/1lSbJIRyfpjAPeLcxADUKU7Bgwi8yyOezF_JbeDqSkuc/edit?usp=sharing  Во всех файлах с тестами находятся закомментированные команды для запуска тестов из командной строки (# pytest -v --tb=line test_main_page.py)
