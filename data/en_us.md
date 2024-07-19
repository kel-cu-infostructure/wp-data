#### {"title": "What kind of data is Kel getting?", "ignoreList": false, "hideContact": false}
# What kind of data is Kel getting?

<p><a href="/data" class="actionlink"><i></i>Русская версия</a></p>

This post discusses the use of the official API, which requires a game license

Because the API checks for a license, your game access token is sent to WaterPlayer when you use the web services.
The verification request goes through the official Minecraft API: https://api.minecraftservices.com/entitlements/mcstore

If you publish your playlist, the request sends this data: id=file name; playlist_data=playlist itself in base64
