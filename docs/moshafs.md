#### MosHaf
-------------------------

##### Getting MosHaf List of a specific language
###### `GET` http://api.mp3quran.net/api_2/moshaf?language=en



```json
{
	"Moshafs_Name": [
		{
			"id": 11,
			"moshaf_type": 1,
			"moshaf_id": 1,
			"name": "Hafs A'n Assem - Murattal"
		},
		{
			"id": 12,
			"moshaf_type": 1,
			"moshaf_id": 2,
			"name": "Hafs A'n Assem - Almusshaf Al Mojawwad"
		},
		...
	]
}
```



- `id` : Unique ID

  

- `name` : Moshaf's name

  

- `moshaf_id` :
	- `1` : Murattal
	- `2` : Almusshaf Al Mojawwad
	- `3` : Almusshaf Al Mo'lim
	
	  
	
- `moshaf_type` : 
	- `1`   : Hafs A'n Assem
	- `2`   : Warsh A'n Nafi'
	- `3`   : Khalaf A'n Hamzah
	- `5`   : Qalon A'n Nafi'
	- `7`   : Assosi A'n Abi Amr
	- `8`   : Qalon A'n Nafi' Men Tariq Abi Nasheet
	- `9`   : Rowis and Rawh A'n Yakoob Al Hadrami
	- `10` : Warsh A'n Nafi' Men  Tariq Abi Baker Alasbahani
	- `11` : Albizi and Qunbol A'n Ibn Katheer
	- `12` : AlDorai A'n Al-Kisa'ai
	- `13` : Aldori A'n Abi Amr
	- `15` : Sho'bah A'n Asim
	- `16` : Ibn Thakwan A'n Ibn Amer