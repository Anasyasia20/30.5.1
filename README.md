# 30.5.1
Домашнее задание к 30 модулю "Поиск элементов с помощью Selenium. Ожидаемый элемент на странице".

Задание 30.3.1 Написать тест, который проверяет, что на странице со списком питомцев пользователя: (все файлы в папке tests)

Присутствуют все питомцы. (test_all_pets_are_present)
Хотя бы у половины питомцев есть фото. (test_pets_have_poto_half)
У всех питомцев есть имя, возраст и порода. (test_all_pets_Have_name_age_breed)
У всех питомцев разные имена. (Test_all_petsPhave_different_names)
В списке нет повторяющихся питомцев. (there_are_no_duplicate_pets_in_the_list).
Задание 30.5.1. В написанном тесте (проверка карточек питомцев) добавьте неявные ожидания всех элементов (фото, имя питомца, его возраст). (test_pet_frends)

В написанном тесте (проверка таблицы питомцев) добавьте явные ожидания элементов страницы. (conftest)

Чеклист для самопроверки:

+В тестах используется настройка implicitly-wait веб-драйвера.

+В тестах используются элементы класса WebDriverWait.
