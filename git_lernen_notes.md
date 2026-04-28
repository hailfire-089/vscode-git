## Git Tutorial in 40 Min
URL: [Git Tutorial - In 40 Minuten Git lernen für Anfänger (2026)](https://www.youtube.com/watch?v=uGLQF2kUwOA)

### Was ist Git?
- Eine Versionsverwaltung
- Zeilenbasiert
### Git installieren und konfigurieren
Git Client (ist auf Mac schon installiert) 
#### Befehle für die Konfiguration im Terminal
**Git Version prüfen**
`git --version`
**Nutzernamen abfragen**
`git config --global user.name`
**Nutzernamen vergeben**
`git config --global user.name "Rapha auf Git"`
**E-Mail Adresse abfragen**
`git config --global user.email`
**E-Mail Adresse vergeben**
`git config --global user.email "raphael.knappe@posteo.de"`
#### Git Repository initialisieren
**Ordner erstellen**
`mkdir ordner-name`
**Git Repository initialisieren**
*Wenn man sich im Ordner befindet*
`git init`
**Status des aktuellen Git Repository prüfen**
`git status`
**Datei im Ordner erstellen**
`touch README.md`
![[Pasted image 20260427101124.png]]
*Jeder Datei muss gesagt werden, dass sie zum Projekt gehört und nachvollzogen wird.*
**Datei zu Git Repository hinzufügen** (Datei stagen) 
*Damit wird die Datei "gestaged"*
`git add README.md`
![[Pasted image 20260427101306.png]]
**Datei comitten** 
*Danach muss die Änderung dann in Historie übernommen werden. Das macht man mit einem Commit mit einer Message, daher -m*
`git comitt -m "Hallo, diese Datei ist neu"
![[Pasted image 20260427102402.png]]
*Nun ist die Datei auf main in die Git Historie übernommen worden. *
## Git Repository Remote - Github & Bitbucket
### Git Push
*Änderungen vom lokalen Repository auf das Remote Repository speichern*
`git push`
*Änderungen vom Remote Repository auf das lokale Repository holen*
`git pull`

### Branches
*Ein Branch ist eine neue Version, neben der Hauptversion. *
`git branch feature_lokales-projekt`