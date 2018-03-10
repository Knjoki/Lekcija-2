## Lekcija 2 

**Fahr to Celsius **

 

 - U lekci 2 smo napravili program koji pretvara Celzijuse u Faradejte. Program smo napisali koristeci `for `petlju.
 Kada kod `for(int i=min ;i<=max; i=i+20)` pokusamo kompajlirati koristeci standard **C89 ** kompajler ce nam javiti gresku. **C89 ** standard ne omogucuje deklarisanje varijabli unutar zagrada `for` petlje. 
 - Da bi nam dio koda gore naveden u `for` petlji komplajler mogao prevesti potrebno je da promjenimo standard tako sto koristimo nardebu **-std=c99**. Ovom naredbom smo postavili nas kompajler da radi na standardu c99.
 
 - Kada smo utvrdili da nas program ne javlja gresku htjeli smo prebaciti na github.
 Da bi program prebacili na github, koristimo se sljedecim usputstvima :
 Potrebno je prvo da na githubu napravimo novi repozitori.
Kada to zavrsimo  otvorimo terminal, potrebno je da se prvo navigiramo na direktorij gdje nam je snimljen fajl koji zelimo prebaciti na github koristeci naredbu  `git clone URL .` 

 Nakon toga koristimo naredbu  koristimo naredbu  `git init `kako bi instalirali repozitorij. 
 Nakon toga potrebno je da narebom `git status ` utvrdimo da li imamo spremljenih commita. 
 Sljedece sto je potrebno jeste da napravimo nasu konfiguraciju naredbama `gir config user.name "Nase ime" i git commit user.email "nas@email.com`  Dalje koristeci se naredbom git add "Fajl koji zelimo dodati", te taj fajl spremimo kao commit naredbom `git commit -m "Ime"`.
 Nakon toga koristeci naredbu `git push origin master ` ` prebacujemo nas fajl na github.
 

> git clone URL
> git init 
> git status
> git user.name "Nase ime " 
> git user.email "nas@email.com
> git commit -m "Naziv"
> git push origin master 


 





<!--stackedit_data:
eyJoaXN0b3J5IjpbMTE2MzcyMDUzMl19
-->