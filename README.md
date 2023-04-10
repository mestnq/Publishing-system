<p align="center">
    <a href="https://github.com/yiisoft" target="_blank">
        <img src="https://avatars0.githubusercontent.com/u/993323" height="100px">
    </a>
    <h1 align="center">Издательская система с Yii 2</h1>
    <br>
</p>

Использовала: Yii2, mySQL, composer, Nginx

Все запускается через Docker.

(Шаблонная верстка) В данный момент существует главная страница с отображением статей. Статьи можно выбрать через категории. Также есть раздел популярных и недавних статей.
(Дефолтная верстка) Есть админка в которую можно попасть через /admin. В админке есть валидации. Можно создать статью, добавить картинку, теги (можно и без них), категорию. Можно не ставить дату поста в админке и он сам поставит текущую. Ну и естественно есть список всех статей.

В БД все сохраняется, картинки при удалении статьи тоже удаляются. Картинки складываются не под своим именем, а под сгенерированным (то есть может существовать n одинаковых картинок).

!!! Планируется доделать регистрацию и авторизацию. Скрыть доступ к админке.
