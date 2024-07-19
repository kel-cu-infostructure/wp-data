#### {"title": "Какие данные получает Кел?", "ignoreList": false, "hideContact": false}
# Какие данные получает Кел?

<p><a href="/data/en_us" class="actionlink"><i></i>English version</a></p>

В данном посте рассматривается использование официального API, которое требует лицензию игры

Поскольку API проверяет наличие лицензии, при использовании веб-сервисов WaterPlayer отправляется ваш токен доступа игры.
Запрос на проверку проходит через официальное API Minecraft: https://api.minecraftservices.com/entitlements/mcstore

Если вы публикуете свой плейлист, то в запросе отправляется вот такие данные: id=название файла; playlist_data=сам плейлист в base64
