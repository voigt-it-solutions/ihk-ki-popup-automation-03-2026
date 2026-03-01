# Aufgabe 1

## Ziel

Wir wollen einen Workflow entwickeln, der bei der vorbereitenden Buchhaltung unterstützt.
Der Workflow soll in der Lage sein, E-Mails zu verarbeiten und herauszufinden, ob es sich um eine Rechnungs-E-Mail, um eine E-Mail mit einem Lieferschein oder eine sonstige E-Mail handelt.
Je nach E-Mail-Typ soll der Workflow die E-Mail in einen entsprechenden Ordner verschieben.
Bei einer Rechnungs-E-Mail kommt noch hinzu, dass der Rechnungsanhang erkannt und in einem Ordner im DMS gespeichert werden soll.

Beachte: Rechnungs-E-Mails enthalten gerne auch Anhänge, die keine Rechnungen sind, wie bspw. Bilder, Signaturen oder Ähnliches. Daher fokussieren wir uns erstmal auf PDFs.

## Anforderungen

- Der Workflow soll in der Lage sein, E-Mails zu verarbeiten und herauszufinden, ob es sich um eine Rechnungs-E-Mail handelt.
- Bei einer Rechnungs-E-Mail soll der Workflow den Rechnungsanhang erkennen und in einem Ordner im DMS speichern.
- Der Workflow soll die E-Mail in einen entsprechenden Ordner verschieben, je nach E-Mail-Typ.
- Der Workflow soll nur PDFs als Rechnungsanhang erkennen.

## Hinweise

- Du benötigst Zugriff auf dein E-Mail-Postfach.
- Du benötigst Zugriff auf dein DMS.
- Wir arbeiten mit MS 365, aber grundsätzlich funktioniert auch die Google Suite. (Auch weitere Tools sind möglich, allerdings werden wir nicht die Zeit haben auf die verschiedenen Systeme einzugehen.)

## Arbeitsschritte

# Basis (ohne Anhänge)

1. Erstelle die E-Mail-Ordner für diesen Workflow
   1. einen Basis-Ordner, aus dem wir die E-Mails abrufen: "01 Email-Eingang"
   2. einen Ziel-Ordner für Rechnungen: "02 Rechnungen"
   3. einen Ziel-Ordner für Lieferscheine: "03 Lieferscheine"
   4. einen Ziel-Ordner für sonstige E-Mails: "04 Sonstige"
2. Kopiere oder verschiebe dir 2-3 E-Mails in diesen E-Mail-Ordner
3. Erstelle in Make.com ein neues Szenario und öffne dies
4. Erstelle eine passende Trigger-Node
5. Rufe die E-Mail aus dem angelegten Ordner "01 Email-Eingang" ab (vgl. 1)
6. Erstelle eine AI-Node, die die wichtigsten Informationen der E-Mail ausliest und eine Kategorisierung vornimmt
   - Erstelle passende Prompts für die AI-Node
   - Nutze gerne die [Vorlage 1](AI%20Vorlage%201.md)
7. Erstelle einen Router, der die Daten je nach Kategorie weiterverarbeitet
   - Lege Filter an den Routen für die jeweilige Kategorie fest
8. Erstelle je nach Kategorie eine entsprechende Node, um die E-Mail in einen entsprechenden Ordner zu verschieben

# Erweiterung um Verarbeitung von Anhängen

9. Lege dir einen Ordner in deinem DMS an, in dem die Dokumente gespeichert werden sollen: "01 Rechnungen"
10. Lade die Anhänge der E-Mail
11. Bereite die Daten für die AI-Node vor, um sie in der Kategorisierung mit zu betrachten
12. Erweitere die Prompts für die AI-Node
    - Nutze gerne die [Vorlage 2](AI%20Vorlage%202.md) oder erstelle deinen eigenen Prompt
13. Speichere die Rechnung (E-Mail-Anhang) im Ordner (vgl. 9)