# Verbindungen der AfD mit Rechtsextremen
# Datensatz #
Codebuch Verbindungen der AfD mit Rechtsextremen Stand Abgabe (13.05.2024)

Erstellt von Simon exner (se099) und Jan Köneke (jk268)

## Inhalt
- faschonodes (Nodelist
- faschoedges (Edgelist)
- Codebuch.md (Codierung der Datensätze)

## Ursprung der Datenerhebung

Unsere Forschung entstand aus der Vorlesung "Soziale Netzwerkanalyse", die während des dritten und vierten Semesters des Studiengangs Crossmedia-Redaktion/Public Relations an der Hochschule der Medien in Stuttgart angeboten wird.

Der Datenzugang erfolgte über den Artikel "Geheimplan gegen Deutschland" von Correctiv, sowie durch eine umfangreiche Analyse verschiedener Medienberichte, um ein möglichst breites Spektrum an Quellen für unser Netzwerk zu erschließen. Die Datenerhebung konzentrierte sich auf Mitglieder der AfD und die Veranstaltungen und Personen, die mit dem Gasthof-Adlon-Treffen und weiteren ähnlichen Zusammenkünften verbunden sind.

Das Netzwerk ist ein *ungerichtetes Gesamtnetzwerk*

# NODELIST-Attribute

**id** 
<p>Eindeutige Identifikation (Bürgerlicher Name) eines Knotens.

**name**
<p>Ebenfalls der Name des Knotens, um ihn im Netzwerk anzeigen zu können

**subgroup** 
<p>Genaue Zugehörigkeit des Knotens zu einer Institution 
<p>("AfD Baden-Württemberg", "AfD Baden-Württemberg Fraktion", "AfD Berlin Fraktion", "AfD Berlin Partei", "AfD Brandenburg Partei", "AfD Bund Mitarbeiter", "AfD Bundestags Fraktion", "AfD Bundesvorstand", "AfD Cottbus", "AfD Fraktion Brandenburg", "AfD Fraktion Nordrhein-Westfalen", "AfD Hessen Partei", "AfD Kreisverband Havelland", "AfD Mecklenburg-Vorpommern Fraktion", "AfD Mecklenburg-Vorpommern Partei", "AfD Nordrhein-Westfalen Partei", "AfD Potsdam", "AfD Sachsen-Anhalt Fraktion", "AFD Sachsen-Anhalt Partei", "AfD Thüringen", "AfD Thüringen Fraktion", "AfD Thüringen Partei", "AfD-FraktionThüringen", "Asow-Regiment", "Backwerk Management GmbH", "Betriebsrat Daimler Benz Sindelfingen", "Bündnis Sarah Wagenknecht", "CDU-Mitglied", "Compact", "Das Institut für Staatspolitik", "Deutschland-Kurier", "Desiderius-Erasmus-Stiftung", "Ein Prozent e.V", "Einzelperson", "EU-Parlament", "Filmkunstkollektiv", "Fraktionslos Bundestagsabgeordneter", "Gasthof Adlon", "Heilpraktiker", "Heimattreue Deutsche Jugend", "Identitäre Bewegung", "Junge Alternative", "Junge Freiheit", "Jurist", "Lega Nord", "Mörig-Clan", "Neue Rechte", "NPD", "Parteilos", "Potsdamer CDU-Kreisvorstand", "Republikaner", "Rundfunkrat Berlin-Brandenburg", "Social Media", "Unternehmer", "Vatikan", "Verein Deutsche Sprache", "Wackren Schwaben (früher IB Schwaben)", "Werteunion", "Wiking-Jugend", "Wügida (Pegida Ableger)", "Youtube", "Zentrum Automobil")

**group**
<p>Weiter gefasste Definition von Institution
<p>("AR"=Asow-Regiment, "AfD-Mitarbeiter", "AfD-Politiker", "BSW"=Bündnis Sarah Wagenknecht, "CDU_Politiker", "DES"=Desiderius Erasmus Stiftung, "IB"=Identitäre Bewegung, "IfS"=Institut für Staatspolitik, "IT"=Italien, "JF"=Junge Freiheit, "Journalist", "MC"=Mörig-Clan, "NPD", "PP"=Privatperson, "USA", "VA"=Vatikan, "WU"=Werteunion, "ZA"=Zentrum Automobil)

**type**
<p>Funktion, die der Knoten erfüllt
<p>("Aktivist", "Autor", "Bauunternehmer", "Ehefrau", "Geistlicher", "Heilpraktiker", "Immobilienunternehmerin", "Influencer", "Journalist", "Jusrist", "Kabarettist", "Milliardär", "Netzaktivist", "Politiker", "Privatperson", "Publizist", "Rechtsanwalt", "Unternehmer", "Zahnärztin")

**remarks**
<p>Kurze Informationen zum jeweiligen Knoten (NA)

# EDGELIST-Attribute

**from**
<p>Entspricht einer ID aus der Nodelist

**to**
<p>Entspricht der entsprechenden ID aus der Edgelist. Die Reihenfolge spielt keine Rolle, da es sich um ein ungerichtetes Netzwerk handelt.

**connection**
<p>Der Anlass, aus dem zwei Knoten Kontakt zueinander hatten (NA)

**weight**
<p>Gewichtung der jeweiligen Verbindung
<p>("1"= Einmaliger Kontakt, "2"= über einmaliges Treffen hinaus, "3"= regelmäßige Zusammenarbeit, "4"= Verwandt, verheiratet, gut befreundet)
