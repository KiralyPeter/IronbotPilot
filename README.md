# IronbotPilot

A Pilot Projekt célja, hogy egy mintát adjon és "kézzel fogható" legyen egy elképzelés. Jelen állapotban csak egy "mockup", nem működő felületi elemekkel.

A példában a fő hangsúly a CSS GRID technológián van.\
[Mozilla - Introduction to CSS Grid Layout](https://mozilladevelopers.github.io/playground/css-grid/)

Inicializálás 'git clone' után:
```
npm init
```

Ez telepíti a lite-server-t és a bootstarp-et:
```
npm install 
```

IronbotPilot Git Repo klónozása: 
```
git clone https://github.com/KiralyPeter/IronbotPilot.git
```
Lokál repozitori szinkronizálása a GitHub-on lévő verzióval 
(arra az esetre, ha a GitHub-on lévő verzió idő közben változott volna..)
```
git pull origin master
```
Új branch létrehozása
```
git checkout -b <branch név>
```
Ezt az új branch-et kellene fel 'push'-olni origin-re.\
GitHub-on lesz a merge (normál esetben megfelelő mérlegelés után...)

Az új branchj push-olása GitHub-ra (origin-re):
```
git push origin <branch név>
```