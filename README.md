# ytb2audiobot-view
ytb2audiobot-view

## 🔐 Защита персональных данных: Рекомендации по обеспечению конфиденциальности

Ваши персональные данные – это ценность, которая заслуживает надежной защиты. Если вы разделяете мои опасения по поводу сохранности личной информации и стремитесь обеспечить максимальную конфиденциальность, следуйте этим рекомендациям:

  - **Оцените свои риски:** Если у вас есть сомнения в безопасности ваших данных, лучше не пользоваться этим ботом.
  - **Установите бота на свой сервер:** Чтобы контролировать все процессы и быть уверенным в безопасности, установите бота самостоятельно на свой сервер.
  - **Открытый код:** Весь код бота публично доступен для просмотра. Можете изучить его, чтобы убедиться в отсутствии эксплойтов, скрытых сохранений данных и любых других возможных утечек ваших персональных данных.

Эти шаги помогут вам защитить свои персональные данные и обеспечить максимальную безопасность при использовании данного бота.


## 🚴‍♂️ Usage and Features

Send any youtube link to movie. Видео станет загружаться сразу автоматически.

В диалоговом окне покажется примерное время загрузки. 

После успешной обрботки и загрузки в телеграм диалоговое окно будет удалено

### 🕰 Timecodes 

Если в описании ролика присутствуют таймкоды - они будут доабвлены в caption скаченного аудифайла

В Телеграме можно удобно прослушивать аудио файл, переходя по ссылкам таймкмодов.

! todo - smooth around 

![photo-1-640](https://github.com/andrewalevin/ytb2audiobot-view/assets/155118488/989f29e7-03d9-46fe-a85d-764b4599d641)




### 🎏 Split param 

Вы всегда можете разделить аудиофайл для более удобного прослушивания.

Как это работает:

  - **По умолчанию:** Все аудиофайлы, длиннее 1 часа 39 минут (как университетская лекция), автоматически разбиваются на части по 39 минут.
  - **Плавный переход:** При разделении к предыдущей части добавляется 5 секунд из следующей, а к началу следующей части - 5 секунд из предыдущей. Это помогает понять, на каком месте вы остановились, и избежать потери информации при разделении.
  - **Магия золотого сечения:** Если последняя часть файла меньше пропорции золотого сечения, она присоединяется к предпоследней части.

**Аудиокниги:** Длинная аудиокнига будет разбита на части, что облегчает загрузку файлов меньшего размера, их передачу и работу с ними.

**Философские тексты:** Например, "Этика" Канта. Слушать такой текст даже по 39 минут сложно, поэтому гораздо удобнее разбивать его на небольшие фрагменты по 20 минут.

Наслаждайтесь удобным прослушиванием!


Параметр 

```
youtu.be/TUJmSgViGoM split 25
```

Алиасами команды для удобства использования и вспоминания добавлены

{split,spl,sp,разделить,раздел,разд,раз}


### 🎶 Настройка битрейта аудиофайлов

По умолчанию, загружаемые аудиофайлы конвертируются в минимальный размер с оптимальным качеством, что обеспечивает битрейт 48k.

Музыкальные файлы могут звучать лучше с более высоким качеством звука.

**Как задать битрейт:**

Вы можете самостоятельно задать выходной битрейт аудиофайла в диапазоне от 48k до 320k. 
Для этого добавьте к отправляемой ссылке через пробел ключевое слово {bit, bitrate} и значение битрейта в тысячных.

**Пример:**

```
youtu.be/TUJmSgViGoM bit 320
```

Алиасами команды для удобства использования и вспоминания добавлены

{bitrate,bitr,bit,битрейт,битр,бит}


<img width="400" alt="img-bitrate-800" src="https://github.com/andrewalevin/ytb2audiobot-view/assets/155118488/b6e98d12-c172-4254-9c12-be341a49c58a">


Для файла из примера получаются следюущие примеры 4 минутный клип:

  - 48k bitrate - 2.1 mb file size (по-умолчанию)
  - 96k bitrate - 3.5 mb file size 
  - 320k bitrate - 9.6 mb file size


### 📝 Subtitles param 

Для скачивания субтитров и поиска по ним воспользуйтесь командой или ее алиасами (для удобства незапомниания :)

{subtitles,subtitle,subt,subs,sub,su,саб,сабы,субтитры,субт,суб,сб}

**Без параметров:** Просто введите команду, и бот скачает субтитры для текущего видео. В субтитрах будут таймкоды и ссылки на соответствующие моменты видео на YouTube.

**С параметрами:** Если после команды ввести слово для поиска, бот выдаст фрагменты субтитров, в которых встречается это слово.


### 📣 In Channels

Алиасами команды для удобства использования и вспоминания добавлены

{download,down,dow,d,bot,скачать,скач,ск}


## 🚀 Install and Launche





































