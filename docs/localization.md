#### Localization
-------------------------

##### Getting translations (Localizations)

###### `GET` http://api.mp3quran.net/api_2/languages

```json
{
	"language": [
		{
			"id": "1",
			"language": "_arabic",
			"reciter_name": "http://api.mp3quran.net/api_2/reads?language=ar",
			"sura_name": "http://api.mp3quran.net/api_2/soar?language=ar",
			"moshaf_name": "http://api.mp3quran.net/api_2/moshaf?language=ar"
		},
		{
			"id": "2",
			"language": "_english",
			"reciter_name": "http://api.mp3quran.net/api_2/reads?language=en",
			"sura_name": "http://api.mp3quran.net/api_2/soar?language=en",
			"moshaf_name": "http://api.mp3quran.net/api_2/moshaf?language=en"
		},
        ...
	]
}
```

