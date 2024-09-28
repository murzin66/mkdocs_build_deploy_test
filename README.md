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



 
