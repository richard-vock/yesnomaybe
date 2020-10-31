# yesnomaybe

(German version below)

## About yesnomaybe

*yesnomaybe* is a simple, browser-based application for ternary image classification -- meaning that an image
can be classified as having some property ("yes"), not having said property ("no") or a state of uncertainty ("maybe").

Once annotated by a user that classification can be saved as a .csv file ready to be imported into Excel, LibreOffice, etc.

It is serverless, so at no point does either the input or the output data leave the client's computer; rendering this tool
suitable for privacy-critical data.

## Usage

A public instance is hosted and can be used here: https://richard-vock.github.io/yesnomaybe

Simply open that URL, choose multiple files using drag-and-drop or the file open dialog and start classifying images using
the green ("yes"), red ("no") or ("grey") button in the bottom right corner.

The blue button creates the output csv file as a "download" (it is actually created in your browser, but anything you want to save to your local disk is technically a "download").

## Compatibility

The tool was tested using current versions of Firefox and Chrome/Chromium. Edge didn't like (as in: ignore) the download button, but no one uses that browser, right?

The CSV file was tested in Excel and LibreOffice Calc.


# yesnomaybe (German version)

## Über yesnomaybe

yesnomaybe ist eine einfache, browser-basierte Anwendung zur ternären Bildklassifikation - d.h. ein Bild kann so klassifiziert werden, dass es eine Eigenschaft hat ("yes"), diese Eigenschaft nicht hat ("nein") oder einen Zustand der Unsicherheit ("maybe").

Sobald diese Klassifikation vom Benutzer erstellt wurde, kann sie als .csv-Datei gespeichert und in Excel, LibreOffice usw. importiert werden.

Die Anwendung ist serverlos, d.h. weder die Eingabe- noch die Ausgabedaten verlassen zu irgendeinem Zeitpunkt den Computer des eigenen Rechners, so dass dieses Tool auch für sensible (datenschutzkritische) Bilddaten geeignet ist.

## Nutzung

Eine öffentliche Instanz kann hier genutzt werden: https://richard-vock.github.io/yesnomaybe

Dazu einfach diese URL öffnen, mehrere Dateien per Drag-and-Drop oder über den Öffnen-Dialog wählen und dann mit Hilfe der Knöpfe unten rechts (grün für "yes", rot für "no" und grau für "maybe") die einzelnen Bilder klassifizieren.

Mit der blauen Schaltfläche wird die csv-Ausgabedatei als "Download" erstellt (sie wird tatsächlich in Ihrem Browser erstellt, aber alles, was auf der lokalen Festplatte gespeichert werden soll, ist technisch gesehen ein "Download").

## Kompatibilität

Die Anwendung wurde getestet mit aktuellen Versionen von Firefox und Chrome/Chromium. Der Edge Browser hat den download button einfach vollständig ignoriert -- aber den nutzt ja auch keiner, oder?

Die CSV Ausgabedateien wurden in Excel und LibreOffice Calc getestet und "sollten" da importierbar sein.
