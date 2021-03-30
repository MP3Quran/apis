#### Radios
-------------------------

##### Getting languages
###### `GET` http://api.mp3quran.net/radios/get_radios.php

```json
{
    "language": [
        {
            "id": "1",
            "language": "العربية",
            "radio_url": "http://api.mp3quran.net/radios/radio_arabic.json"
        },
        {
            "id": "2",
            "language": "English",
            "radio_url": "http://api.mp3quran.net/radios/radio_english.json"
        },
        ...
    ]
}
```

--------

##### `radio_url` Getting radios list of a single language
###### `GET` http://api.mp3quran.net/radios/radio_english.json

```json
{
    "radios": [
        {
            "name": "---Amazing short Recitations---",
            "radio_url": "http://live.mp3quran.net:9702/;"
        },
        {
            "name": "--Quran Tafseer--",
            "radio_url": "http://live.mp3quran.net:9718/;"
        },
        {
            "name": "-Beautiful Recitations-",
            "radio_url": "http://live.mp3quran.net:9992/;"
        },
        {
            "name": "-Main Radio-",
            "radio_url": "http://live.mp3quran.net:8006/;"
        },
        ...
    ]
}
```