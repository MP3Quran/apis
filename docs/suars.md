#### Suras
-------------------------

##### Getting Suras List of a specific language
###### `GET` http://api.mp3quran.net/api_2/soar?language=en



```json
{
	"Suras_Name": [
		{
			"id": 1,
			"name": "Al-Fatihah ",
			"start_page": 1,
			"end_page": 1,
			"type": 0
		},
		{
			"id": 2,
			"name": "Al-Baqarah ",
			"start_page": 2,
			"end_page": 49,
			"type": 1
		},
      	...
	]
}
```



- `id` : Unique ID

  

- `name` : Sura's name

  

- `start_page` : Starting page number

  

- `end_page` : Ending page number

  

- `type` :
	
	- `0` : Makiya
	- `1` : Medinan
