#### Reciters
-------------------------

##### Getting Reciters List of a specific language
###### `GET` http://api.mp3quran.net/api_2/reads?language=en

`language` 	=> Accepts any language's code (<a href="../docs/localization.md" target="_blank">Localizations - الترجمات</a>)

```json
{
    "reads": [
        ...
        {
			"id": 51,
			"name": "Abdulbasit Abdulsamad",
			"Server": "",
			"letter": "A",
			"moshaf": [
				{
					"id": 53,
					"moshaf_type": 11,
					"name": "Hafs A'n Assem - Murattal",
					"Server": "https://server7.mp3quran.net/basit",
					"sample": "",
					"count": 114,
					"suras": "1,2,3,4,5,6,7,8,9,10,11,12,13,14,15,16,17,18,19,20,21,22,23,24,25,26,27,28,29,30,31,32,33,34,35,36,37,38,39,40,41,42,43,44,45,46,47,48,49,50,51,52,53,54,55,56,57,58,59,60,61,62,63,64,65,66,67,68,69,70,71,72,73,74,75,76,77,78,79,80,81,82,83,84,85,86,87,88,89,90,91,92,93,94,95,96,97,98,99,100,101,102,103,104,105,106,107,108,109,110,111,112,113,114"
				},
				{
					"id": 52,
					"moshaf_type": 21,
					"name": "Warsh A'n Nafi' - Murattal",
					"Server": "https://server10.mp3quran.net/basit_warsh",
					"sample": "",
					"count": 114,
					"suras": "1,2,3,4,5,6,7,8,9,10,11,12,13,14,15,16,17,18,19,20,21,22,23,24,25,26,27,28,29,30,31,32,33,34,35,36,37,38,39,40,41,42,43,44,45,46,47,48,49,50,51,52,53,54,55,56,57,58,59,60,61,62,63,64,65,66,67,68,69,70,71,72,73,74,75,76,77,78,79,80,81,82,83,84,85,86,87,88,89,90,91,92,93,94,95,96,97,98,99,100,101,102,103,104,105,106,107,108,109,110,111,112,113,114"
				},
				{
					"id": 51,
					"moshaf_type": 12,
					"name": "Hafs A'n Assem - Almusshaf Al Mojawwad",
					"Server": "https://server13.mp3quran.net/basit_mjwd",
					"sample": "",
					"count": 114,
					"suras": "1,2,3,4,5,6,7,8,9,10,11,12,13,14,15,16,17,18,19,20,21,22,23,24,25,26,27,28,29,30,31,32,33,34,35,36,37,38,39,40,41,42,43,44,45,46,47,48,49,50,51,52,53,54,55,56,57,58,59,60,61,62,63,64,65,66,67,68,69,70,71,72,73,74,75,76,77,78,79,80,81,82,83,84,85,86,87,88,89,90,91,92,93,94,95,96,97,98,99,100,101,102,103,104,105,106,107,108,109,110,111,112,113,114"
				}
			]
		},
        ...
    ]
}
```



- `id` : Unique ID

  

- `name` : Reciter's name

  

- `letter` : First letter of the Reciter's name

  

- `moshaf` : MosHaf List of the Reciter
	
	- `id` : Unique ID
	
	- `moshaf_type` : MosHaf's Type ID  (<a href="../docs/moshafs.md" target="_blank">MosHaf - المصحف</a>)
	
	- `name` : MosHaf's Name
	
	- `server` : URL of audio files list
	
	- `count` : Total Suras Count
	
	- `suras` : Concatenated list of Suras numbers
	
	  

------


##### Getting Latest Reciters added recently

###### `GET` http://api.mp3quran.net/api_2/recent_reads

```json
{
	"reads": [
		{
			"id": 274,
			"name": "محمد أبوسنينة",
			"Server": "",
			"letter": "م",
			"recent_date": "2021-03-25 16:34:55",
			"moshaf": [
				{
					"id": 274,
					"moshaf_type": 51,
					"name": "قالون عن نافع - مرتل",
					"Server": "http://server16.mp3quran.net/sneineh/Rewayat-Qalon-A-n-Nafi",
					"sample": "",
					"count": 114,
					"suras": "1,2,3,4,5,6,7,8,9,10,11,12,13,14,15,16,17,18,19,20,21,22,23,24,25,26,27,28,29,30,31,32,33,34,35,36,37,38,39,40,41,42,43,44,45,46,47,48,49,50,51,52,53,54,55,56,57,58,59,60,61,62,63,64,65,66,67,68,69,70,71,72,73,74,75,76,77,78,79,80,81,82,83,84,85,86,87,88,89,90,91,92,93,94,95,96,97,98,99,100,101,102,103,104,105,106,107,108,109,110,111,112,113,114"
				}
			]
		},
		...
	]
}
```
