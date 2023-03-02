# Commands executed during this task

$ mkdir dir-name - koristimo da kreiramo folder

$ touch file-name - koristimo da kreiramo file

$ ssh username@bandit.labs.overthewire.org -p 2220 - konekcija pomocu ssh dodavanjem specificnog username-a i porta

$ cat readme - prikaz sadrzaja readme file-a

$ cat ./-   - za citanje sadrzaja file-a specificnog naziva

$ logout - za zatvaranje konekcije

$ ls - za ispisivanje postojecih datoteka u trenutnom folderu u kojem se nalazimo


$ cat "spaces in the filename" - moramo koristiti navodnike za fajlove koji imaju razmak u nazivu

$ cd inhere - da se prebacimo u inhere folder

$ ls -a  - prikaz hidden fajla

$ cat .hidden - prikaz sadrzaja hidden fajla


$ ls -l 

$ file ./-file*  -* je umjesto bilo kojeg postojeceg znaka, bitno je da je prije njega -file, ispisuje se tip podataka, trazimo ascii jer je to tip podataka koji je citljiv covjeku

$ cat ./-file07 - ispis sadrzaja fajla pod nazivom -file07
lrIWWI6bB37kxfiCQZqUdOIYfr6eEeqR

$ find -readable -size 1033c ! -executable  - nalazi file u inhere folderu koji je readable, velicine 1033 bytes i not executable
$ cat ./maybehere07/.file2 - citamo sifru
P4L4vucdmLnm8I7Vl7jG1ApGSfjYKqJU

$ find / -type f -user bandit7 -group bandit6 -size 33c 2>/dev/null - nalazak fajla (type f), posjedovan od strane user bandit7, posjedovan od strane grupe bandit6 i velicine 33, 2>/dev/null krije errore permission denied

$ cat (lokacija) - citanje sadrzaja odnosno sifre

z7WtoNQU2XfjmMtWA8u5rN4vzqu4v99S

$ cat data.txt | grep millionth - grep koristeno za pronalazenje i "matching"

TESKZC0XvTetK0S9xNwm25STk5iWrBvP

$ sort data.txt | uniq -u - sort vrsi sortiranje podataka u data.txt a -u nalazi unikatne vrijednosti odnosno one koje se pojavljuju samo jednom. -u se vecinom koristi u paru sa sort.
EN632PlfYiZbn3PhVK3XOGSlNInNE00t

$ strings data.txt | grep === - nalazi stringove human readable (strings), filtrira = pomocu grep

G7w8LIi6J3kTb8A7j9LgrywtEUlyyp6s

$ cat data.txt - prikaz podataka it txt fajla

$ base64 -d data.txt - binary-to-text encoding scheme (base64), -d za dekodiranje

6zPeziLdR2RKNdNYFNb6nVCKzphlXHBM