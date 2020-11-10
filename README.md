# Übung 7
Quellcode der Vorlesung: https://github.com/fdiba-inf/vorlesung
## Repl.it öffnen
Bevor Sie die Taste _"Work in Repl.it"_ klicken, öffnen Sie https://repl.it/auth/github/get, um sicherzustellen, dass Sie in repl.it angemeldet sind.
## Aufgabe 1. Palindrom
Ändern Sie die Klasse _Palindrome_ im Paket _exercise6_. 
Der Benutzer soll eine Zahl eingeben.
Zuerst wird überprüft, ob die Zahl großer Null ist (benutzen Sie das Schlüsselwort _assert_).
Dann wird bestimmt, ob die Zahl Palindrom ist (wenn rückwärts gelesen, erscheint dieselbe Zahl z.B. 1221, 242).
Ausgabe:
``` 
Palindrome: <true/false>
``` 
## Aufgabe 3. Passwortüberprüfung
Ändern Sie die Klasse _PasswordCheck_ im Paket _exercise6_. 
Sie soll die Korrektheit eines Passworts überprüfen. 
Der Benutzer soll ein Password eingeben, bis es korrekt ist:
* ist mindestens acht Zeichen lang
* besteht nur aus Buchstaben und Ziffern (_Character.isLetterOrDigit(symbol)_)
* enthält mindestens zwei Ziffern (_Character.isDigit(symbol)_)

Die folgende Nachricht wird am Ende in der Konsole ausgegeben:
``` 
Password valid!
``` 
## Achtung! Achtung! Achtung!
Wenn Sie alle Aufgaben gemacht haben, sollen Sie die Lösungen in _GitHub_ hochladen. 
Wenn "Version Control" nicht verfügbar ist, geben Sie die folgenden Befehle in die Konsole ein:
``` 
git pull
git add .
git commit -m "Some message"
git push
``` 
