#### Versesf
-------------------------

##### Getting languages
###### `GET` http://api.mp3quran.net/verse/verse.php

```json
{
	"language": [
		{
			"id": "1",
			"language": "العربية",
			"verse_url": "https://api.mp3quran.net/verse/verse_ar.json"
		},
        ...
    ]
}
```

--------

##### `verse_url` Getting reciters list with verses of a single language
###### `GET` https://api.mp3quran.net/verse/verse_en.json
`audio_url_bit_rate_32_		=> Audio files 32`
`audio_url_bit_rate_64		=> Audio files 64`
`audio_url_bit_rate_128		=> Audio files 128`

```json
{
	"reciters_verse": [
		{
			"id": "1",
			"name": "Ibrahim Al-Akdar",
			"rewaya": "Rewayat Hafs A'n Assem",
			"musshaf_type": "Murattal",
			"audio_url_bit_rate_32_": "https://verse.mp3quran.net/arabic/ibrahim_alakhdar/32/",
			"audio_url_bit_rate_64": "",
			"audio_url_bit_rate_128": ""
		},
        ...
    ]
}
```

--------

#####  Getting sura's verses list
###### `GET` http://api.mp3quran.net/api/surah?surah=1&language=ar

```json
{
    "1": {
        "lang": "Arabic",
        "lang_native": "العربية",
        "surah_id": 1,
        "aya_id": 1,
        "surah_name": "الفاتحة",
        "ayah_text": "بِسْمِ اللَّهِ الرَّحْمَنِ الرَّحِيمِ",
        "image_url": "http://api.mp3quran.net/ayah_image/001001.png",
        "reciter_name": "",
        "audio_url_arabic": "",
        "bitrate": ""
    },
    "2": {
        "lang": "Arabic",
        "lang_native": "العربية",
        "surah_id": 1,
        "aya_id": 2,
        "surah_name": "الفاتحة",
        "ayah_text": "الْحَمْدُ لِلَّهِ رَبِّ الْعَالَمِينَ",
        "image_url": "http://api.mp3quran.net/ayah_image/001002.png",
        "reciter_name": "",
        "audio_url_arabic": "",
        "bitrate": ""
    },
	...
}
```

--------

#####  Getting sura's single verse
###### `GET` http://api.mp3quran.net/api/aya?surah=1&aya=1&language=ar

```json
{
	"lang": "Arabic",
	"lang_native": "العربية",
	"surah_id": 1,
	"aya_id": 1,
	"surah_name": "الفاتحة",
	"ayah_text": "بِسْمِ اللَّهِ الرَّحْمَنِ الرَّحِيمِ",
	"image_url": "http://api.mp3quran.net/ayah_image/001001.png",
	"reciter_name": "",
	"audio_url_arabic": "",
	"bitrate": ""
}
```

--------

#####  Getting sura's single verses by range
###### `GET` http://api.mp3quran.net/api/ayat?surah=1&from=1&to=2&language=ar

```json
{
	"1": {
		"lang": "Arabic",
		"lang_native": "العربية",
		"surah_id": 1,
		"aya_id": 1,
		"surah_name": "الفاتحة",
		"ayah_text": "بِسْمِ اللَّهِ الرَّحْمَنِ الرَّحِيمِ",
		"image_url": "http://api.mp3quran.net/ayah_image/001001.png",
		"reciter_name": "",
		"audio_url_arabic": "",
		"bitrate": ""
	},
	"2": {
		"lang": "Arabic",
		"lang_native": "العربية",
		"surah_id": 1,
		"aya_id": 2,
		"surah_name": "الفاتحة",
		"ayah_text": "الْحَمْدُ لِلَّهِ رَبِّ الْعَالَمِينَ",
		"image_url": "http://api.mp3quran.net/ayah_image/001002.png",
		"reciter_name": "",
		"audio_url_arabic": "",
		"bitrate": ""
	}
}

```