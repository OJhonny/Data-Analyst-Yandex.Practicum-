### <a href="https://github.com/OJhonny/Data-Analyst-Yandex.Practicum-/blob/main/Payback_for_attracting_app_users/%D0%9E%D0%BA%D1%83%D0%BF%D0%B0%D0%B5%D0%BC%D0%BE%D1%81%D1%82%D1%8C%20%D0%BF%D1%80%D0%B8%D0%B2%D0%BB%D0%B5%D1%87%D0%B5%D0%BD%D0%B8%D1%8F%20%D0%BF%D0%BE%D0%BB%D1%8C%D0%B7%D0%BE%D0%B2%D0%B0%D1%82%D0%B5%D0%BB%D0%B5%D0%B9%20%D0%BF%D1%80%D0%B8%D0%BB%D0%BE%D0%B6%D0%B5%D0%BD%D0%B8%D1%8F.ipynb">Окупаемость привлечения пользователей приложения</a>


**Статус проекта:**

проект был выполнен в рамках обучения на программе "Аналитик данных" Я.Практикума.

**Цель:**

выяснить причины низкой окупаемости привлечения пользователей, чтобы повысить эффективность маркетинга приложения Procrastinate Pro.

**Инструменты:**

`pandas, matplotlib.pyplot, seaborn, numpy, datetime`

**Выводы:**

1. В результате проведенного анализа бизнес-показателей был определен сверх затратный по расходам рекламный канал "Tip Top",  привлекающий пользователей в США. С июня расходы на данный канал выросли с 1,5 до 3,5 доллара за пользователя, что больше, чем в 3,5 раза, чем следующий за ним по расходам рекламный канал "FaceBoom". 
2. При этом показатели конверсии и удержания у канала  "Tip Top" на хорошем уровне.
3. Еще два рекламных канала "FaceBoom" и "AdNonSense", имея следующий после "Tip Top" уровень CAC имеют значительно более низкий уровень удержания пользователей, чем остальные каналы.
4. То, что неокупаемость рекламы связана с рекламными каналами в США (прежде всего "Tip Top", но также и "FaceBoom") доказывает окупаемость рекламы во Франции, Германии и Великобритании и позитивный ROI по устройствам в этих же европейских странах в отличие от США.

**Рекомендации**

- выяснить причины значительного повышения расходов на рекламный канал "Tip Top" и нормализовать оные, не отказываясь от самого канала при возможности сократить расходы на него в 3,5 раза;
- отказаться от использования каналов  "FaceBoom" и "AdNonSense"; 
- перераспределить бюджет в пользу рекламных каналов "lambdaMediaAds", "RocketSuperAds" и "WahooNetBanner", которые привлекают наиболее качественных пользователей по средним ценам.

