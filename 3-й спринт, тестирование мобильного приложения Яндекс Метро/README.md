# 3-й спринт, тестирование мобильного приложения: Яндекс Метро

## Описание проекта
Этот проект посвящен тестированию мобильного приложения «Яндекс Метро» на Android после рефакторинга. Основная цель — протестировать измененную функциональность, выполнить регрессионное тестирование и подготовить отчет для менеджера о готовности приложения к публикации.

### Основные задачи
- Провести тест-анализ требований, затронутых рефакторингом, и создать чек-лист для функционального тестирования.
- Подготовить регрессионный чек-лист, включающий тесты, связанные с функциональностью мобильного устройства, и обязательные проверки для мобильных приложений.
- Выполнить тестирование приложения, завести баг-репорты и классифицировать их по приоритетам.
- Подготовить отчет о тестировании для менеджера, включающий результаты тестов, найденные баги и рекомендации.

## Артефакты проекта

### Документация тестирования
- [Чек-лист функционального и регрессионного тестирования](https://docs.google.com/spreadsheets/d/1zpjzGJOg4_5Ps90ouBt9k1ygJsfwFz9MvLFM2DIEsGk/edit?usp=sharing) — проверка измененной функциональности, проверка взаимодействия с устройством и общие проверки для мобильных приложений.
- [Майндмэп анализа требований в Miro](https://miro.com/app/board/uXjVK5URgfA=/) — визуализация ключевых требований и их связей.
- [Отчет о тестировании](https://docs.google.com/document/d/1s36XX0WzhGuxRfltx7HY-dxnZW8yrfCR9q18SaGT0jQ/edit?usp=sharing) — итоговый отчет с результатами тестов и рекомендациями.

### Баг-репорты
- Все баги были задокументированы в [YouTrack](https://gospodarsky.youtrack.cloud/dashboard?id=529-2) и включены в таблицу результатов тестирования.

## Скриншоты
- **Основное окно приложения Яндекс Метро**

  <img src="images/YMetro_main.png" alt="Основное окно приложения" width="300" height="auto">
- **Экран выбора маршрута**  

  <img src="images/YMetro_route.png" alt="Экран выбора маршрута" width="200" height="auto">

## Инструменты и технологии
![Bug Reporting](https://img.shields.io/badge/-Bug%20Reporting-red?style=for-the-badge&logo=bug&logoColor=white)
![YouTrack](https://img.shields.io/badge/-YouTrack-0062CC?style=for-the-badge&logo=jetbrains&logoColor=white)
![Google Sheets](https://img.shields.io/badge/-Google%20Sheets-34A853?style=for-the-badge&logo=googlesheets&logoColor=white)
![Emulation](https://img.shields.io/badge/-Emulation-grey?style=for-the-badge&logo=android&logoColor=white)
![Android Studio](https://img.shields.io/badge/-Android%20Studio-3DDC84?style=for-the-badge&logo=androidstudio&logoColor=white)
![UI/UX Testing](https://img.shields.io/badge/-UI/UX%20Testing-purple?style=for-the-badge&logo=figma&logoColor=white)
![Figma](https://img.shields.io/badge/figma-%23F24E1E.svg?style=for-the-badge&logo=figma&logoColor=white)
![Responsive Testing](https://img.shields.io/badge/-Responsive%20Testing-lightblue?style=for-the-badge&logo=responsive&logoColor=white)
![Test Design Techniques](https://img.shields.io/badge/-Test%20Design%20Techniques-ffb900?style=for-the-badge&logo=knowledgebase&logoColor=white)
![Mindmapping](https://img.shields.io/badge/-Mindmapping-yellowgreen?style=for-the-badge&logo=brain&logoColor=white)
![Miro](https://img.shields.io/badge/-Miro-FFD02F?style=for-the-badge&logo=miro&logoColor=black)

## Тестовое окружение
Тестирование проводилось на следующей конфигурации:
- **Устройство**: эмулятор Honor 8
- **Операционная система**: Android 9.0 Pie
- **Разрешение экрана**: 1080x1920, диагональ 5.5

Номер тестируемой версии приложения: v3.6.


## Выводы и достижения
Все требования, затронутые изменениями, были покрыты чек-листом. Из 111 проверок успешно прошло 92 теста, 19 тестов не прошло и 1 пропущен. С учётом того, что блокирующих багов не найдено, а критические дефекты не расположены в основных пользовательских сценариях, команда тестирования не против публикации новой версии приложения в Google Play.

- на анализ, декомпозицию требований и написание тестовой документации ушло 4 дня 
- на тестирование ушло так же 4 дня
- Все баги не помешают пользователю ориентироваться в метро с помощью мобильного устройства. Основные функции - схема метро, построение маршрута и оценка времени в пути работают
- В процессе тестирования приложения удалось применить регрессионное и функциональное виды тестирования
- при тестировании Яндекс Метро после исправления багов стоит обратить внимание на проверки из списков задач с критическим и средним приоритетом т.к. эти ошибки значительно снижают комфорт пользования приложением, что может привести к репутационным потерям
- по результатам тестирования Яндекс Метро считаю что новую версию приложения можно публиковать в Google Play



