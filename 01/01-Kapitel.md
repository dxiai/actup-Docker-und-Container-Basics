# 1. Docker - Installationsanleitung

Als ersten Schritt müssen Sie die Docker-Software auf Ihrem Computer installieren. Dieses Kapitel beschreibt im Detail die Installation von Docker unter Windows, macOS und Linux. Obwohl Docker eigentlich aus der Linux-Ecke kommt, gelingt die Installation unter Windows und macOS wesentlich einfacher. Unter Linux gibt
es je nach Distribution unzählige Varianten und Sonderfälle, die eine kompakte
Darstellung schwierig machen. In diesem Kurs gehen wir auf die Distributionen
Debian/Ubuntu, Fedora, Oracle Linux (stellvertretend für die ganze RHEL-Familie)
sowie Raspberry Pi OS ein.

Beachte, um den Docker zu installieren und zu nutzen ist keine Registrierung erfoderlich. Man benötigt erst einen Docker-Account, wenn man Images im Docker Hub anbietet. 

## 1.1 DockerHub und Docker Desktop

FürWindows und macOS bietet Docker den sogenannten Docker Desktop an. Das ist
ein Komplettpaket, das neben der Docker-Infrastruktur auch eine grafische Benutzeroberfläche
umfasst.
Unter Linux müssen Sie auf den Docker Desktop verzichten. Allzu schlimm ist das
nicht: Egal, ob Sie untermacOS,Windows oder Linux arbeiten – in jedem Fallwerden
Sie Docker überwiegend durch Kommandos steuern. Diese Kommandos funktionieren
auf allen Plattformen gleich. Der Docker Desktop vereinfacht die Installation,
bietet plattformspezifische Konfigurationsmöglichkeiten (von denen viele für Linux
gar nicht relevant sind) und bietet in manchen Fällenmehr Bequemlichkeit. Das Programm
stellt Windows- oder macOS-Fans aber keine echten Zusatzfunktionen zur
Verfügung.

Info ganz am Rande: Es ist bekannt, dass Linux trotz der fehlenden Benutzeroberfläche
die beste Plattform für Docker ist. Das hat damit zu tun, dass Docker einen Linux-
Kernel voraussetzt. Unter Linux ist diese Voraussetzung immer gegeben. Linux und
Docker teilen sich den Speicher, den Prozessraum usw. Unter macOS und Windows
wird der Kernel dagegen durch ein Virtualisierungssystem bzw. durch WSL ausgeführt
und stellt in einemgewissen Ausmaß immer einen Fremdkörper dar.


## 1.2 Installation unter Windows

Die aktuelle Version von Docker Desktop finden Sie hier zum Download:
https://docs.docker.com/docker-for-windows/install

Die Installation verläuft in der Regel vollkommen unkompliziert. Keine einzige
Option ist einzustellen! Während der Installation wird automatisch WSL2 aktiviert,
falls dies auf Ihrem Rechner noch nicht der Fall sein sollte. Nach der Installation finden Sie auf dem Desktop bzw. im Startmenü einen Eintrag zum Start von Docker
Desktop. Dieses Programm bietet Ihnen beim ersten Mal die Möglichkeit, eine
Einführungs-Tour zumachen.

### Voraussetzungen für Windows Benutzer 
- Docker wird in Kombination mit WSL2 verwendet. 
- Dazu benötigen Sie eine einigermassen aktuelle 64-Bit-Installation von Windows 10 Home, Pro oder Enterprise. 
- Ihr Rechner benötigt mindestens 4 GB RAM. (Für den Entwickleralltag empfehlen wir Ihnen aber 16 GB.)
- Die Virtualisierungsfunktionen der CPU müssen aktiviert sein.

### Übung
1. Installiere den Docker Desktop je nach deinem Betriebssystem
2. Rufe deine Eingabeaufforderung / PowerShell in cmd.exe oder das Windows Terminal auf und schreibe **docker version**.

3. Um zu testen, dass Docker wirklich funktioniert, können Sie das Mini-Linux-System
Alpine als Container starten. Mit ping testen Sie, ob die Netzwerkverbindung nach
außen funktioniert. exit beendet den Container, der aufgrund der Option --rm auch
sofort wieder gelöscht wird:





## Wiki
- Was ist eine Linux Distribution?
- Nenne einige bekannte Linux Distributionen? Debian/Ubuntu, Fedora, Oracle Linux und Raspberry Pi OS

