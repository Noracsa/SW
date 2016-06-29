# Semantic Web

''Projekt-Thema:''

"Welche historischen Persönlichkeiten finden in japanischen Videospielen Erwähnung?" Media:SW Thema.pdf (Arbeitstitel)

Festlegung: japanische Spiele sind Videospiele von japanischen Publishern

Idee: Liste historischer Persönlichkeiten vergleichen mit Liste von Charakteren aus Videospielen

mögliche Probleme:
- Schreibweise von Namen (Schriftzeichen, Reihenfolge von Vor- u. Nachname, ...)
- Dopplung von Namen verschiedener Personen (Uneindeutigkeit)
- mehr als ein Publisher

Beispiele:
- Rasputin als Gegner bei "Shadow Hearts: Covenant" (von Aruze, Midway)
- Oda Nobunaga als Spielfigur bei "Samurai Warriors" (von Koei)

Arbeitsplan
- Daten beschaffen
- Daten aufbereiten/vereinheitlichen
- Daten-Tripel in RDF-Format überführen
- Daten in Tripel-Store laden
- SPARQL-Anfrage
- Ergebnisse verifizieren


Daten-Quellen

Geboren.am (historische Personen)
    * Link: http://geboren.am/
    * Datenformat: HTML
    * Schnittstelle: HTTP
    * Lizenz: Creative Commons (CC)
    * Open Data: **** (4 Sterne)

Videospielehub.Wikia (Charaktere in Videospielen)
    * Link: http://de.videospielehub.wikia.com/wiki/Videospiele_Hub
    * z.B. http://shadowhearts.wikia.com/wiki/Category:Shadow_Hearts:_Covenant_Characters
    * Datenformat: HTML
    * Schnittstelle: HTTP
    * Lizenz: Creative-Commons-Lizenz (CC-BY-SA)
    * Open Data: **** (4 Sterne)

List of Every Video Game Ever von Data_Baser (Videospiele)
    * Link: http://pastebin.com/EuxZMbWT
    * Datenformat: Text (herunterladbar)
    * Schnittstelle: Notepad++ oder anderer Texteditor
    * Lizenz: Urheberrecht und den Lizenzbestimmungen des jeweiligen Autors (laut pastebin.com)
    * Open Data: *** (3 Sterne)

Dbpedia (für semantische Verknüpfung, alternative Schreibweisen)
    * Link: http://de.dbpedia.org
    * z.B http://de.dbpedia.org/page/Grigori_Jefimowitsch_Rasputin
    * Datenformat: RDF
    * Schnittstelle: HTTP
    * Lizenz: GNU-Lizenz
    * Open Data: ***** (5 Sterne)

Wikipedia (zur Evaluierung und weitere Infos)
    * Link: https://de.wikipedia.org
    * z.B. https://de.wikipedia.org/wiki/Portal:Japan/Personen
    * Datenformat: HTML
    * Schnittstelle: HTTP
    * Lizenz: Creative-Commons-Lizenz, GFDL
    * Open Data: **** (4 Sterne)

