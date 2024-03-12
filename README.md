# number_and_categorical_features_analysis_titanic_example
Анализ по одной из вариаций датасета titanic с числовыми и категориальными признаками

Смотрим пропуски данных



![image](https://github.com/PaslenAmari/number_and_categorical_features_analysis_titanic_example/assets/106679149/74b00cf2-a805-47fd-aca5-9891c460b34c)


Анализ по пропущенным значениям



![image](https://github.com/PaslenAmari/number_and_categorical_features_analysis_titanic_example/assets/106679149/c9699b29-f7b5-4d53-ac6c-f061c3f5cad9)


Заменили пропущенные значения средними (mean) по числовым признакам


![image](https://github.com/PaslenAmari/number_and_categorical_features_analysis_titanic_example/assets/106679149/7fac18a5-1fd5-4ab1-87e7-e35cd32ccd33)


Заменили пропущенные значения по категориальным признакам


![image](https://github.com/PaslenAmari/number_and_categorical_features_analysis_titanic_example/assets/106679149/16167426-2567-4a77-b5fe-9ecfc36b78e4)


Проверили количество пропущенных значений по всему датасету


![image](https://github.com/PaslenAmari/number_and_categorical_features_analysis_titanic_example/assets/106679149/afc5562d-364b-4b3c-8745-bdf73dd4e921)


Посмотрели аналитику по уникальным значениям признаков датасета


![image](https://github.com/PaslenAmari/number_and_categorical_features_analysis_titanic_example/assets/106679149/7f78a648-4c5d-4283-b365-134394f4b65b)

С помощью аналитики определили влияние всех признаков на признак Survived (выживание)


![image](https://github.com/PaslenAmari/number_and_categorical_features_analysis_titanic_example/assets/106679149/e6965d61-aef3-436b-94e4-25656d191ba0)

корреляция по Пирсону


![image](https://github.com/PaslenAmari/number_and_categorical_features_analysis_titanic_example/assets/106679149/8796794d-09b3-4bd1-8100-57c9e9c4e1e3)


Посмотрели признаки с группировкой


![image](https://github.com/PaslenAmari/number_and_categorical_features_analysis_titanic_example/assets/106679149/f99fa0e6-42db-431d-9f72-45e0f3c6c45c)
![image](https://github.com/PaslenAmari/number_and_categorical_features_analysis_titanic_example/assets/106679149/b5732fbb-a15c-44c3-af89-9e1965b0a96e)
![image](https://github.com/PaslenAmari/number_and_categorical_features_analysis_titanic_example/assets/106679149/567043ee-5403-4545-bc25-1713eda27386)
![image](https://github.com/PaslenAmari/number_and_categorical_features_analysis_titanic_example/assets/106679149/dbdfa53e-d85a-478d-a1df-4720f4e539f5)

Выводы:


На основе построенных графиков:



*   по числовым принакам мы видим, что есть корреляция между признаком PClass и выживаемостью (Survived) - выживаемость выше у пассажиров 1-го класса, тогда как у 3-го класса самая низкая выживаемость, а также Fare и выживаемостью - чем стоимость проезда выше, тем выживаемость выше (так как скорее пассажиры первого класса платили больше).
*   по категориальным признакам моно выделить зависимость между признаком Sex и выживаемостью - выживаемость выше у женщин (female) ввиду очередности эвакуации и ограниченного количества мест, Embarked и выживаемостью - на данном этапе однозначно выделить причину большей выживаемости пассажиров из Cherbourg не представляется возможным (Cherbourg - первая остановка после начала маршрута Титаника,  в то время как Southampton - начало маршрута, Queenstown - последняя точка посадки пассажиров).




