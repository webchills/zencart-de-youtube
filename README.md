# zencart-de-youtube

YouTube auf Artikeldetailseite 1.4 für Zen Cart 1.5.5 deutsch

Mit dieser Erweiterung können YouTube Videos auf der Artikeldetailseite integriert werden.
Das Video wird responsiv eingebunden und enthält danach keine "passenden" Videos.
In der Artikelbearbeitung steht ein neues Feld zur Verfügung, in das einfach der jeweilige YouTube Kurzcode eingetragen wird.
Es ist also nicht nötig den kompletten Einbettungscode zu verwenden und die Anzeige des Videos ist frei positionierbar.


Installation und Verwendung:

Dieses Modul ist nur für Zen Cart 1.5.5 deutsch geeignet.

Für den Einbau dieses Moduls sollten Sie über folgende Werkzeuge verfügen:

1) Ein guter Texteditor.
Damit ist nicht das in Windows enthaltene Notepad oder Microsoft Word gemeint.
Sie benötigen einen Texteditor, der utf-8 versteht und auch im Format utf-8 ohne BOM abspeichern kann.
Empfehlung: UltraEdit (kostenlose 30 Tage Testversion verfügbar)
Ebenfalls gut geeignet ist der kostenlose Texteditor Notepad++

2) Ein Tool zum Vergleichen von Dateien
Bei der Installation dieses Moduls ist es erforderlich, dass Sie den Inhalt einiger Ihrer bestehenden Zen Cart Dateien mit dem Inhalt der neuen Moduldateien vergleichen und die Änderungen zusammenführen ("mergen").
Empfehlung: BeyondCompare (kostenlose 30 Tage Testversion verfügbar)
Ebenfalls gut geeignet ist das kostenlose Programm WinMerge

Empfehlung:

Dieses Modul erst in einem Testsystem einbauen und dort konfigurieren/testen und endgültig an die eigenen Wünsche anpassen. 
Erst dann in einem Liveshop einsetzen! Sichern Sie unbedingt alle Dateien Ihres Shops per FTP und sichern Sie die Datenbank mit phpMyAdmin oder anderen geeigneten Tools!
WICHTIG
Vor dem Einbau dieser Änderungen:
BACKUP von Shop und Datenbank machen!
Keine Haftung, Verwendung auf eigene Gefahr!
BACKUP gemacht? Ok, dann weiterlesen...

Die Installation erfolgt in folgenden Schritten. Halten Sie diesen Ablauf ein!


1.
Die Datei install.sql im Ordner SQL mit einem Texteditor öffen und den Inhalt kopieren

2.
Zen Cart Administration öffnen und unter Tools > SQL Patches installieren den Inhalt ins Feld hineinkopieren und absenden.

3.
Im Ordner GEAENDERTE DATEIEN alle Ordner namnes DEINTEMPLATE auf den Namen des im Shop aktiven Templates umbenennen.
Den Ordner DEINADMIN auf den namen Ihres Adminverzeichnisses umbenennen
Wenn Sie Zen Cart 1.5.5 gerade frisch installiert haben und noch keinerlei Änderungen an den Dateien vorgenommen haben, können Sie nun alle Dateien/Ordner aus dem Ordner GEAENDERTE DATEIEN in der vorgegebenen Struktur in die Zen Cart Installation hochladen. Dabei werden dann etliche Dateien überschrieben.
Wenn Sie Zen Cart 1.5.5 schon länger im Einsatz haben und schon einmal Änderungen an Dateien vorgenommen oder andere Module eingebaut haben, dann laden Sie die Dateien keinesfalls einfach hoch.
Vergleichen Sie alle Dateien im Ordner GEAENDERTE DATEIEN mit den entsprechenden Dateien in Ihrem Shop und nehmen Sie die Änderungen manuell per WinMerge oder BeyondCompare vor.
Dann spielen Sie die geänderten Dateien in der gezeigten Struktur ein.

4.
Beim Bearbeiten eines Artikels steht nun unten das Feld YouTube Code zur Verfügung.
Immer nur die kurze ID des Videos verwenden
Lautet der Link zum Video z.B.
https://www.youtube.com/watch?v=tBHMzCOn2Sk
Dann wäre einzugeben:
tBHMzCOn2Sk
