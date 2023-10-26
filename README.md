# h1
Homework for course taught by Tero Karvinen

 Tehtävän tekeminen alkaa alkaa 25.10.2023 klo 13:30.  Tein tehtäviö yhdessä kurssitoverini Alisa Ahokkaan kanssa. 

Level 0

The goal of this level is for you to log into the game using SSH. The host to which you need to connect is bandit.labs.overthewire.org, on port 2220. The username is bandit0 and the password is bandit0. Once logged in, go to the Level 1 page to find out how to beat Level 1.

Anon command prompt commandin 	•	ssh bandit0@bandit.labs.overthewire.org -p 2220 

Sen jälkeen annoin salasanan, joka oli annettu tehtäcän annossa.

Kirjautuminen sisään onnistui.  
Level 1

The password for the next level is stored in a file called readme located in the home directory. Use this password to log into bandit1 using SSH. Whenever you find a password for a level, use SSH (on port 2220) to log into that level and continue the game.

Syötin ls komennon. Sen jälkeen cat readme. Sain vastaukseksi NH2SXQwcBdpmTEzi3bvBHMM9H66vVXjL.  Kokeilin syöttää ei toiminut. Annoin komennon exit. Sen jälkeen annoin komennon. ssh bandit1@bandit.labs.overthewire.org -p 2220. Syötin salasanan NH2SXQwcBdpmTEzi3bvBHMM9H66vVXjL. Pääsin kirjautumaan sisään. 

Level 2

The password for the next level is stored in a file called - located in the home directory

Ls komennolla sain vastaukseksi -. Kokeilin avata komennolla cat -. Ei toiminut. Googletin ja piti avata cat < - komennolla. Sain vastaukseksi rRGizSaX8Mk1RTb1CNQoXTcYZWU6lgzi. Annoin komennon exit. Komento ssh bandit2@bandit.labs.overthewire.org -p 2220. Sen jälkeen annoin salasanan rRGizSaX8Mk1RTb1CNQoXTcYZWU6lgzi. Kirjauduin sisään onnistuneesti. Ratkaistu level 2.

Klo 14:23 25.10.2023. a kohta ratkaistu.

B.) Kohta

Päätin suorittaa Challenge.fi ssä yksi tehtävä. Valitsin numeron 172. Tehtävän anto where was this picture taken. Aukesi kuva eiffel tornista. Etsin kuvan tiedoista GPS. Siinä löytyi osoite missä kuva on otettu. Oikea vastaus oli Las Vegas. 

C.)
tJ,?xW6@2N8T.5qQ*aL?4(4d496N7X\^

C ratkaise PortSwigger Labs: Lab: SQL injection vulnerability in WHERE clause allowing retrieval of hidden data. Muutetaan urlia rikkomalla tietokantalause urlissa hakemalla ‘OR+1+=1—  . C ratkaistu.

Lopetus 15:30
