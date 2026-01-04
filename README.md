# Домашнее задание к занятию «GitLab»

# Задание 1
## Что нужно сделать:

1. Разверните GitLab локально, используя Vagrantfile и инструкцию, описанные в этом репозитории.
2. Создайте новый проект и пустой репозиторий в нём.
3. Зарегистрируйте gitlab-runner для этого проекта и запустите его в режиме Docker. Раннер можно регистрировать и запускать на той же виртуальной машине, на которой запущен GitLab.

В качестве ответа в репозиторий шаблона с решением добавьте скриншоты с настройками раннера в проекте.

# ОТВЕТ НА ЗАДАНИЕ 1

### Рисунок №1. Логотип локально установленного GitLab.
![logo gitlab](https://github.com/Yuriykup/hw_803/blob/main/screenshoots/1-1-1_GitLab-logo.png)

### Рисунок №2. Новый проект.
![new project](https://github.com/Yuriykup/hw_803/blob/main/screenshoots/1-2-1_New-project.png)

### Рисунок №3. Запущенный на ВМ Ubuntu-bionic Runner.
![docker runner](https://github.com/Yuriykup/hw_803/blob/main/screenshoots/1-3-1_docker-runner.png)

### Рисунок №4. Зарегистрированный Runner в проекте Ntlg803 на Gitlab.
![runner registry](https://github.com/Yuriykup/hw_803/blob/main/screenshoots/1-3-2_Runner-registry.png)


# Задание 2
## Что нужно сделать:

1. Запушьте репозиторий на GitLab, изменив origin. Это изучалось на занятии по Git.
2. Создайте .gitlab-ci.yml, описав в нём все необходимые, на ваш взгляд, этапы.

В качестве ответа в шаблон с решением добавьте:

- файл gitlab-ci.yml для своего проекта или вставьте код в соответствующее поле в шаблоне;
- скриншоты с успешно собранными сборками.

# ОТВЕТ НА ЗАДАНИЕ 2

### Рисунок №5. "Запушенный" репозиторий на GitLab.
![push repos gilab](https://github.com/Yuriykup/hw_803/blob/main/screenshoots/2-1-1_Copy-Reposy.png)

### Рисунок №6. Добавленный файл .gitlab-ci.yml в проекте Ntlg803 на Gitlab.
![yaml file](https://github.com/Yuriykup/hw_803/blob/main/screenshoots/2-2-1_Yaml-file.png)

### Рисунок №7. Код .gitlab-ci.yml.
![code yaml](https://github.com/Yuriykup/hw_803/blob/main/screenshoots/2-2-2_Ci-file.png)

### Рисунок №8. Отработаные задачи (jobs) в GitLab.
![true jobs](https://github.com/Yuriykup/hw_803/blob/main/screenshoots/2-2-3_true_jobs.png)

