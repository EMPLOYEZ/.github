<a name="readme-top"></a>
<!-- PROJEKT SHIELDS -->
[![Contributors][contributors-shield]][contributors-url]
[![Forks][forks-shield]][forks-url]
[![Stargazers][stars-shield]][stars-url]
[![Issues][issues-shield]][issues-url]



<!-- PROJEKT LOGO -->
<br />
<div align="center">
  <a href="https://github.com/EMPLOYEZ/EMPLOYEZ/">
    <img src="https://raw.githubusercontent.com/EMPLOYEZ/design/main/Logos/Logo.png" alt="Logo" width="600">
  </a>

<h3 align="center">EMPLOYEZ</h3>

  <p align="center">
    EMPLOYEZ - Mitarbeiterverwaltungsprogramm
    <br />
    <a href="https://github.com/EMPLOYEZ/documents/"><strong>Zur Dokumentation »</strong></a>
    <br />
    <br />
    <a href="https://github.com/EMPLOYEZ/EMPLOYEZ/">Demo ansehen</a>
    ·
    <a href="https://github.com/EMPLOYEZ/EMPLOYEZ/issues">Bug melden</a>
    ·
    <a href="https://github.com/EMPLOYEZ/EMPLOYEZ/issues">Feature anfragen</a>
  </p>
</div>



<!-- INHALTSVERZEICHNIS -->
<details>
  <summary>Inhaltsverzeichnis</summary>
  <ol>
    <li>
      <a href="#über-das-projekt">Über das Projekt</a>
      <ul>
        <li><a href="#erstellt-mit">Erstellt mit</a></li>
      </ul>
    </li>
    <li>
      <a href="#erste-schritte">Erste Schritte</a>
      <ul>
        <li><a href="#voraussetzungen">Voraussetzungen</a></li>
        <li><a href="#installation">Installation</a></li>
      </ul>
    </li>
    <li><a href="#verwendung">Verwendung</a></li>
    <li><a href="#projektstrukturplan">Projektstrukturplan</a></li>
    <li><a href="#kontakt">Kontakt</a></li>
  </ol>
</details>



<!-- ÜBER DAS PROJEKT -->
## Über das Projekt
### Was ist EMPLOYEZ?
EMPLOYEZ ist ein Mitarbeiterverwaltungsprogramm bestehend aus einer Personalakte, Stempeluhr, Zeiterfassung und den Zeitsummen.

![Mitarbeitererfassung][product-screenshot1]
![Stempeluhr][product-screenshot2]
![Zeiterfassung][product-screenshot3]
![Zeitsummen][product-screenshot4]

EMPLOYEZ Projektarbeit LBS4


<p align="right">(<a href="#readme-top">zurück</a>)</p>



### Erstellt mit
* [![C#]][C#-url]
* [![.NET]][.NET-url]
* [![Visual Studio]][Visual Studio-url]
* [![MySQL]][MySQL-url]
* [![GitHub]][GitHub-url]

<p align="right">(<a href="#readme-top">zurück</a>)</p>



<!-- ERSTE SCHRITTE -->
## Erste Schritte

Folgende Schritte werden notwendig sein, damit das Projekt lokal läuft.

### Voraussetzungen

Zur Vereinfachung benutzte IDE/Texteditor
* [![Visual Studio]][Visual Studio-url]
* [![Visual Studio Code]][Visual Studio Code-url]


Framework
* [![.NET]][.NET-url]

### Installation

1. Repo klonen
   ```sh
   git clone https://github.com/EMPLOYEZ/EMPLOYEZ.git
   ```
2. Eingeben der Datenbankverbindungsinformationen in DatabaseInfo.xml
   ```xml
   <?xml version="1.0" encoding="utf-8" ?>
    <DatabaseInfo>
	  <Server>server</Server>
	  <Database>database</Database>
	  <Username>username</Username>
	  <Password>password</Password>
   </DatabaseInfo>
   ```
3. Datenbank für Verbindung erstellen
   #### .NET Core CLI
   .NET CLI
   ```sh
   dotnet ef database update
   ```
   #### Visual Studio
   PowerShell
   ```sh
   Update-Database
   ```
4. Programm ausführen  und mit folgenden Standartbenutzer anmelden:
   ```sh
   Benutzer: admin
   Ohne Passwort
   ```

<p align="right">(<a href="#readme-top">zurück</a>)</p>



<!-- VERWENDUNG -->
## Verwendung

Für eine Anleitung zur Verwendung des Projektes, siehe [Dokumentation](https://github.com/EMPLOYEZ/documents/)

<p align="right">(<a href="#readme-top">zurück</a>)</p>



<!-- PROJEKTSTRUKTURPLAN -->
## Projektstrukturplan

- [X] Vorprojektphasen
- [X] Entwicklung
- [X] Projektmanagement
- [X] Dokumentation
- [X] Testing und Qualitätsmanagement

Siehe [Issues](https://github.com/EMPLOYEZ/EMPLOYEZ/issues) für eine Auflistung der Phasen.

<p align="right">(<a href="#readme-top">zurück</a>)</p>


<!-- KONTAKT -->
## Kontakt

Organisations-Link: [https://github.com/EMPLOYEZ](https://github.com/EMPLOYEZ)

<p align="right">(<a href="#readme-top">zurück</a>)</p>


<!-- LINKS & BILDER -->
[contributors-shield]: https://img.shields.io/github/contributors/github_username/repo_name.svg?style=for-the-badge
[contributors-url]: https://github.com/github_username/repo_name/graphs/contributors
[forks-shield]: https://img.shields.io/github/forks/github_username/repo_name.svg?style=for-the-badge
[forks-url]: https://github.com/github_username/repo_name/network/members
[stars-shield]: https://img.shields.io/github/stars/github_username/repo_name.svg?style=for-the-badge
[stars-url]: https://github.com/github_username/repo_name/stargazers
[issues-shield]: https://img.shields.io/github/issues/github_username/repo_name.svg?style=for-the-badge
[issues-url]: https://github.com/github_username/repo_name/issues
[product-screenshot1]: https://raw.githubusercontent.com/EMPLOYEZ/design/main/Modullayouts/Mitarbeitererfassung%20-%20Planung.png
[product-screenshot2]: https://raw.githubusercontent.com/EMPLOYEZ/design/main/Modullayouts/Stempeluhr%20-%20Planung.png
[product-screenshot3]: https://raw.githubusercontent.com/EMPLOYEZ/design/main/Modullayouts/Zeiterfassung%20-%20Planung.png
[product-screenshot4]: https://raw.githubusercontent.com/EMPLOYEZ/design/main/Modullayouts/Zeitsummen%20-%20Planung.png
[C#]: https://img.shields.io/badge/c%23-%23239120.svg?style=for-the-badge&logo=c-sharp&logoColor=white
[C#-url]: https://learn.microsoft.com/en-us/dotnet/csharp/
[.NET]: https://img.shields.io/badge/.NET-5C2D91?style=for-the-badge&logo=.net&logoColor=white
[.NET-url]: https://dotnet.microsoft.com/
[Visual Studio]: https://img.shields.io/badge/Visual%20Studio-5C2D91.svg?style=for-the-badge&logo=visual-studio&logoColor=white
[Visual Studio-url]: https://visualstudio.microsoft.com/
[Visual Studio Code]: https://img.shields.io/badge/Visual%20Studio%20Code-0078d7.svg?style=for-the-badge&logo=visual-studio-code&logoColor=white
[Visual Studio Code-url]: https://code.visualstudio.com/
[MySQL]: https://img.shields.io/badge/mysql-%2300f.svg?style=for-the-badge&logo=mysql&logoColor=white
[MySQL-url]: https://www.mysql.com/
[GitHub]: https://img.shields.io/badge/github-%23121011.svg?style=for-the-badge&logo=github&logoColor=white
[GitHub-url]: https://github.com/
