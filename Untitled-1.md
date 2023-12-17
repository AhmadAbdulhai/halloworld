ReadMe:


Um Code aus Visual Studio Code (VS Code) in Git einzuchecken, folge diesen Schritten:

Git Repository Initialisieren: Falls dein Projekt noch kein Git-Repository ist, musst du eines erstellen. Öffne das Terminal in VS Code (normalerweise mit Ctrl + ) und führe den Befehl git init im Wurzelverzeichnis deines Projekts aus.

Änderungen Stagen: Nachdem du Änderungen an deinen Dateien vorgenommen hast, musst du diese Änderungen zum Staging-Bereich hinzufügen. Du kannst dies tun, indem du im "Source Control"-Panel von VS Code die gewünschten Dateien auswählst und auf "Stage Changes" (das "+" Symbol) klickst.

Commit Message Hinzufügen: Nachdem du die Änderungen gestaged hast, musst du einen Commit erstellen. Gib eine aussagekräftige Commit-Nachricht im "Source Control"-Panel ein und klicke auf das Häkchen ("Commit") oder führe im Terminal git commit -m "Deine Nachricht" aus.

Remote-Repository Hinzufügen: Falls du noch kein Remote-Repository (wie GitHub, GitLab, Bitbucket) verbunden hast, füge es hinzu mit git remote add origin DEINE_REPOSITORY_URL.

Code Einchecken (Push): Schließlich, um deinen Code in das Remote-Repository hochzuladen (einzuchecken), führe den Befehl git push origin DEIN_BRANCH aus. Wenn es dein erster Push ist, verwende git push -u origin DEIN_BRANCH.       
Fertig!
