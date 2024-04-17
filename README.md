Válassz egyet a következő, ingyenesen, bejelentkezés nélkül használható API feladatokból egyet, és készíts webalkalmazást vele.


1) Időjárás: (https://github.com/robertoduessmann/weather-api)
	API Endpoint: https://goweather.herokuapp.com/weather/<város>
	Példa API Endpoint: https://goweather.herokuapp.com/weather/Budapest
	A feladat nagyon egyszerű: készíts egy webalkalmazást amely a kezelőfelületén
	bekér egy város nevet, majd az API segítségével megjeleníti
 	a megadott városban lévő időjárás adatait:
 		- Szél sebessége.
		- Jelenlegi hőmérsékélet.
		- 3 napos előrejelzés.
		(Ezek az adatok mind megtalálhatóak az API válaszában).
	Használj ikonokat, törekedj a frappáns megjelenésre, illetve a könnyen kezelhetőségre, reszponzivitásra.




2) Filmek: (https://github.com/SpEcHiDe/IMDbOT)
	API Endpoint: https://search.imdbot.workers.dev/?q=<Film cím>
	Példa API Endpoint: https://search.imdbot.workers.dev/?q=Interstellar
	A feladat egy filmkereső webapplikáció elkészítése.
	A fent látható API Endpointnak a "q" url paraméterébe meg lehet adni egy film nevet,
	majd vissza adja JSON formátumban a találatokat. Csinálj egy olyan webapplikációt amely
	rendelkezik egy keresővel amellyel filmekre tudunk keresni. 
	A találatokról jelenítsd meg a következő adatokat külön külön kártyában:
		- A film címe
		- A film Helyezése
		- A film Szereplői
		- A film posztere



3) Emojik: (https://github.com/cheatsnake/emojihub)
	API Endpoint: https://emojihub.yurace.pro/api/<egyéb routeok>
	Példa API Endpoint: https://emojihub.yurace.pro/api/random
	A feladat egy emoji böngésző webalkalmazást készíteni.
	Lehetőség van egy random emoji-t lekérni (pl.: a példa endpoint-tal),
	kategóriák közül választani. Kiválasztasz egy kategóriát -> megjelennek az abba
	a kategóriába tartozó emojik. 
	Fontos, egy emoji-t ki lehessen másolni ha rákattintunk.
	Nézd meg a Git repository-t, amiben találsz példa kéréseket, illetve
 	ott találod meg a kategóriákat is, amikből lehet kérdezni.
	A következő adatokat jelenítsd meg egy emojiról:
		- Az emoji neve
		- HTML kódja 
		- Unicode-ja.

Bármely feladat megoldása során használj ikonokat, törekedj a 
frappáns megjelenésre, illetve a könnyen kezelhetőségre, reszponzivitásra.
A feladat kiválasztása előtt mindenképp nyisd meg a példa API Endpointokat, hiszen
láthatod, hogy pontosan milyen adatszerkezettel kell majd dolgoznod ez pedig 
segíthed döntésed meghozatalában, vagy az ötletelésben.

- Rostás András Péter 2024.04.17
