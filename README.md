# git

# Sta je git?

Git(softver) je sistem kontrole verzija za praćenje promena u racunarskim fajlovima i za koordinisan rad više ljudi na tim fajlovima. Prednosti gita su njegova brzina, mogucnost rada vise ljudi i nelinearan rad.

# Sta je github?

Github je sajt koji koristi git kako bi omogucio da ljudi postavljaju projekte , razmenjuju ih,istovremeno rade na njima, a pored toga github omogucava I kontrolu pristupa, proveru gresaka…

# Osnovne komande github-a

•	git add dodaje fajl u staging area 

git add project

•	git log omogucav pregled ranijih verzija projekta te grane

git log

•	git init kreira novo git skladiste ili ponovo pokrece vec postojace

git init C:/Users/Radni/Desktop

•	git clone kreira kopiju postojaceg projekta

git clone https://github.com/darkwolf2442/git

•	git commit cuva promene u skladistu

git commit - m "first file"

•	git status prikazuje stanje radnog direktorijuma I sve fajlove koji treba da budu prilozeni

git status

•	git revert vraca ofredjene promene iz proslosti

git revert project~1

•	git reset vraca skladiste na stanje iz proslosti

git reset zadatak.cs

•	git diff prikazuje sve razlike izmedji sacuvanog fajla I onih koji nisu jos prilozeni

git diff

# Kreiranje , grananje, spajanje

Da bi se kreirao novi projekat moramo kliknuti na new repository (ili ako zelimo da ucitamo vec postojeci kliknemo import repository), izabrati ime I opis projekta, odluciti da li ce biti private ili public. 

![image](https://user-images.githubusercontent.com/119406841/204519925-f68aebc3-9a28-4dca-8d1f-d7fefe112b86.png) 
![image](https://user-images.githubusercontent.com/119406841/204520090-440c4b7e-ee00-479c-9a8d-d44de4e0ee2a.png)

Git ima dobru kontrolu grananja. Mozemo da imamo puno lokalnih grana koje nisu medjusobno zavisne( promene na jednoj ne uticu na drugu granu). Te grane pored toga sto mogu da se prave I brisu mogu I da se spajaju. 

•	git branch prikazuje sve postojace grane(kreira ili brise)

git branch my2.6.14 v2.6.14

•	git merge spaja istoriju navedene sa trenutnom granum

git merge main grana-2

•	git pull uzima I spaja promene sa trenutnog skladista sa navedenim granama

origin next

•	git push obavlja promene na glavnom skladistu pomocu promena na trenutnom

origin master
# SSH

SSH (Secure Shell Protocol) je mrezni protokol za bezbedno upravljanje mreznim uslugama preko nezasticene mreze. možete da se povezete i potvrdite identitet sa udaljenim serverima i uslugama. Pomocu ssh kljuceva moze se povezati na github bez snabdevanja imena I licnih tokena prstupa. Najistaknutije aplikacije su prijavljivanje sa daljine I izvrsavanje sa komandne linije.

![image](https://user-images.githubusercontent.com/119406841/204524730-d54014d8-fd36-43e1-a3a5-da1d14233449.png)



