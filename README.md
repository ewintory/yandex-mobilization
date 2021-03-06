# Yandex Mobilization 2016

Данное приложение является тестовым заданием для Школы мобильной разработки проводимой Яндексом в 2016 году.

## Требования

> Напишите приложение для платформы Android на языке Java. Чтобы вам было легче, мы подготовили примерный вид экранов тестового приложения и набор данных.
>
> Минимальная функциональность:
> * На первом экране нужно показать список имен исполнителей популярной музыки.
> * На следующем экране — подробную информацию о выбранном исполнителе.
> * Исходные данные приложение получает по сети в формате JSON. JSON доступен по ссылке: [download.cdn.yandex.net/mobilization-2016/artists.json](http://download.cdn.yandex.net/mobilization-2016/artists.json)
>
> Наш ведущий разработчик, который будет проверять выполненные задания, очень радуется, когда встречает:
>
> * комментарии в коде;
> * обработку ошибок;
> * анимацию;
> * кеширование (например, можно научить приложение сохранять предыдущий ответ сервера);
> * тесты.
>
> Результат пришлите в виде двух ссылок — на GitHub-репозиторий с исходным кодом (Java) и на файл apk.
>
> Реализуйте приложение удобным для вас способом, но только на Java. Используйте любые инструменты и библиотеки. Мы будем оценивать качество кода, а не его объём.

### Реализованные Требования

- [x] комментарии в коде;
- [x] обработку ошибок;
- [ ] анимацию;
- [x] кеширование (приложение сохраняет предыдущий ответ сервера);
- [ ] тесты.

### Примерный вид экранов

<img src="../master/art/provided/artists-list.png" width="250">
<img src="../master/art/provided/artists-detail.png" width="250">

## Библиотеки

* [ButterKnife](https://github.com/JakeWharton/butterknife)
* [Timber](https://github.com/JakeWharton/timber)
* [Dagger 2](https://github.com/google/dagger)
* [Retrofit 2](https://github.com/square/retrofit)
* [OkHttp 3](https://github.com/square/okhttp)
* [Gson](https://github.com/google/gson)
* [Glide](https://github.com/bumptech/glide)
* [GlidePalette](https://github.com/florent37/GlidePalette)
* [RxJava](https://github.com/ReactiveX/RxJava)
* [RxAndroid](https://github.com/ReactiveX/RxAndroid)
* [Gradle Retrolambda](https://github.com/evant/gradle-retrolambda)

## Школа мобильной разработки Яндекса

* [Описание](https://academy.yandex.ru/events/mobdev/msk-2016/)
* [Регистрация](https://academy.yandex.ru/events/mobdev/msk-2016/register/)

## License

    Copyright 2016 Emin Yahyayev

    Licensed under the Apache License, Version 2.0 (the "License");
    you may not use this file except in compliance with the License.
    You may obtain a copy of the License at

        http://www.apache.org/licenses/LICENSE-2.0

    Unless required by applicable law or agreed to in writing, software
    distributed under the License is distributed on an "AS IS" BASIS,
    WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied.
    See the License for the specific language governing permissions and
    limitations under the License.
