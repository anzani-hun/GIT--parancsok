# CRUD műveletek!

``Create -> POST``
``Read -> GET``
``Update -> PUT-PATCH``
``Delete -> DELETE``



# GITHUB

##
Új Git repository létrehozása. A git init parancs létrehoz egy új Git repositoryt a jelenlegi mappában.

`git init`

---

Egy távoli repository klónozása a helyi gépre.

`git clone <repository URL>`

---


Megmutatja a munkamenet aktuális állapotát, azaz az új, módosított és törölt fájlokat.

`git status`

---


új fájlok hozzáadása a repohoz: [A git add parancs hozzáadja a módosított fájlokat a következő commit-hoz. Ezután azok készen állnak a commit-ra.]

`git add <filename.txt>`

---

A staging area tartalmának mentése a lokális repository-ba egy commit-ként (hozzáadás, módosítás után commitolhatjuk a változást):
A git commit parancs elmenti a fájlok aktuális állapotát a helyi repositoryba, és hozzárendel egy egyedi azonosítót a változtatásokhoz.
Ezenkívül lehetőséget ad arra, hogy egy üzenetet is adjunk a commit-hoz, amely részletesen leírja a változtatásokat.

`git commit -m <commitüzenet>`

---

Lokális commit-ok feltöltése a távoli repository-ba.
A git push parancs feltölti a lokális repository-ban található változtatásokat.
`git push`

---

A távoli repository-ban lévő változások letöltése és merge-elése a lokális munkamappába.

`git pull`

---

A git branch parancs létrehoz egy új ágat a projektben. Az ág lehetővé teszi, hogy párhuzamosan dolgozhassunk több funkcióval, majd ezeket a változtatásokat a fő ágba egyesítsük.

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

---

Az aktuális munkakönyvtár és commit közötti eltérést (mi változott) mutatja meg.

`git diff`


