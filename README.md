Vizsga során alkalmazott git parancsok

    - git init -> local repository (helyi gyűjtemény) inicializálása a projektünkben
    - git pull git@github.com:szabopeter92/git-vizsga0104.git -> távoli gyűjteményből (remote repository) letöltöm a fájlokat helyi gyűjteménybe
    - git status -> a gyűjtemény státuszának ellenőrzése. Tájékoztat az utoljára módosított/létrehozott fájlokról
    - git add . -> hozzáadjuk a fájlokat a gyűjteményhez
    - git branch console -> új ág létrehozása, melynek neve console lesz
    - git checkout console -> átváltom az ágamat main-ről console-ra
    - git commit -m "milyen változtatásokat hajtottunk végre" -> rögzítjük az eddigi változtatásokat egy verzióban
    - git remote add origin -> távoli gyűjtemény megadása
    - git push -u origin main console -> main ill. console ág feltöltése a távoli gyűjteménybe