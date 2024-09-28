# mkdocs_build_deploy_test
На занятиии 27.09.2024 был протестирован деплой тестового сайта на github pages и применение стилей github pages к оформлению сайт, а также протестирован деплой тестового сайта, собранного автоматически средствами mkdir.

На первом этапе был создан github репозиторий и склонирован на локальный компьютер. 
![make_directory](https://github.com/user-attachments/assets/2825c08d-af6b-4508-9f60-21f62a3831a7)

В репозитории была создана директория docs и в ней создан Readme.md файл. 
![file_readme_md](https://github.com/user-attachments/assets/ca9d353e-a1a9-4db4-9646-7d6f1884ec56)

Для наполнения сайта был использован открытый репозиторий https://github.com/cbracco/html5-test-page/blob/master/index.html . Содержимое репозитория было использовано для наполнения Readme.md файла.

Для применения стиля cayman был создан файл _config.yml в директории docs 
![yml_file](https://github.com/user-attachments/assets/8c5f9288-9057-478a-a769-88d2e3773132)

Измененные файлы были добавлены в комит, изменения добавлены в удаленный github репозиторий. Для деплоя репозитория в github pages в настройках был выбран раздел pages, выбраны ветка и директория.
![pages](https://github.com/user-attachments/assets/11fe431e-ae6c-457a-97a7-a4bc552e1cf4)

После внесения изменений через некоторое время происходит успешный деплой и появляется URL готовой веб страницы
![Pages2](https://github.com/user-attachments/assets/a465c650-eb45-463b-9ad5-7ea6108fbf2e)

Полученная веб-страница с учетом применения стиля выглядит следующим образом:
![Pages3](https://github.com/user-attachments/assets/2de9e035-4994-4b93-8155-a92bb603dcb9)

Ссылка на сайт: https://murzin66.github.io/Python_study/

Также во время занятия была протестирована автоматическая сборка сайта с помощью mkdocs. С помощью команды mkdocs build была построена документация mkdocs. После этого в текущем расположении была создана директория site cо следующим содержимым:
![site](https://github.com/user-attachments/assets/5be1c8c2-a81b-4fa1-aeb0-6cee40951386)

После этого вручную произведен деплой содержимого папки site на github pages. Результат выглядит следующим образом:
![mkdocs_documentation](https://github.com/user-attachments/assets/3ff2cdc9-79dc-4b8a-87c8-fd87a88558ba)

Ссылка на сайт: https://murzin66.github.io/mkdocs-test/

<b>Создание и развертывание статического сайта</b>
Создаем и клонируем локально репозиторий github
![git_clone](https://github.com/user-attachments/assets/b1b104e0-e051-47f5-b70f-475780aaacd7)
Создаем и активируем виртуальное окружение
![env](https://github.com/user-attachments/assets/350e7ee0-bb33-4fe1-bae0-c9f0b17f13da)

Создаем новый проект с документацией mkdocs, запустим локальный сервер для просмотра содержимого, поменяем заголовок сайта, наблюдаем изменение статического сайта 
![new_mkdocs](https://github.com/user-attachments/assets/b6bd7b28-4b98-4e07-8881-57c3cb616bf5)
![mkdocs_site](https://github.com/user-attachments/assets/0c8626f3-9ba6-46e1-a30e-05f630a65606)
Убеждились в том, что страница запущена, осуществляем деплой командой mkdocs gh-deploy
![deploy1](https://github.com/user-attachments/assets/1ce999c3-3038-4520-bf4e-42add203f7e0)
Наблюдаем появление новой ветки в репозитории github, убеждаемся в том, что в данной ветке присутствуют необходимые файлы
![new-branch](https://github.com/user-attachments/assets/7e9c840c-7421-4f98-a914-2e14402beabb)
![new_branch_contain](https://github.com/user-attachments/assets/4310c734-434c-4e49-99a4-adadaa5ac414)

Выбираем данную ветку для развертывания на github pages
![deploy2](https://github.com/user-attachments/assets/6f66eb26-3178-4e1a-9f08-c8615ca466e0)
Появляется сообщение об успешном деплое 
![deploy3](https://github.com/user-attachments/assets/def255af-064f-488f-af18-edb5ad186da1)
Проверяем работоспособность сайта, внешний вид сайта
![deploy4](https://github.com/user-attachments/assets/cb0fcd7e-6b6b-4eaf-b2fb-cf01c9c91b8e)
Адрес сайта: https://murzin66.github.io/mkdocs_build_deploy_test/









 
