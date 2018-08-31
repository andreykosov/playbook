2018-08-09

Opengraph: что это такое?
-
Opengraph - это разметка, которая позволяет контролировать данные, когда пользователь делится ссылкой в социальных сетях,
а как известно социальные сети один из крупнейших источников трафика. Проверить используются ли на вашем сайте
opengraph теги вы можете размезтив ссылку на сайт у себя на странице в одной из социальных сетей (должно корректно отобразиться название, картинка, ссылка), или
воспользовавшись сервисом для проверки, например https://opengraphcheck.com.
На наших сайтах эта разметка была добавлена в начале 2018 года.

Описание open graph тегов:

- "og:locale" — локализация (язык сайта), можно использовать значение "ru_RU" по умолчанию.
- "og:type" — указывает тип страницы (статья, новость, видео, категория и т. д.), можно использовать по умолчанию "article".
- "og:title" — указывает заголовок статьи.
- "og:description" — указывает краткое описание, которое выводится при формировании превью ссылки.
- "og:url" — ссылка на страницу сайта.
- "og:image" — ссылка на картинку, которая будет отображаться в посте.
- "og:site_name" — название сайта.

Пример отображения разметки в HTML5:

```
<meta property=“og:title” content=“Пример заголовка статьи”>
<meta property=“og:site_name” content=“название сайта”>
<meta property=“og:type” content=“article”>
<meta property=“og:url” content=“http://example.com/пример-заголовка-статьи”>
<meta property=“og:image” content=“http://example.com/картинка_статьи.jpg”>
<meta property=“og:description” content=“Краткое описание статьи.”>
```

На детальных страницах на наших сайтах в качество изображения используется первое изображение из слайдеа. На общих страницах изображение самого первого элемента.

Массовое использование Open Graph разметки началось в 2017 году, и стало одним из трендов года.