# h1
Homework for course taught by Tero Karvinen

 Tehtävän tekeminen alkaa alkaa 25.10.2023 klo 13:30.  Tein tehtäviö yhdessä kurssitoverini Alisa Ahokkaan kanssa. 

Level 0

The goal of this level is for you to log into the game using SSH. The host to which you need to connect is bandit.labs.overthewire.org, on port 2220. The username is bandit0 and the password is bandit0. Once logged in, go to the Level 1 page to find out how to beat Level 1.

Annoin command prompt commandin ssh bandit0@bandit.labs.overthewire.org -p 2220 



<img width="796" alt="Screenshot 2023-10-25 at 13 41 06" src="https://github.com/AkiAleksi/h1/assets/112399816/35e42af5-adf4-449f-a35b-86d8351da70a">





Sen jälkeen annoin salasanan, joka oli annettu tehtäcän annossa eli bandit0.
<img width="603" alt="Screenshot 2023-10-25 at 13 41 15" src="https://github.com/AkiAleksi/h1/assets/112399816/731730d4-49a5-4a78-a19c-61a1d840ced7">


Kirjautuminen sisään onnistui.  



<img width="551" alt="Screenshot 2023-10-25 at 13 33 17" src="https://github.com/AkiAleksi/h1/assets/112399816/364ea0d8-9f74-4bfa-ad4e-cd0c516b0338">


Level 0 suoritettu.

The password for the next level is stored in a file called readme located in the home directory. Use this password to log into bandit1 using SSH. Whenever you find a password for a level, use SSH (on port 2220) to log into that level and continue the game.

Syötin ls komennon. Sen jälkeen cat readme. Sain vastaukseksi NH2SXQwcBdpmTEzi3bvBHMM9H66vVXjL.  Kokeilin syöttää salasanan ei toiminut.

<img width="762" alt="permission denied lvl1" src="https://github.com/AkiAleksi/h1/assets/112399816/a4ec0299-3187-4c0b-b4ab-06e66c7fdf96">







Annoin komennon exit. Sen jälkeen annoin komennon. ssh bandit1@bandit.labs.overthewire.org -p 2220. Syötin salasanan NH2SXQwcBdpmTEzi3bvBHMM9H66vVXjL. Pääsin kirjautumaan sisään. 


<img width="653" alt="Screenshot 2023-10-25 at 13 59 25" src="https://github.com/AkiAleksi/h1/assets/112399816/8af814d9-7a54-4123-b481-fd955fae12ef">

Level 1 suoritettu.

Level 2

The password for the next level is stored in a file called - located in the home directory

Ls komennolla sain vastaukseksi -. Kokeilin avata komennolla cat -. Ei toiminut. Googletin ja piti avata cat < - komennolla. Sain vastaukseksi rRGizSaX8Mk1RTb1CNQoXTcYZWU6lgzi. 

<img width="360" alt="level 2 kuva 1" src="https://github.com/AkiAleksi/h1/assets/112399816/98793787-3a4b-4af2-8d8d-ffb3edba7de5">



Annoin komennon exit. Komento ssh bandit2@bandit.labs.overthewire.org -p 2220. Sen jälkeen annoin salasanan rRGizSaX8Mk1RTb1CNQoXTcYZWU6lgzi. 

<img width="712" alt="level 2 kuva 2" src="https://github.com/AkiAleksi/h1/assets/112399816/29ec60d2-29ce-47f0-841d-08702287b5b8">



Kirjauduin sisään onnistuneesti. 

<img width="824" alt="level 2 kuva 3" src="https://github.com/AkiAleksi/h1/assets/112399816/b9fcebbe-f193-402a-bcdf-e8f4220028e4">



Ratkaistu level 2.

Klo 14:23 25.10.2023. a kohta ratkaistu.

B.) Kohta

Päätin suorittaa Challenge.fi ssä yksi tehtävä. Valitsin numeron 172. Tehtävän anto where was this picture taken.

<img width="652" alt="b kohta" src="https://github.com/AkiAleksi/h1/assets/112399816/3dfcf55d-02b0-4726-b9cd-baaaedf46f44">


Aukesi kuva eiffel tornista.


Etsin kuvan tiedoista GPS. Siinä löytyi osoite missä kuva on otettu.

<img width="339" alt="Screenshot 2023-10-25 at 14 54 43" src="https://github.com/AkiAleksi/h1/assets/112399816/eebfe26d-14b7-433b-ac18-c0ca2fc6d821">


Oikea vastaus oli Las Vegas. 

<img width="602" alt="B kohta ratkasiu" src="https://github.com/AkiAleksi/h1/assets/112399816/906cd1cd-de04-4e6a-aba1-e91ccc84b73e">

C.)
tJ,?xW6@2N8T.5qQ*aL?4(4d496N7X\^

C ratkaise PortSwigger Labs: Lab: SQL injection vulnerability in WHERE clause allowing retrieval of hidden data. Muutetaan urlia rikkomalla tietokantalause urlissa hakemalla ‘OR+1+=1—  . C ratkaistu.

Lopetus 15:30
