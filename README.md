# h1

Tehtävän tekeminen alkaa alkaa 25.10.2023 klo 13:30.  Tein tehtäviä yhdessä kurssitoverini Alisa Ahokkaan kanssa. ALoitin tehtävien teon a kohdasta jätin x myöhemmäksi.

# a.)

# Level 0

The goal of this level is for you to log into the game using SSH. The host to which you need to connect is bandit.labs.overthewire.org, on port 2220. The username is bandit0 and the password is bandit0. Once logged in, go to the Level 1 page to find out how to beat Level 1.

Annoin command prompt commandin ssh bandit0@bandit.labs.overthewire.org -p 2220 



<img width="796" alt="Screenshot 2023-10-25 at 13 41 06" src="https://github.com/AkiAleksi/h1/assets/112399816/35e42af5-adf4-449f-a35b-86d8351da70a">





Sen jälkeen annoin salasanan, joka oli annettu tehtäcän annossa eli bandit0.
<img width="603" alt="Screenshot 2023-10-25 at 13 41 15" src="https://github.com/AkiAleksi/h1/assets/112399816/731730d4-49a5-4a78-a19c-61a1d840ced7">


Kirjautuminen sisään onnistui.  



<img width="551" alt="Screenshot 2023-10-25 at 13 33 17" src="https://github.com/AkiAleksi/h1/assets/112399816/364ea0d8-9f74-4bfa-ad4e-cd0c516b0338">


Level 0 suoritettu.

# level 1
The password for the next level is stored in a file called readme located in the home directory. Use this password to log into bandit1 using SSH. Whenever you find a password for a level, use SSH (on port 2220) to log into that level and continue the game.

Syötin ls komennon. Sen jälkeen cat readme. Sain vastaukseksi NH2SXQwcBdpmTEzi3bvBHMM9H66vVXjL.  Kokeilin syöttää salasanan ei toiminut.

<img width="762" alt="permission denied lvl1" src="https://github.com/AkiAleksi/h1/assets/112399816/a4ec0299-3187-4c0b-b4ab-06e66c7fdf96">







Annoin komennon exit. Sen jälkeen annoin komennon. ssh bandit1@bandit.labs.overthewire.org -p 2220. Syötin salasanan NH2SXQwcBdpmTEzi3bvBHMM9H66vVXjL. Pääsin kirjautumaan sisään. 


<img width="653" alt="Screenshot 2023-10-25 at 13 59 25" src="https://github.com/AkiAleksi/h1/assets/112399816/8af814d9-7a54-4123-b481-fd955fae12ef">

Level 1 suoritettu.

# Level 2

The password for the next level is stored in a file called - located in the home directory

Ls komennolla sain vastaukseksi -. Kokeilin avata komennolla cat -. Ei toiminut. Googletin ja piti avata cat < - komennolla. Sain vastaukseksi rRGizSaX8Mk1RTb1CNQoXTcYZWU6lgzi. 

<img width="360" alt="level 2 kuva 1" src="https://github.com/AkiAleksi/h1/assets/112399816/98793787-3a4b-4af2-8d8d-ffb3edba7de5">



Annoin komennon exit. Komento ssh bandit2@bandit.labs.overthewire.org -p 2220. Sen jälkeen annoin salasanan rRGizSaX8Mk1RTb1CNQoXTcYZWU6lgzi. 

<img width="712" alt="level 2 kuva 2" src="https://github.com/AkiAleksi/h1/assets/112399816/29ec60d2-29ce-47f0-841d-08702287b5b8">



Kirjauduin sisään onnistuneesti. 

<img width="824" alt="level 2 kuva 3" src="https://github.com/AkiAleksi/h1/assets/112399816/b9fcebbe-f193-402a-bcdf-e8f4220028e4">



Ratkaistu level 2.

Klo 14:23 25.10.2023. a kohta ratkaistu.

# B.) 

Päätin suorittaa Challenge.fi ssä yhden tehtävän. Valitsin numeron 172. Tehtävän anto oli "where was this picture taken".

<img width="652" alt="b kohta" src="https://github.com/AkiAleksi/h1/assets/112399816/3dfcf55d-02b0-4726-b9cd-baaaedf46f44">


Aukesi kuva eiffel tornista.

<img width="682" alt="Screenshot 2023-10-26 at 10 14 28" src="https://github.com/AkiAleksi/h1/assets/112399816/9938b0fe-8efb-464f-b4e2-8b34cbb05866">


Etsin kuvan tiedoista GPS. Siinä löytyi osoite missä kuva on otettu.

<img width="339" alt="Screenshot 2023-10-25 at 14 54 43" src="https://github.com/AkiAleksi/h1/assets/112399816/eebfe26d-14b7-433b-ac18-c0ca2fc6d821">


Oikea vastaus oli Las Vegas. 

<img width="602" alt="B kohta ratkasiu" src="https://github.com/AkiAleksi/h1/assets/112399816/906cd1cd-de04-4e6a-aba1-e91ccc84b73e">

# C.)

Ratkaise PortSwigger Labs: Lab: SQL injection vulnerability in WHERE clause allowing retrieval of hidden data.

Muutetaan urlia rikkomalla tietokantalause urlissa hakemalla ‘OR+1+=1—  .

<img width="1582" alt="Lab" src="https://github.com/AkiAleksi/h1/assets/112399816/d54bca98-bffc-4805-bba2-ca4beb013def">

C ratkaistu.

<img width="547" alt="Screenshot 2023-10-25 at 15 22 12" src="https://github.com/AkiAleksi/h1/assets/112399816/cd39c95b-f144-4614-a9d1-24eca43b0060">


Tehtävien teko sessioni päättyi 25.10.2023 klo 15:30.
Tehtävien teko jatkuu 26.10.2023 klo 10:43. Tällä kertaa yksin.
# d.)
Asenna Linux virtuaalikoneeseen. Suosittelen joko Kali (viimeisin versio) tai Debian 12-Bookworm.

Latasin ja asensin Virtualboxin koneelleni. Latasin Kali Linux ISO tiedoston sen virallisilta nettisivuilta. Loin uuden virtuaalikoneen. Valitsin käyttöjärjestelmäksi Linux.  Sen jälkeen, kun virtuaalikone oli luotu menin virtuaalikoneen asetuksiin. Storage-välilehdeltä lisäsin Kali Linuxin ISO-tiedoston optinen asema kohdassa. Tallensin asetukset. Sen jälkeen käynnistin virtuaalikoneen.



<img width="850" alt="Screenshot 2023-10-26 at 11 42 43" src="https://github.com/AkiAleksi/h1/assets/112399816/1de66dfb-aa69-4ed9-acc6-24d077946fcf">




Sen jälkeen aloitin asennuksen. Tein kuitenkin pienen virheen asennusprosessin raportoinnin kannalta. Autocapturoin hiiren ja näppäimistön, joten en pystynyt ottamaan screenshotteja asennusprosessin aikana.


<img width="319" alt="Screenshot 2023-10-26 at 11 42 52" src="https://github.com/AkiAleksi/h1/assets/112399816/ac559b7c-caf1-4970-a0df-360986527980">


Asennus onnistui kuitenkin muuten hyvin. Löysin netistä ohjeet asennukseen screenshotteina. seurasin ohjeita. https://www.kali.org/docs/installation/hard-disk-install/


<img width="1259" alt="Screenshot 2023-10-26 at 13 19 03" src="https://github.com/AkiAleksi/h1/assets/112399816/acd5e945-d436-4cce-9ef7-24d80a068399">


<img width="403" alt="Screenshot 2023-10-26 at 13 14 40" src="https://github.com/AkiAleksi/h1/assets/112399816/8154f6f8-c131-4eaf-b676-5682cd8275c9">

Kokeilin kirjautua sisään ja se onnistui.


<img width="405" alt="Screenshot 2023-10-26 at 13 02 32" src="https://github.com/AkiAleksi/h1/assets/112399816/4c632d63-42a9-47ff-a9b6-3a9fb6dc3d99">


Kohta d ratkaistu.

# e.)

Porttiskannaa 1000 tavallisinta tcp-porttia omasta koneestasi (localhost). Analysoi tulokset.

Avasin terminaalin Kali Linuxissa. Ajoin komennon nmap -p 1-1000 "oma ip-osoite". 


<img width="331" alt="Screenshot 2023-10-26 at 14 00 53" src="https://github.com/AkiAleksi/h1/assets/112399816/ce778548-054d-429d-aa84-d3fbe649102a">

Sain vastaukseksi. Not shown: 1000 closed tcp ports (conn-refused). Skannaukseni havaitsi siis 1000 suljettua TCP-porttia. Niihin yritettiin muodostaa yhteys. Yhteyspyyntö kuitenkin hylättiin. Tulos osoittaa, että portit joihin ei saatu yhteyttä ovat suljettuja. Niiden kautta ei voi hyökkäystarkoituksessa muodostaa yhteyksiä. Se suojelee tietokonetta ulkopuolisilta hyökkäyksiltä. 

# f.)

Ajoin Kali Linuxissa komennon nmap -p- "oma IP-osoite".

<img width="372" alt="TCP kaikki" src="https://github.com/AkiAleksi/h1/assets/112399816/8b1453a6-d239-4e75-8f0a-06f4c14f0614">

Nyt minulla näkyy avoimia portteja. Se tarkoittaa, että portit ovat kuuntelevia yhteyksiä. Joku ohjelma, palvelu tai prosessi käyttää niitä. Esimerkiksi minulla näyttäisi olevan MySQL-tietokantapalvelin käytössä. Joissain porteissa näkyy filtered. Kyseinen portti ei vastaa skannausyrityksiin. Se tarkoittaa, että portin tila ei ole avoin eikä suljettu vaan suodatettu. Syynä tälle voisi olla palomuuri tai verkkosuodatus. Joissain porteissa esiintyvä "unknown" taas viittaa siihen, että nmap ei pysty määrittelemään portin tarkkaa sovellusta tai palvelua sen vastauksen perusteella. Avoimet portit voivat olla tietoturvariski, jos ei ole tietoinen avoimista porteista ja niiden palveluiden tietoturva-aukoista.

# g.)
https://www.codecademy.com/resources/docs/cybersecurity/nmap/aggressive-scan mukaan nmap -A on laaja skannaus. Se tarjoaa paljon tarkempaa tietoa kuin normaali skannaus. OS detection (-O), Version detection (-sV), Script scanning (-sC), Traceroute (--traceroute). 

<img width="362" alt="Nmap -A 1" src="https://github.com/AkiAleksi/h1/assets/112399816/aeeb44dc-d956-48df-80f4-fd58df9cb4bf">

<img width="430" alt="nmap-A 2" src="https://github.com/AkiAleksi/h1/assets/112399816/f43d596f-b1d6-4bf3-93b0-9d8c9242dec8">





