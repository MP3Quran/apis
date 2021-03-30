#### Reciters
-------------------------

##### Getting languages
###### `GET` https://mp3quran.net/api/get_json.php
`json 		=> Reciters List (URL)`
`sura_name 	=> Suras Names List (URL)`

```json
{
    "language": [
        {
            "id": "1",
            "language": "_arabic",
            "json": "https://mp3quran.net/api/_arabic.json",
            "sura_name": "https://mp3quran.net/api/_arabic_sura.json"
        },
        {
            "id": "2",
            "language": "_english",
            "json": "https://mp3quran.net/api/_english.json",
            "sura_name": "https://mp3quran.net/api/_english_sura.json"
        },
        ...
    ]
}
```

------


##### `json` Getting reciters of  a single language

###### `GET` https://mp3quran.net/api/_english.json
`Server 	=> URL of audio files list`

```json
{
	"reciters": [
		{
			"id": "49",
			"name": "Abdelbari Al-Toubayti",
			"Server": "https://server6.mp3quran.net/thubti",
			"rewaya": "Rewayat Hafs A'n Assem",
			"count": "114",
			"letter": "A",
			"suras": "1,2,3,4,5,6,7,8,9,10,11,12,13,14,15,16,17,18,19,20,21,22,23,24,25,26,27,28,29,30,31,32,33,34,35,36,37,38,39,40,41,42,43,44,45,46,47,48,49,50,51,52,53,54,55,56,57,58,59,60,61,62,63,64,65,66,67,68,69,70,71,72,73,74,75,76,77,78,79,80,81,82,83,84,85,86,87,88,89,90,91,92,93,94,95,96,97,98,99,100,101,102,103,104,105,106,107,108,109,110,111,112,113,114"
		},
		...
	]
}
```


------


##### `sura_name` Getting suras names list of  a single language

###### `GET` https://mp3quran.net/api/_english_sura.json

```json
{
	"Suras_Name": [
		{
			"id": "1",
			"name": "Al-Fatihah "
		},
		{
			"id": "2",
			"name": "Al-Baqarah "
		},
		{
			"id": "3",
			"name": "Al-Imran "
		},
		...
	}
}
```
