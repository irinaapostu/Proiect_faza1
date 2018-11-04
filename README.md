# Proiect_faza1
INTRODUCERE

1.	Care este principala nevoie/problemă pe care o rezolvă produsul vostru?
Conform Institutului Național de Statistică, în România, timpul liber al persoanelor este în scădere, acesta fiind în medie 3:50 ore în zilele lucrătoare și 6:10 ore în zilele de odihnă. Aplicația noastră are rolul de a veni în sprijinul oamenilor de a economisi timp prin crearea unor playlist-uri după preferințele utilizatorului. De asemenea, produsul pe care îl livrăm oferă posibilitatea utilizatorul de a putea asculta melodiile pe care le dorește fără să fie întrerupt de către reclame sau să fie nevoit să aibă aplicația deschisă atunci când este redată muzica aleasă de către acesta.

2.	Cărui tip de utilizatori se adresează produsul vostru?
Aplicația are ca și grup țintă persoanele cu vârstele cuprinse între 20- 24 de ani, pasionați de muzică, sunt angajați sau studenți și locuiesc în mediul urban.
Profilul demografic al utilizatorului:
-	Vârstă cuprinsă între 20- 24 de ani;
-	Persoană pasionată de orice tip de muzică;
-	Persoană ocupată, care își gestionează timpul cât mai util;
-	Angajat sau student;
-	Locuiește în mediul urban;

3.	Ce alte produse similare există în piață?

•	Aplicația Deezer-Songs&Music Player oferă utilizatorului o gamă largă de melodii pe care le poate asculta chiar si offline.Deasemenea, aplicația oferă posibilitatea urmăririi artiștilor preferați, pentru a fi la curent cu cele mai noi melodii.
•	SoundCloud este o aplicație care ofera posibilitatea creării de playlist-uri offline.Mai mult,dispune de o platformă sociala unde iți poți promova propria muzică.
•	Groove este o aplicație de tip music player atât pentru IOS cât și pentru Android,  ce folosește un algoritm special pentru recomandarea unor melodii pe baza preferințelor utilizatorului.Aceasta integreaza Last.fm.
•	CloudTunes e o alta aplicație care faciliteaza accesul la melodii stocate in cloud(YouTube , Dropbox) și integreaza cu Last.fm,Facebook,Musicbrainz.Adăugarea melodiilor in playlist se realizează prin drag and drop, iar playlisturile pot conține atât melodii de pe Dropbox, cât si videoclipuri de pe Youtube.

INTERFEȚE APLICAȚIE

Un vizitator al paginii are opțiunea - register (dacă e nou pe site) -login (dacă a mai folosit deja platforma) - să continue fără a avea un cont; 
După logare/înregistrare, user-ul va avea acces: 
- la o bară de căutare a melodiilor preferate;
- la un buton de creare playlist; 
- la playlist-urile create anterior (dacă nu s-a înregistrat acum pentru prima oară);
- aici își poate șterge/adăuga melodii, sau chiar șterge playlist; 
Daca alege prima opțiune și dacă melodia este găsită, acesta are opțiunea de a o asculta sau de a o adăuga la un playlist creat de el. După delogare, playlist-urile user-ului ramân salvate în baza de date. Dacă vizitatorul alege să continue fără un cont, datele ramân doar pe sesiunea curentă.













API REST

Request: get/artists?search={artistname}
Response: 
[
{
“artistname”: “Searched artists”
}
]

Request: get/songs?search={songname}
Response:
[
{
“songname”: “Searched songs”
}
]



Request: get/playlists?search={userplaylist}
Response:
[
{
“userplaylist”: “User’s playlist”
}
]

Request: get/currentsongs?search={currentsong}
Response:
[
{
“currentsong”: “Current song”
}
]















ANEXE
1.	Chestionar pentru validarea ideii

