# 2023 Rosatom hackathon "HackAtom" pipe defects computer vision detection case
In this repository you will see the solution to the case “Production Defect Detector” from the Dog and Fox team.

All the necessary files are presented here, from the code for generating the dataset and training the model, to laptops for training and additional training of the model.

Also here are 3 files with models that our team trained as part of the hackathon:

`Nano_final.pt` - the fastest model

`Medium_final.pt` - the most accurate model

`Small_final.pt` - the best option for a combination of speed and accuracy

The laptops contain all the necessary code, with which the case holder can:
1) create the dataset necessary for training the model
2) train or retrain the model
3) implement it into the production process

## Telegram bot
In this file you can find an example of integrating a model into a telegram bot based on the code from the file `Model_usage.ipynb`
Also, based on the code from this file, you can integrate the model into any system

The `confusion_matrix` files contain confusion matrices, on the basis of which one can indirectly judge the quality of the models
But we invite you to personally verify the quality of work of our models in the Telegram bot

P.S.
The file `Medium_final.pt` is not uploaded to the repository due to size restrictions, so here is a link to it https://drive.google.com/file/d/1_kz32RR8Ks0xdxRGXvDQHfVoU4ke-HYq/view?usp=sharing

# Хакатон Росатома "ХакАТОМ" 2023, решение кейса "Детектор производственных дефектов"
В данном репозитории вы увидите решеине кейса "Детектор производственных дефектов" от команды Пёс да лис.

Здесь представлены все необходимые файлы, начиная от кода для формирования датасета и обучения модели, заканчивая ноутбуками для обучения и дообучения модели.

Также здесь представлены 3 файла с моделями, которые наша команда натренировала в рамках хакатона:

`Nano_final.pt` - самая быстродейственная модель

`Medium_final.pt` - самая точная модель

`Small_final.pt` - оптимальный вариант по сочетанию быстродействия и точности

В ноутбуках присутвует весь необходимый код, при помощи которого кейсодерждатель сможет:
1) сформировать необходимый для обучения модели датасет
2) обучить, либо дообучить модель
3) внедрить её в производственный процесс

## Telegram bot
В данном файле вы можете найти пример интеграции модели в телеграм бота на основе кода из файла `Model_usage.ipynb`
Также на основе кода из данного файла можно интегрировать модель в любую систему

В файлах `confusion_matrix` находятся матрицы неточностей, на основе которых можно косвенно судить о качестве работы моделей
Но мы предлагаем Вам лично убедиться в качестве работы наших моделей в Телеграм боте

P.S.
Файл `Medium_final.pt` не загружается на репозиторий из-за ограничений по размеру, поэтому вот ссылка на него https://drive.google.com/file/d/1_kz32RR8Ks0xdxRGXvDQHfVoU4ke-HYq/view?usp=sharing
