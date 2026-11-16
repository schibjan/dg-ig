<!--
  Schritt 7: Startseite eures IG
  Ersetzt die TODOs durch eigenen Text. Markdown ist erlaubt.
  Diese Seite ist die erste, die man auf GitHub Pages sieht.
-->

### Use Case

This implementation guide defines the structure to record patient allergies.
The doctor collects and enter the data right after the patient's arrival.
The primary use cases are emergencies.

### Scope

This IG is designed for emergencies, so it exclusively records medication allergies.
Food allergies and other intolerances will therefore not be recorded.

### Artefakte

* [DG Arzneimittelallergie](StructureDefinition-dg-medication-allergy.html): A FHIR-profile based on CH Core that sets the mandatory rules
* [Penicillin Allergy Anna Muster](AllergyIntolerance-PenicillinAllergyAnna.html): An example dataset of a patient with a penicillin allergy

### Abhängigkeiten

Dieses IG baut auf [CH Core 6.0.0](https://fhir.ch/ig/ch-core/6.0.0/) auf.

### Autorin oder Autor

Janine Schibli

<p style="font-size:smaller">Erstellt im Lab des Moduls Data Standards in Healthcare, ZHAW, HS26. Kein offizieller Standard.</p>
