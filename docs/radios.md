#### Radios
-------------------------

##### Getting radios list of a specific language
###### `GET` http://api.mp3quran.net/api_2/radios?language=en

```json
{
	"reads": [
		{
			"id": 1,
			"URL": "http://live.mp3quran.net:9946/;",
			"name": "Ibrahim Al-Akdar"
		},
		{
			"id": 2,
			"URL": "http://live.mp3quran.net:9966/;",
			"name": "Shaik Abu Bakr Al Shatri"
		},
        ...
    ]
}
```



- `id` : Unique ID

  

- `name` : Radio's name

  

- `URL` : Radio's URL