**[Исходник от LoftSchool мною доработанный (Автопрефикс и source-map и тд)](https://loftblog.ru/material/1-vvedenie-v-webpack-2/)**

# `GMPJS` 
***
## GMP - Good Manufacturing Practice
## GMP - Надлежащая производственная практика (из фармпроизводства)
***
## `Что такое GMPJS:`
### 1. Средство для разработки (нужно будет удалить лишние страницы из ..\source\pages и в webpack.config.js аналогичные страницы из "entry" и из "plugins")
### 2. Наглядное пособие - РАБОЧИЕ примеры в папках:
### 2.1. ..\helper\use. В консоле вводи (например) - node statusUse.js
### 2.2. ..\source\components - смотри исходники
***
# `Как установить проект:`
##  ![#03CA27](https://placehold.it/20/c5f015/000000?text='') `git clone https://github.com/vlad-74/webpack_2_pug_scss_mini.git jmpjs`
##  ![#03CA27](https://placehold.it/20/c5f015/000000?text='') `Перейти в проект - cd jmpjs`
##  ![#03CA27](https://placehold.it/20/c5f015/000000?text='') `yarn install`
##  ![#03CA27](https://placehold.it/20/c5f015/000000?text='') `yarn run start`
***
# `Функциоанал разделен на:`
## 1. Разработка - yarn run start (npm run start) - http://localhost:9000/
## 2. Сборка и тестирование:
### 2.1. Сборка (для последующего тестирования) - yarn run build (npm run build)
### 2.2. Тестирование - yarn run serv (npm run serv) - http://127.0.0.1:8080
***
# `В сборке присутствует следующий функционал:`
## 1. Инструент для сборки JS проекта - сам проект
## 2. HTML шаблонизатор (pug) - в Разработке и в Сборке и тестирование
## 3. Работа с картинками - в Разработке и в Сборке и тестирование
## 4. Прогон через автопрефексеры - в Разработке и в Сборке и тестирование
## 5. Минимизация JS & CSS фйлов - в Сборка и тестирование
## 6. DevServer - в Разработке (для моментального обновления при изменение в коде)
## 7. source-map - в Разработке (для дебага)
## 8. Компиляция scss файлов - в Разработке
***
# `Примеры:`
## 1. Реализация меню
***
# P.S. Webpack не должен быть установлен глобально. Из-за этого у меня сыпались ошибки