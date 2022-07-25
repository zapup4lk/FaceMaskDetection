<h1 align="center">Face Mask Detection</h1>

<h1 align= "center"><img src="https://user-images.githubusercontent.com/81526639/158228829-e0f3d24e-23ec-47cf-99e6-1a0f2709ec93.png" width="200" height="200"/>
  <h4 align= "center">Система обнаружения масок на лицах, построенная с помощью OpenCV, Keras/TensorFlow с использованием концепций глубокого обучения и компьютерного зрения для обнаружения масок на лицах на видео в реальном времени..</h4>
  
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;
![Live Demo](https://github.com/zapup4lk/FaceMaskDetection/blob/main/Examples/720%20(1).gif)

## Мотив
В связи со всемирной пандемией COVID-19 все население планеты было вынуждено носить средства индивидуальной защиты (медицинские маски, резиновые перчатки и т.д.), чтобы защитить себя и окружающих. Но, к сожалению, многие люди пренебрегают этими правилами.
  
<p align="center"><img src="https://github.com/zapup4lk/FaceMaskDetection/blob/main/Examples/Ex%20No.%203.png">
  
### :warning: Использованные библиотеки

- [TensorFlow](https://www.tensorflow.org/)
- [keras](https://keras.io/)
- [imutils](https://pypi.org/project/imutils/)
- [NumPy](https://numpy.org/)
- [OpenCV](https://opencv.org/)
- [Matplotlib](https://matplotlib.org/)
- [SciPy](https://scipy.org/)
  
### :star: Особенности
  
Наш детектор масок на лицах не использует какой-либо набор данных морфированных изображений с масками, и модель является относительно точной. 

Данная система может использоваться в приложениях реального времени, где требуется обнаружение лиц в масках в целях безопасности в связи со вспышкой COVID-19. Данный проект может быть интегрирован со встроенными системами для применения в аэропортах, на вокзалах, в офисах, школах и общественных местах для обеспечения соблюдения правил общественной безопасности.


### :file_folder: Набор данных
  
Набор данных можно скачать здесь - [Нажмите, чтобы скачать](https://www.kaggle.com/vijaykumar1799/face-mask-detection)
  
Набор данных содержит 6886 изображений, разбитых на два класса:
*	__with_mask: 5886 изображений__
*	__without_mask: 1000 изображений__
  
Изображения были собраны с [Kaggle](https://www.kaggle.com/)
  
### :key: Предустановки

Все необходимые библиотеки были собраны в файле <code>requirements.txt</code> [Смотреть здесь](https://github.com/zapup4lk/FaceMaskDetection/blob/main/requirements.txt)
 
### Установка

1. Копируйте репозиторий:
```
$ git clone https://github.com/zapup4lk/FaceMaskDetection.git
```
  
2. Смените текущую директорию на скопированный репозиторий:
```
$ cd FaceMaskDetection
```

3. Создайте виртуальное окружение Python и активируйте его:
```
$ virtualenv test
```
```
$ source test/bin/activate
```
  
4. Теперь, запустите следующую команду в терминале для установки библиотек:
```
$ pip3 install -r requirements.txt
```


### :bulb: Работа
  
1. Откройте терминал. Перейдите в директорию скопированного проекта и напишите следующую команду: 
```
$ python3 train_mask_detector.py --dataset dataset
```
  
2. Для детекции маски в реальном времени введите следующую команду:
```
$ python3 detect_mask_video.py
```
  
### :key: Результат
  
### Мы получили следующий график кривой обучения точность/потери
<p align ="center"><img src="https://github.com/zapup4lk/FaceMaskDetection/blob/main/plot.png">
