# ИНФРАСТРУКТУРА

На push запускается workflow release.yml - с тестами, коммитлинтом и проверкой тега версии. Если тесты прошли и есть тег - через Issue выкладывается Release, который автоматом закрывается

На pull request запускается workflow pullRequest.yml - с тестами и коммитлинтом. Если проверки не проходят - PR автоматически отклоняется.