Небольшая часть магистерской работы, где было исследовано влияние методов инициализации на качество сегментации архитектуры U-Net. 
Помимо классических инициализаций по Каймингу и Хавьеру было исследовано самоконтролируемое (SSL обучение) 
Для инициализации SSL обучением обучалась SSL сеть на предзадаче восстановления изображения, а затем инициализировались в энкодере целевой сети.
 

![image](https://github.com/user-attachments/assets/fc39a101-9057-41f5-91db-20b1909926dd)

График средних потерь на десяти эпохах: а) инициализация весами самоконтролируемого обучения на сгенерированных данных; б) инициализация весами самоконтролируемого обучения на данных близких к целевым; в) инициализация весами самоконтролируемого обучения на повернутых на 180 градусов обучающих данных; г) инициализация по Каймингу; д) инициализация по Хавьеру
