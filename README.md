# SPA - Domaća zadaća 2

## Rok za predaju:	1. srpnja 2017, 23:59:59
### Upute za predaju rješenja: 
- Rješenje se predaje pull requestom na projekt https://github.com/racspa/spa2017dz2
- Rješenje predano nakon gornjeg roka neće se uvažiti
- Naziv pull requesta treba biti u obliku *SPA-Z02-ImePrezime-ImeAsistenta* (npr *SPA-Z02-ImePrezime-dbele* ili *SPA-Z02-ImePrezime-mzagar*)
- Solution s projektima 'zadatak1' i 'zadatak2' kreirajte u direktoriju 'rjesenje'


## Zadatak 1: I4, 2 boda
U prilogu je aplikacija kakvu trebate napraviti, a sastoji se od sljedećeg: prilikom pokretanja aplikacije korisnik unosi redak i stupac početne točke A i redak i stupac krajnje točke B (broj retka ide od 1 do 20, a broj stupca od 1 do 40). Nakon toga, aplikacija treba osmisliti put od točke A do točke B i svakih 100 milisekundi iscrtati gdje se trenutno nalazimo. Točka A i točka B se mogu nalaziti na bilo kojem dopuštenom mjestu (isprobajte kako radi aplikacija u prilogu s, primjerice, A = 1, 1 i B = 20, 40, te kako radi s A = 20, 20 i B = 10, 10).

## Zadatak 2: I6, 2 boda
U prilogu je aplikacija kakvu trebate napraviti, a sastoji se od sljedećeg: igraća površina je velika 30x25 znakova i potpuno je okružena znakovima '#'. Odmah po pokretanju treba iscrtati igrača (znak 'X') na sredini igraće površine te voćku (znak 'D') na slučajnom položaju (ali nikako ne na istom položaju na kojem je igrač). Nakon toga, igraća površina, igrač i voćka se ponovno iscrtavaju svakih 100 milisekundi. Igrač se inicijalno pomiče udesno, a korisnik može koristiti tipke 'a', 's', 'd' i 'w' kako bi promijenio smjer kretanja igrača. Cilj igrača je doći do voćke, čime se ona pojavljuje na nekom drugom slobodnom mjestu. Igra završava ili pritiskom tipke 'k' ili kad igrač udari u rub igraće površine. 

Savjeti:
- Od nestandardnih zaglavlja se preporuča uključiti: Windows.h, conio.h, ctime.
-  Kad želimo dohvatiti koju tipku je korisnik zadnju pritisnuo, možemo koristiti:
   ```
   char get_user_input() {
     if (_kbhit()) {
       return _getch();
     }
     return 0;
   }
   ```

### Koraci za kreiranje pull requesta
- kreirajte github account
- ulogirajte se na github
- otvorite url projekta https://github.com/racspa/spa2017dz2 i kreirajte kopiju na svom github racunu klikom na gumb 'Fork' 
- rijesite zadatak i push-ajte promjene u svoj spa2017dz2 projekt repozitorij (mozete commit-ati i push-ati koliko promjena god zelite)
- kada ste rijesili zadatak predajte ga kreiranjem pull requesta sa svog projekt natrag u projekt racspa/spa2017dz2
- naziv pull requesta zadajte prema gore navedenim uputama
- upute za kreiranje pull requesta iz kreiranog forka: https://help.github.com/articles/creating-a-pull-request-from-a-fork/
