# 28.1.-PJ-04-
Для запуска тестов:

установить все библиотеки и зависимости: pip install -r requirements.txt.
убедитесь что у вас присутствуют основные браузеры для тестирования - в файле conftest.py у фикстуры initialize_driver можете изменить браузер.
запустить тесты: pytest tests/test_auth.py.
запустить тест: pytest tests/test_auth.py::TestAuth::название_нужного_теста.
