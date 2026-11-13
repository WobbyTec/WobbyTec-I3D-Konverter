# WobbyTec-I3D-Konverter
Dieser Konverter ist das BindeGlied zwischen dem I3D-Importer von "Nadine Brinkmann" und dem >>>> GIANTS Community Exporter <<<<
Da wie zu erwarten war der GIANTS Exporter nicht immer fehlerfrei läuft zur englischen Benutzeroberfläche von Blender zwingt
und wie auch in der Vergangenheit gerne mal mit Fehlern den Export verweigert, ist hier eine Möglichkeit den bisher absolut
zuverlässigen >>>> GIANTS Community Exporter <<<< zu nutzen !
Anwendung ist ganz Einfach :
1. die gewünschte I3D in Blender ab v5.x.x importieren ( v4.x.x sind nicht gestestet)
2. NICHT !! die "Prepare Export" Funktion des I3d Importers verwenden !! da diese den Export für den GIANTS Exporter vorbereitet
3. Den Debug Material Modus kann man wie gewohnt nutzen um sich das Modell in den original Farben und Materialen anzuschauen MUSS !! aber vor dem Konvertieren und dem Export in den Export Material Modus geschaltet werden !!
4. das Modell kann bearbeitet, Parts getrennt werden
5. erst wenn man dann dann exportieren möchte, den Export Material Modus wie der einschalten und alle Parts ( einzeln oder alle ) selektieren und dann die Funktion "Daten >>> I3d Comm. Exporter" nutzen
   Es werden nun alle original Daten in den GIANTS Community Exporter übertragen. Sowohl Shader als auch Farben und Material Parameter werden in die enstprechenden Input Fields geschrieben, was auch sichtbar ist
6. nun wie gewohnt einfach den Export mit dem >>> GIANTS Community Exporter <<<<  starten und sich darüber freuen das die i3d fehlerfrei und mit allen Parametern im GIANTS Editor zu sehen sein wird.

-ENGLISH-
This converter serves as a bridge between the I3D importer by "Nadine Brinkmann" and the >>>> GIANTS Community Exporter <<<<.
Since the GIANTS Exporter—as might be expected—does not always run without errors, forces the use of Blender’s English user interface, 
and has a history of occasionally refusing to export due to various issues, this tool offers a way to utilize the highly reliable >>>> GIANTS Community Exporter <<<< instead!
Usage is very simple:
1. Import the desired I3D file into Blender (version 5.x.x or later; versions 4.x.x have not been tested).
2. Do NOT use the "Prepare Export" function of the I3D importer, as it prepares the model specifically for the standard GIANTS Exporter.
3. You can use "Debug Material" mode as usual to view the model with its original colors and materials; however, you MUST switch to "Export Material" mode before performing the conversion and export!
4. You may edit the model or separate its parts as needed.
5. When you are ready to export, switch to "Export Material" mode, select the relevant parts (either individually or all at once), and use the function "Data >>> I3D Comm. Exporter."
   All original data will then be transferred to the GIANTS Community Exporter. Shaders, colors, and material parameters are automatically populated into the corresponding input fields, where they will be visible.
6. Finally, simply initiate the export using the >>>> GIANTS Community Exporter <<<< as usual—and enjoy the fact that your I3D file will appear in the GIANTS Editor, error-free and with all its parameters intact.
