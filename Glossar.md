# Glossar

Hier werden wichtige Begriffe aus dem Bereich der Business Automation erläutert.

### Allgemeine Konzepte

| Begriff | Definition / Erläuterung |
| :--- | :--- |
| **Business Automation** | Der Einsatz von Technologie zur Automatisierung von Geschäftsprozessen, um Effizienz zu steigern, Fehler zu reduzieren und menschliche Ressourcen für wertschöpfendere Aufgaben freizusetzen. |
| **BPA (Business Process Automation)** | Ein technologiegestützter Ansatz zur Automatisierung komplexer Geschäftsprozesse, oft mit Fokus auf die Optimierung des gesamten Workflows. |
| **RPA (Robotic Process Automation)** | Software-Roboter, die menschliche Interaktionen mit Benutzeroberflächen imitieren, um repetitive Aufgaben in Altsystemen ohne API-Zugriff zu automatisieren. |
| **Workflow** | Eine Abfolge von vordefinierten Schritten oder Aufgaben, die ausgeführt werden, um ein bestimmtes Geschäftsergebnis zu erzielen. |
| **MVP (Minimum Viable Product)** | Die erste, funktionsfähige Version eines Produkts oder einer Automatisierung, die nur die Kernfunktionen enthält, um schnelles Feedback zu erhalten. |
| **No-Code / Low-Code** | Ansätze zur Softwareentwicklung, die es ermöglichen, Anwendungen oder Automatisierungen mit minimalem (Low-Code) oder ganz ohne (No-Code) manuelles Programmieren zu erstellen, meist durch visuelle Editoren. |
| **ROI (Return on Investment)** | Ein Maßstab für die Rentabilität einer Automatisierung, der den finanziellen Nutzen dem investierten Kapital (und Zeit) gegenüberstellt. |
| **Skalierbarkeit** | Die Fähigkeit eines Systems oder Prozesses, bei steigendem Arbeitsaufkommen effizient mitzuwachsen, ohne dass die Leistung proportional sinkt. |
| **ETL (Extract, Transform, Load)** | Ein Prozess zur Datenintegration, bei dem Daten aus verschiedenen Quellen extrahiert, in ein passendes Format umgewandelt und in ein Zielsystem geladen werden. |

### Plattformen & Tools

| Begriff | Details & Preismodell |
| :--- | :--- |
| **iPaaS (Integration Platform as a Service)** | Eine Cloud-Plattform, die verschiedene Anwendungen und Systeme miteinander verbindet und den Datenaustausch zwischen ihnen automatisiert (z. B. Make, Zapier). |
| **SaaS (Software as a Service)** | Software, die über das Internet als Abonnement bereitgestellt wird (z. B. CRM-Systeme, Buchhaltungstools). |
| **make.com** | Eine leistungsstarke iPaaS-Plattform zur visuellen Erstellung komplexer Automatisierungs-Workflows. <br> *Preismodell: Freemium (kostenloser Einstieg möglich), Abrechnung nach "Operations".* |
| **n8n (nodemation)** | Ein (fair-code) Workflow-Automatisierungstool, das sowohl selbst gehostet als auch in der Cloud genutzt werden kann. <br> *Preismodell: Kostenlos bei Self-Hosting, Abomodelle für Cloud-Nutzung.* |
| **Zapier** | Eines der bekanntesten No-Code-Automatisierungstools mit einer sehr großen Anzahl an unterstützten Apps. <br> *Preismodell: Freemium, Abrechnung nach "Tasks".* |
| **Power Automate** | Die Automatisierungsplattform von Microsoft, die tief in das Microsoft 365 Ökosystem integriert ist. <br> *Preismodell: Oft in bestehenden Microsoft 365 Lizenzen enthalten, Zusatzpakete für RPA und Premium-Connectoren.* |
| **Workato** | Eine Enterprise-Grade-iPaaS-Plattform für komplexe Integrationen und Automatisierungen in größeren Unternehmen. <br> *Preismodell: Hochpreisig, individuelle Enterprise-Verträge.* |
| **Activepieces** | Ein Open-Source No-Code-Automatisierungstool, das sich besonders durch seine Benutzerfreundlichkeit und Cloud-Option auszeichnet. <br> *Preismodell: Open Source (kostenlos bei Self-Hosting) oder Cloud-Abo.* |

### Technische Begriffe

| Begriff | Definition / Erläuterung |
| :--- | :--- |
| **API (Application Programming Interface)** | Eine Schnittstelle, über die verschiedene Softwareanwendungen miteinander kommunizieren und Daten austauschen können. |
| **API-Key** | Ein eindeutiger Code, der zur Authentifizierung bei einer API verwendet wird, um den Zugriff auf Daten zu autorisieren. |
| **OAuth** | Ein Standardprotokoll für die sichere Autorisierung, das es Anwendungen ermöglicht, auf Daten zuzugreifen, ohne die Passwörter der Benutzer preiszugeben. |
| **Webhook** | Eine Methode, um Echtzeit-Benachrichtigungen von einem System an ein anderes zu senden, sobald ein bestimmtes Ereignis eintritt (Event-driven). |
| **Trigger** | Das auslösende Ereignis, das einen Workflow oder eine Automatisierung startet (z. B. eine neue E-Mail oder ein Formulareingang). |
| **Node (Knoten)** | Ein einzelner Schritt innerhalb eines Workflows (in Tools wie n8n), der eine spezifische Aktion ausführt (z. B. Daten abrufen, filtern oder senden). |
| **Szenario** | Die Bezeichnung für einen vollständigen Workflow in make.com. |
| **Mapping** | Der Prozess der Zuweisung von Datenfeldern aus einer Quelle zu den entsprechenden Feldern in einem Zielsystem. |
| **Router (make.com)** | Ein Modul, das den Datenfluss in verschiedene Pfade aufteilt, basierend auf bestimmten Bedingungen. |
| **Filter (make.com)** | Eine Bedingung, die bestimmt, ob Daten innerhalb eines Workflows weiterverarbeitet werden oder nicht. |
| **Logs / Logging** | Die systematische Aufzeichnung von Ereignissen und Fehlern während der Ausführung einer Automatisierung zur Überwachung und Fehlerbehebung. |
| **Error Handling / Retries** | Mechanismen, die festlegen, wie ein System auf Fehler reagiert (z. B. automatisches erneutes Versuchen einer fehlgeschlagenen Aktion). |
| **JSON (JavaScript Object Notation)** | Ein leichtgewichtiges Datenformate, das einfach von Menschen zu lesen und von Maschinen zu verarbeiten ist; der Standard für den Datenaustausch über APIs. |
| **Parsing** | Das Analysieren und Umwandeln von Daten (z. B. aus einer E-Mail oder einem PDF) in ein strukturiertes Format, das von Automatisierungstools verarbeitet werden kann. |
| **Variables / Variablen** | Platzhalter für Daten, die sich während der Ausführung eines Workflows ändern können (z. B. der Name eines Kunden oder ein Datum). |

### Systeme & Datenmanagement

| Begriff | Definition / Erläuterung |
| :--- | :--- |
| **CRM (Customer Relationship Management)** | Software zur Verwaltung von Kundenbeziehungen und Interaktionen (z. B. Salesforce, Hubspot). |
| **ERP (Enterprise Resource Planning)** | Eine zentrale Softwarelösung zur Steuerung aller Geschäftsprozesse eines Unternehmens (z. B. SAP, Microsoft Dynamics, Odoo). |
| **DMS (Document Management System)** | Ein System zur digitalen Archivierung und Verwaltung von Dokumenten. |
| **PIM (Product Information Management)** | Ein System zur zentralen Verwaltung und Bereitstellung von Produktinformationen für verschiedene Kanäle. |

### Künstliche Intelligenz (AI)

| Begriff | Definition / Erläuterung |
| :--- | :--- |
| **AI Agent** | Ein KI-System, das autonom Aufgaben plant und ausführt, um ein vorgegebenes Ziel zu erreichen, anstatt nur auf Fragen zu antworten. |
| **Agentic** | Ein Begriff für KI-Systeme, die ein hohes Maß an Autonomie und Entscheidungsfähigkeit besitzen, um komplexe Workflows selbstständig zu steuern. |
| **Guardrails (AI)** | Sicherheitsmechanismen und Regeln, die das Verhalten einer KI einschränken, um sicherzustellen, dass die Ausgaben korrekt, sicher und relevant bleiben. |
| **Klassifizierung (AI)** | Der Prozess, bei dem eine KI Daten (z. B. E-Mails oder Dokumente) automatisch in vordefinierte Kategorien einordnet. |
| **LLM (Large Language Model)** | Ein KI-Modell, das auf riesigen Textmengen trainiert wurde, um menschliche Sprache zu verstehen und zu generieren (z. B. GPT-4, Claude). |
| **RAG (Retrieval-Augmented Generation)** | Eine Technik, bei der eine KI auf externe, aktuelle Datenquellen zugreift, um präzisere und kontextbezogene Antworten zu geben. |
| **Prompt Engineering** | Das gezielte Entwerfen und Optimieren von Eingabeaufforderungen (Prompts), um die bestmöglichen Ergebnisse von einer KI zu erhalten. |
| **Halluzination (AI)** | Ein Phänomen, bei dem eine KI Fakten erfindet oder falsche Informationen mit großer Überzeugung präsentiert. |
| **Token** | Die kleinste Einheit von Text, die ein LLM verarbeitet (oft Silben oder Wortfragmente). Die Abrechnung von KI-Diensten erfolgt meist nach der Anzahl verbrauchter Token. |

### Abrechnungsmodelle & Credits

| Begriff | Definition / Erläuterung |
| :--- | :--- |
| **Credits / Operations / Tasks** | Die internen Währungen von Automatisierungstools. Jede ausgeführte Aktion innerhalb eines Workflows verbraucht eine bestimmte Menge dieser Einheiten. |
| **Freemium** | Ein Geschäftsmodell, bei dem die Basisnutzung des Tools kostenlos ist, während für fortgeschrittene Funktionen oder höhere Nutzungskontingente Gebühren anfallen. |
| **Pay-per-use** | Ein Abrechnungsmodell, bei dem nur die tatsächliche Nutzung bezahlt wird (z. B. Anzahl der verarbeiteten Daten oder API-Aufrufe). |
| **Rate Limiting** | Eine Begrenzung der Anzahl von Anfragen oder Aktionen innerhalb eines bestimmten Zeitraums (z. B. 100 Anfragen pro Minute), oft abhängig vom gewählten Preisplan. |
