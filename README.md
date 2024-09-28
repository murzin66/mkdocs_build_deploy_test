# mkdocs_build_deploy_test
На занятиии 27.09.2024 был протестирован деплой тестового сайта на github pages и применение стилей github pages к оформлению сайт, а также протестирован деплой тестового сайта, собранного автоматически средствами mkdir.

На первом этапе был создан github репозиторий и склонирован на локальный компьютер. 
![Создание репозитория]([http://url/to/img.png](https://drive.google.com/file/d/1TvR7cyHJ1aGl4LS261QtFaX5uCd6AhQ9/view?usp=drive_link))

В репозитории была создана директория docs и в ней создан Readme.md файл. 
![Readme.md файл]([http://url/to/img.png](https://drive.google.com/file/d/1OCrS_81D-HYyax_ikHn9Y7zQglEEOR1L/view?usp=drive_link))

Для наполнения сайта был использован открытый репозиторий https://github.com/cbracco/html5-test-page/blob/master/index.html . Содержимое репозитория было использовано для наполнения Readme.md файла.

Для применения стиля cayman был создан файл _config.yml в директории docs 
![Readme.md файл]([http://url/to/img.png](https://drive.google.com/file/d/1vJgK6-YRBfusaphajkpcSwfsaTuPYrrF/view?usp=drive_link))

Измененные файлы были добавлены в комит, изменения добавлены в удаленный github репозиторий. Для деплоя репозитория в github pages в настройках был выбран раздел pages, выбраны ветка и директория.
![Readme.md файл]([http://url/to/img.png](https://drive.google.com/file/d/1RdH-HnNNrTxbRLPgKh0x_TzqlGt8Q___/view?usp=drive_link)) 

После внесения изменений через некоторое время происходит успешный деплой и появляется URL готовой веб страницы
![Readme.md файл]([http://url/to/img.png](https://drive.google.com/file/d/1_rvekr76iIYCR2hfJVFzBcZ6DI_aC28B/view?usp=drive_link))

Полученная веб-страница с учетом применения стиля выглядит следующим образом:
![Readme.md файл]([http://url/to/img.png](https://drive.google.com/file/d/1Dft7PDaTzaVquB5y3wnpc6AOM0c6UGYT/view?usp=drive_link))
Ссылка на сайт: https://murzin66.github.io/Python_study/

Также во время занятия была протестирована автоматическая сборка сайта с помощью mkdocs. С помощью команды mkdocs build была построена документация mkdocs. После этого в текущем расположении была создана директория site cо следующим содержимым:
![Readme.md файл]([http://url/to/img.png](https://drive.google.com/file/d/1dO08mTQBrwvVOoEvdAyRePHzjzJ5SpGd/view?usp=drive_link))

После этого вручную произведен деплой содержимого папки site на github pages. Результат выглядит следующим образом:
![Readme.md файл]([http://url/to/img.png](https://drive.google.com/file/d/1aaUNiEmEBJs9bQc1QlaHoKjrbtFnPsgs/view?usp=drive_link))

Ссылка на сайт: https://murzin66.github.io/mkdocs-test/



 
