# GITHUB

##
Új Git repository létrehozása.

`git init`

---

Egy távoli repository klónozása a helyi gépre.

`git clone <repository URL>`

---


Megmutatja a munkamenet aktuális állapotát, azaz az új, módosított és törölt fájlokat.

`git status`

---


új fájlok hozzáadása a repohoz:

`git add <filename.txt>`

---

A staging area tartalmának mentése a lokális repository-ba egy commit-ként (hozzáadás, módosítás után commitolhatjuk a változást):

`git commit -m <commitüzenet>`

---

Lokális commit-ok feltöltése a távoli repository-ba.

`git push`

---

A távoli repository-ban lévő változások letöltése és merge-elése a lokális munkamappába.

`git pull`

---

Megjeleníti a lokális branch-ek listáját.

`git branch`

---

Átváltás egy másik branch-re.

`git checkout <branch-name>`

---

Kilistázza az összes távoli repository-t és azok URL-jeit.

`git remote -v`

---

A commit történet megjelenítése.

`git log`
