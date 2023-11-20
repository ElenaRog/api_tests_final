# Проект по тестированию API сервисов [reqres.in](https://reqres.in) и [catfact.ninja](https://catfact.ninja)

## Список проверок
 - Проверяются ответы на GET,POST, PUT, DELETE-запросы;
 - Проверяются схемы полученных ответов.

## Технoлoгии и инструмeнты
<p align="center">
<a href="https://www.python.org/"><img src="design/icons/python.svg" width="50" height="50"  alt="Python" title="Python"/></a>
<a href="https://docs.pytest.org/"><img src="design/icons/pytest.svg" width="50" height="50"  alt="PyTest" title="PyTest"/></a>
<a href="https://www.selenium.dev//"><img src="design/icons/selenium.svg" width="50" height="50"  alt="Selenium" title="Selenium"/></a>
<a href="https://www.jenkins.io/"><img src="design/icons/jenkins.svg" width="50" height="50"  alt="Jenkins" title="Jenkins"/></a>
<a href="https://qameta.io/allure-report/"><img src="design/icons/allure.png" width="50" height="50"  alt="allure-report" title="allure-report"/></a>
<a href="https://qameta.io/allure-report/"><img src="design/icons/allure_testops.png" width="50" height="50"  alt="allure-report" title="allure-report"/></a>
<a href="https://github.com/"><img src="design/icons/github.png" width="50" height="50"  alt="Github" title="Github"/></a>
<a href="https://web.telegram.org/"><img src="design/icons/telegram.png" width="50" height="50"  alt="Telegram" title="Telegram"></a>
</p>

## Запуск автотестов в Jenkins
#### 1. Открыть <a target="_blank" href="https://jenkins.autotests.cloud/job/C07-elena_ching-python_API_tests_final/">проект</a>
#### 2. Нажать **Build Now**
![This is an image](design/jenkins_build.png)
#### 3. Результат запуска сборки можно посмотреть в отчёте Allure
![This is an image](design/allure_results.png)


# Интеграция с Allure TestOps и Telegram
### Результаты прохождения тестов, а также сами тест-кейсы будут отправлены в Allure TestOps
![This is an image](design/testopts.png)
### Настроено автоматическое оповещение о результатах сборки Jenkins в Telegram
![This is an image](design/telegram.png)
