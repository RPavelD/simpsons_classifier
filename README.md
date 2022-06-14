# Распознование персонажей из Симпсонов


Содержимое проекта:

- В "main.ipynb" хранится код обучения 
	> глубокой сверточной нейронной сети с архитектурой densnet201
- В "model" хранится обученная модель
- В "use_model/" хранится код использования модели 
	> с помощью телеграм бота @use_models_bot

## Эффективность модели
- Скороcть обработки 100 запросов занимает около 8 секунд
	> OS: ubuntu 18.04
	> Graphics Processor: NVIDIA GeForce MX230
	> ![alt text](https://github.com/RPavelD/simpsons_classifier/blob/master/info/speed.png)

- Качество распознования на неизвестных данных
	> Результат на соревновании kaggle (https://www.kaggle.com/competitions/journey-springfield)
 	> ![alt text](https://github.com/RPavelD/simpsons_classifier/blob/master/info/result_kaggle.png)


## Особенности:
- Использование библиотеки gTTS для создание голосовых сообщений
- Работа на GPU
