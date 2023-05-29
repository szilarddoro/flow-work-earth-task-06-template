# 6. feladat

1. Hozz létre egy repositoryt a GitHub-on a saját felhasználód alá, aminek a neve `flow-work-earth-task-06` legyen.
2. Klónozd le a saját gépedre ezt a repositoryt a `~/flow/git` mappán belülre a `task-06` mappába. Fontos, hogy ne azt, amit az 1. lépésben létrehoztál, hanem azt, amit a `szilarddoro` felhasználó alatt találsz! (`git clone git clone https://github.com/szilarddoro/flow-work-earth-task-06-template task-06`)
3. Változtasd meg az `origin` URL-jét, hogy az legyen, amit az 1. lépésben létrehoztál. (`git remote set-url origin <url>`)
4. Pushold fel az aktuális tartalmat a GitHub-ra. (`git push -u origin main`)
5. Készíts egy új branchet, aminek a neve legyen: `product-id-fixes`.
6. A `termekek` mappában lévő fájlok nevei nem megfelelőek. A fájlok nevei csak bizonyos esetekben tartalmazzák a termékek azonosítóit. A fájlok neveit javítsd ki úgy, hogy a fájlok nevei tartalmazzák a termékek azonosítóit!
7. Commitold a változtatásaidat.
8. Pushold fel a változtatásaidat a GitHub-ra. (`git push -u origin product-id-fixes`)
9. Készíts egy új Pull Requestet a `product-id-fixes` branchről `main` branchre.
10. Mergeld be a Pull Requestet a GitHub felületén.
11. Lokálisan frissítsd a `main` branchet. (`git checkout main && git pull`)
