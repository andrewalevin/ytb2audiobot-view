# ytb2audiobot-view
ytb2audiobot-view

## 🔐 Privacy

Ваши персональные данные – это ценность, которая заслуживает надежной защиты. Если вы разделяете мои опасения по поводу сохранности личной информации и стремитесь обеспечить максимальную конфиденциальность, следуйте этим рекомендациям:

Если у вас есть сомнения в безопасности ваших данных, лучше не пользоваться этим ботом :)

Чтобы контролировать все процессы и быть уверенным в безопасности, установите бота самостоятельно на свой сервер.
  
Проверьте код бота: Тщательно изучите код, чтобы убедиться в отсутствии эксплойтов, скрытых сохранений данных и любых других возможных утечек информации.

Эти шаги помогут вам защитить свои персональные данные и обеспечить максимальную безопасность при использовании данного бота.


## 🚴‍♂️ Usage and Features

Send any youtube link to movie. Видео станет загружаться сразу автоматически.

В диалоговом окне покажется примерное время загрузки. 

После успешной обрботки и загрузки в телеграм диалоговое окно будет удалено

### 📣 Timecodes 

Если в описании ролика присутствуют таймкоды - они будут доабвлены в caption скаченного аудифайла

В Телеграме можно удобно прослушивать аудио файл, переходя по ссылкам таймкмодов.

! todo - smooth around 

![photo-1-640](https://github.com/andrewalevin/ytb2audiobot-view/assets/155118488/989f29e7-03d9-46fe-a85d-764b4599d641)




### 🎏 Split param 

split

Вы всегда можете разделить аудифоайл для удобства прослушивания.

По-умолчанию все аудио файлы длиннее 1 часа 39 минут (университетская лекция) разбиваются на части по 39 минут.

Последняя часть порисоединяется к предпоследней, если ее отношение меньше золотого сечения. Такая Магия.

При разделении файла на части к прошлой чатси добавляется 5 секунд следующего, а в следюущий вначале добавляется 5 секунд из предудыщего, 
чтобы было поянтно, в каком месте вы остановились, а также избежать поетри информации при произивольном разделении.

Как этим пользоваться.

Например, длинная аудиокнига будет разбита на части. 
Это облегчит загразку файла мальенького размера, его передачу и работу с ним.

А вот в случае философских текстов, например, этика Канта.
Ее очень сложно слушать даже по 39 минут.
Гораздо удобнее будет уметь небольшие фрагменты по 20 минут.

Параметр 

```
youtu.be/TUJmSgViGoM split 25
```



### 🎶 Bitrate param 

subtitles

По-умолчанию загружаемые аудио файлы коныертируются в минимальным размер с оптимальным качеством, так что 
получается битрейт 48k. 

Музыкальные файлы могут звучать интресеннее с болле высоким качетсвом звука.

Поэтому вы сами можете задать выходной битрейт аудио файла в диапощоне 48k - 320k

Для этого добавиьте к отправляемой ссылке через пробел ключевое слово {bit, bitrate} и значение указанное в тысячных

Пример для битерейта в 320к

```
youtu.be/TUJmSgViGoM bit 320
```

<img width="400" alt="img-bitrate-800" src="https://github.com/andrewalevin/ytb2audiobot-view/assets/155118488/b6e98d12-c172-4254-9c12-be341a49c58a">


Для файла из примера получаются следюущие примеры 4 минутный клип:

  - 48k bitrate - 2.1 mb file size (по-умолчанию)
  - 96k bitrate - 3.5 mb file size 
  - 320k bitrate - 9.6 mb file size


### 📝 Subtitles param 

subtitles



### In Channels

## Usage Hints


## 🚀 Install and Launche





































