# Verziókezelés - git
## Helyi repo létrehozása

- Inicializálás, megszületik a helyi repo:
    >git init
- Ellenőrzés, mi módosult?
    >git status
- minden fájlt amiben történt módosulás sszeretnék az új verzióban menteni:
    >git add .
- az előkészített adatok (commit előtt) ellenőrzöm (a stage-n)
    >git status
- felhasználónév és email beállítása:
    > git config user.name .......
    > git config user.email ......
- új verzió megszületése( commit):
    > git commit -m "First commit"
- ellenőrzés:
    > git status

## Távoli repo létrehozása, összekapcsolása
- GitHub új repo létrehozása
- Összekapcsolás: 
    > git remote add origin https://token@github.com/CrashizVok/Suli.git
- első push
    >git push -u origin master
- további push
    >git push