<h3>Анализ юзабилити сайта "Интернет-банк"</h3>

<h4>1. Авторизация</h4>

<h5>Проблема "Выход из системы"</h5>

На этапе авторизации в системе, при троекратном неверном вводе пароля, учетная запись блокируется, и клиент информируется об этом соответствующим сообщением с указанием времени автоматической разблокировки.

![blocked](https://raw.github.com/she-wo1f/she-wo1f.github.io/master/imgs/blocked.png)

При этом повторить попытку авторизации, в т.ч. под другим пользователем, нет возможности до указанного времени разблокировки, так как система не прерывает сессию автоматически до наступления таймаута.

<h5>Проблема "Отображение меню неавторизованным пользователям"</h5>

При блокировке пользователя слева отображается меню, сами кнопки при этом неактивны.

<h5>Рекомендации:</h5>

1. Добавить на страницу ссылку "Выход";
2. Не показывать меню слева до прохождения авторизации в системе.

![exit](https://raw.github.com/she-wo1f/she-wo1f.github.io/master/imgs/exit.png)
