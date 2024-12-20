# 4-й спринт, тестирование API

## Описание проекта  
В этом спринте тестировалась новая функциональность API Яндекс.Прилавка. Задача на проектирование тестов для проверки работы API и выполнение тестирования.  

---

## Основные задачи  
- Изучение новой функциональности API, включая документацию и требования.  
- Проектирование чек-листа для тестирования следующих операций:  
  - Работа с наборами: добавление продуктов в набор.  
  - Работа с курьерами: расчет доставки через службу "Привезём быстро".  
  - Работа с корзиной: добавление, удаление и просмотр содержимого.  
- Выполнение тестирования API через Postman.  
- Регистрация обнаруженных дефектов в YouTrack.  
- Подготовка отчета о результатах тестирования.  

---

## Артефакты проекта  

### 📋 [Чек-лист в Google Sheets](https://docs.google.com/spreadsheets/d/1vQMt8TcdpMyOeO9upue-dzbEsA5bQ6nJYGR83_f6woQ/edit?usp=sharing)  
  Чек-лист содержит тестовые сценарии для проверки работы всех ручек API, переданных на тестирование.  

### 🛠️ Тестирование API в Postman  
- Проверены ручки:  
  - `POST /api/v1/kits/{id}/products`  
  - `POST /fast-delivery/v3.1.1/calculate-delivery.xml`  
  - `GET /api/v1/orders/:id`  
  - `PUT /api/v1/orders/:id`  
  - `DELETE /api/v1/orders/:id`
 
<img src="images/API_collection_4sprint.png" alt="Экран выбора маршрута" width="800" height="auto">  

### 🐞 [Баг-репорты в YouTrack](https://gospodarsky.youtrack.cloud/dashboard?id=529-4)

---

## Инструменты и технологии  
![API Testing](https://img.shields.io/badge/-API%20Testing-orange?style=for-the-badge&logo=api&logoColor=white)
![Postman](https://img.shields.io/badge/-Postman-f76935?style=for-the-badge&logo=postman&logoColor=white)  
![Bug Reporting](https://img.shields.io/badge/-Bug%20Reporting-red?style=for-the-badge&logo=bug&logoColor=white)
![YouTrack](https://img.shields.io/badge/-YouTrack-0062CC?style=for-the-badge&logo=jetbrains&logoColor=white)
![Google Sheets](https://img.shields.io/badge/-Google%20Sheets-34A853?style=for-the-badge&logo=googlesheets&logoColor=white)  
![Apidoc](https://img.shields.io/badge/-Apidoc-005C99?style=for-the-badge&logo=readthedocs&logoColor=white)

---

## Выводы и достижения  
- Спроектированы и выполнены тесты, покрывающие всю новую функциональность API.  
- Обнаружены и зарегистрированы баги с указанием шагов воспроизведения, ожидаемого и фактического результатов.  
- Сделан вывод о стабильности протестированной функциональности.




