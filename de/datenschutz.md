---
title: Datenschutzerklärung
layout: default
---

# SimplyTrain - Datenschutzerklaerung

Stand: [INKRAFTTRETENSDATUM]

> Diese Datenschutzerklaerung ist ein projektbezogener Entwurf fuer `SimplyTrain` auf Basis des aktuellen Code- und Feature-Stands. Vor der Veroeffentlichung muessen die Platzhalter vervollstaendigt und die finale Fassung rechtlich geprueft werden.

## 1. Verantwortlicher

- Verantwortlicher: `[VOLLSTAENDIGER NAME ODER FIRMA]`
- Rechtsform: `[RECHTSFORM, FALLS VORHANDEN]`
- Anschrift: `[LADUNGSFAEHIGE ANSCHRIFT]`
- E-Mail: `[KONTAKT-E-MAIL]`
- Support: `[SUPPORT-URL]`

Sofern gesetzlich erforderlich oder vorhanden:

- Datenschutzkontakt / Datenschutzbeauftragter: `[DATENSCHUTZ-KONTAKT ODER DSB, FALLS VORHANDEN]`

## 2. Worum es in dieser Datenschutzerklaerung geht

Diese Datenschutzerklaerung informiert darueber, welche personenbezogenen Daten bei der Nutzung der App `SimplyTrain` verarbeitet werden, zu welchen Zwecken dies geschieht, auf welcher Rechtsgrundlage dies beruht, welche Empfaenger beteiligt sein koennen und welche Rechte betroffene Personen haben.

`SimplyTrain` ist eine offline-first iOS-App fuer Trainingsplanung, Workout-Tracking und Fortschrittsdokumentation. Nach aktuellem Stand verarbeitet die App Daten primaer lokal auf dem Geraet. Optionale Apple-Dienste wie `Sign in with Apple`, `CloudKit`, `HealthKit` und lokale iOS-Benachrichtigungen werden nur genutzt, wenn sie fuer bestimmte Funktionen erforderlich oder vom Nutzer aktiviert sind.

## 3. Kategorien personenbezogener Daten

Je nach Nutzung der App koennen insbesondere folgende Daten verarbeitet werden:

- Account- und Identitaetsdaten:
  - Apple User ID aus `Sign in with Apple`
  - von Apple ggf. bereitgestellte E-Mail-Adresse
  - von Apple ggf. bereitgestellter Anzeigename
- Vertrags- und Kaufbezugsdaten:
  - Beginn-Zeitstempel der 60-Tage-Testphase (`firstSignedInAt`, unveraenderlich in privater iCloud-Datenbank des Nutzers)
  - Kauf- bzw. Freischaltungsstatus (`Lifetime`, `6-Monats-Abo`, `Jahres-Abo`)
  - aktive Berechtigungsinformationen aus Apple-StoreKit (Original-Transaction-ID, Ablaufdatum bei Abos, Widerrufszeitstempel)
- Trainings- und Nutzungsdaten:
  - Trainingsplan
  - absolvierte Sessions, Uebungen, Saetze, Wiederholungen, Gewichte, RIR-Werte
  - Uebungsnotizen
  - Fortschritts- und Verlaufsdaten
  - Einstellungen wie Split, Trainingsfrequenz, Sessiondauer, Fokusmuskelgruppen, Equipment, Deload-Optionen
- Koerper- und Gesundheitsbezugsdaten:
  - Alter, Geschlecht, Koerpergroesse, Koerpergewicht
  - optionale Koerperumfaenge und Koerperfettangaben
  - Gelenk- und Belastungseinschraenkungen
- Fortschrittsfotos:
  - optional aufgenommene oder gespeicherte Progress-Fotos
  - Vorschaubilder der Fotos
  - Metadaten wie Erfassungsdatum und Kontext
- HealthKit-Daten:
  - optional aus Apple Health gelesene Daten, insbesondere Gewicht
  - optional in Apple Health geschriebene Trainings- und Gewichtsdaten
- Geraete- und Berechtigungsdaten:
  - Status von Kamera-, Benachrichtigungs- und HealthKit-Freigaben
  - Status von Cloud-Backup- und Foto-Speicheroptionen

## 4. Zwecke der Verarbeitung

Wir verarbeiten personenbezogene Daten nur insoweit, wie dies fuer den Betrieb der App und der von dir genutzten Funktionen erforderlich ist. Insbesondere zu folgenden Zwecken:

- Bereitstellung und Betrieb der App
- Anmeldung und Wiedererkennung des Nutzerkontos ueber `Sign in with Apple`
- Speicherung und Synchronisierung von Trainings-, Profil- und Einstellungsdaten
- Erstellung, Anpassung und Fortschreibung deines Trainingsplans
- Dokumentation und Visualisierung deiner Trainingsentwicklung
- Speicherung und Anzeige optionaler Fortschrittsfotos
- Synchronisierung mit Apple Health, soweit von dir aktiviert
- Wiederherstellung eines optional erworbenen Freischaltungsstatus
- Versand rein lokaler Geraete-Benachrichtigungen, soweit von dir aktiviert
- Fehlervermeidung, Datensicherheit und Missbrauchspraevention

## 5. Rechtsgrundlagen

Soweit die DSGVO anwendbar ist, stuetzen wir die Verarbeitung insbesondere auf folgende Rechtsgrundlagen:

- Art. 6 Abs. 1 lit. b DSGVO:
  - fuer die Bereitstellung der App,
  - fuer Login, App-Betrieb, Datenspeicherung, Trainingsplanung und Kaufstatus-Verwaltung,
  - soweit die jeweilige Verarbeitung fuer die Erfuellung des Nutzungsvertrags erforderlich ist
- Art. 6 Abs. 1 lit. a DSGVO:
  - fuer optionale Funktionen, die du freiwillig aktivierst, z. B. Kamera, lokale Benachrichtigungen oder iCloud-Backup, soweit hierfuer eine Einwilligung oder freiwillige Aktivierung massgeblich ist
- Art. 9 Abs. 2 lit. a DSGVO:
  - fuer die Verarbeitung besonderer Kategorien personenbezogener Daten, insbesondere gesundheitsbezogener Angaben, Koerperdaten, Fortschrittsfotos mit Gesundheitsbezug sowie die optionale HealthKit-Nutzung, soweit du diese Daten freiwillig eingibst oder die jeweilige Funktion ausdruecklich aktivierst
- Art. 6 Abs. 1 lit. c DSGVO:
  - soweit eine Verarbeitung zur Erfuellung gesetzlicher Pflichten erforderlich sein sollte
- Art. 6 Abs. 1 lit. f DSGVO:
  - soweit erforderlich zur Gewaehrleistung von IT-Sicherheit, Integritaet, Missbrauchsabwehr oder Verteidigung gegen Rechtsansprueche, sofern nicht deine Interessen oder Grundrechte ueberwiegen

## 6. Lokale Datenverarbeitung auf deinem Geraet

Nach aktuellem Stand ist `SimplyTrain` als offline-first App aufgebaut. Das bedeutet:

- Trainings- und Profildaten werden grundsaetzlich lokal auf deinem iPhone gespeichert.
- Die lokale Datenhaltung ist die primaere Datenquelle.
- Ohne aktivierte Zusatzfunktionen werden deine Kernnutzungsdaten nicht an einen eigenen Server des Anbieters uebermittelt.

Lokal gespeichert werden insbesondere:

- Trainingsplan und Trainingshistorie
- Profil- und Praeferenzdaten
- Uebungs- und Lastkonfigurationen
- optionale lokale Fortschrittsfotos
- lokale Vorschauen von Fortschrittsfotos
- Statusinformationen zu Berechtigungen und optionalen Apple-Integrationen
- lokal zwischengespeicherter Kaufstatus

## 7. Sign in with Apple

Fuer bestimmte Funktionen oder bereits fuer die Erstnutzung kann `Sign in with Apple` erforderlich sein. Dabei verarbeiten wir insbesondere:

- deine Apple User ID,
- deine von Apple ggf. freigegebene E-Mail-Adresse,
- deinen von Apple ggf. freigegebenen Namen.

Diese Daten werden verwendet, um:

- dein Nutzerkonto in der App zuzuordnen,
- lokale Nutzerdaten deinem Account zuzuordnen,
- optionale Cloud-Funktionen accountbezogen zu trennen,
- den Kaufstatus oder die Wiederherstellung bei Geraetewechsel zu unterstuetzen.

Die Daten werden nach aktuellem Stand lokal im iOS-Keychain bzw. in appbezogenen lokalen Speichern verarbeitet. Zusaetzlich gelten die Datenschutzbestimmungen von Apple fuer `Sign in with Apple`.

## 8. In-App-Kauf, Abonnements und StoreKit

`SimplyTrain` bietet ueber den Apple App Store eine 60-Tage-Testphase sowie folgende kostenpflichtige Produkte an:

- ein automatisch verlaengerbares 6-Monats-Abonnement,
- ein automatisch verlaengerbares Jahres-Abonnement,
- einen einmaligen `Lifetime`-Kauf.

Wenn du eines dieser Produkte nutzt, wiederherstellst oder dein Abonnement automatisch verlaengert wird, werden die zugehoerigen Berechtigungsinformationen ueber Apple-StoreKit verarbeitet. Wir erhalten dabei keinen vollstaendigen Zahlungsdatensatz von dir, sondern verarbeiten ausschliesslich die fuer Freischaltung, Wiederherstellung und korrekte Anzeige des Premium-Status erforderlichen Informationen (Produkt-ID, Original-Transaction-ID, Ablaufdatum, Widerrufszeitstempel).

Die Zahlungsabwicklung sowie die Verwaltung und Kuendigung von Abonnements erfolgen ausschliesslich ueber Apple bzw. die Apple-ID-Einstellungen des Nutzers. Es gelten insoweit auch die Datenschutz- und Vertragsbedingungen von Apple.

## 9. CloudKit und iCloud

`SimplyTrain` nutzt `CloudKit` (deine private iCloud-Datenbank) fuer zwei unterschiedliche Zwecke:

### 9.1 Trial- und Berechtigungs-Statushaltung (essentiell)

Beim ersten `Sign in with Apple` wird in deiner privaten iCloud-Datenbank ein Datensatz mit dem Beginn-Zeitstempel deiner 60-Tage-Testphase (`firstSignedInAt`) angelegt. Dieser Zeitstempel ist unveraenderlich und an deine Apple-ID gebunden. Er ist erforderlich, damit die Testphase auch bei Geraetewechsel, App-Neuinstallation oder Abmeldung korrekt fortgesetzt wird.

Im selben Datensatz koennen die jeweils zuletzt von Apple-StoreKit gemeldeten Berechtigungsinformationen gespeichert werden (Lifetime-Status oder aktives Abonnement, Ablaufdatum, Original-Transaction-ID).

Diese Funktion ist nicht abschaltbar, da sie fuer die korrekte Verwaltung von Testphase und Berechtigungsstatus zwingend erforderlich ist.

### 9.2 Datenbank- und Foto-Backup (optional)

Zusaetzlich kann ein vollstaendiges Cloud-Backup in den App-Einstellungen aktiviert werden. Wenn aktiviert, werden insbesondere folgende Daten in einem separaten Datensatz deiner privaten iCloud-Datenbank gespeichert:

- die lokale App-Datenbank mit Trainings- und Profildaten,
- Plattform- und App-Praeferenzen,
- optional die Originaldateien deiner Fortschrittsfotos (siehe § 10).

Das Backup dient ausschliesslich der Wiederherstellung deiner App-Daten auf einem neuen oder zuruckgesetzten Geraet. Es ist optional und kann jederzeit deaktiviert werden.

### 9.3 Allgemeine Hinweise zu iCloud/CloudKit

- Beide Datensaetze liegen in deiner privaten iCloud-Datenbank — der Anbieter hat darauf keinen direkten Zugriff.
- Die Verarbeitung erfolgt innerhalb der von Apple bereitgestellten Infrastruktur.
- Auf die weitere Verarbeitung durch Apple haben wir nur den durch Apple vorgesehenen Einfluss.
- Fuer Apple-Dienste gelten zusaetzlich die Datenschutzinformationen von Apple.

## 10. Fortschrittsfotos und Kamera

Die Kamera wird nur verwendet, wenn du aktiv die Funktion fuer Fortschrittsfotos nutzt.

Je nach von dir gewaehlter Speicheroption werden Fotos:

- lokal in der App gespeichert, oder
- als private Originaldatei in deiner iCloud/CloudKit-Umgebung gespeichert, waehrend lokal nur eine Vorschau verbleibt.

Die Fortschrittsfotos dienen ausschliesslich deiner persoenlichen Dokumentation innerhalb der App. Nach aktuellem Stand werden diese Fotos nicht fuer Werbung, Tracking oder eine profilerstellende Auswertung durch uns verwendet.

## 11. HealthKit / Apple Health

Die App kann optional `HealthKit` nutzen. Dies geschieht nur, wenn du die HealthKit-Freigaben auf iOS-Ebene erteilst und die Funktion in der App aktivierst.

Nach aktuellem Projektstand kann die App insbesondere:

- Trainings als Krafttraining in Apple Health schreiben,
- Koerpergewicht in Apple Health schreiben,
- bestimmte Health-Daten wie Gewicht aus Apple Health lesen.

Die Verarbeitung von HealthKit-Daten erfolgt ausschliesslich zur Unterstuetzung deiner Trainingsdokumentation und Kontextualisierung innerhalb der App.

Wichtige Hinweise:

- HealthKit-Daten sind gesundheitsbezogene Daten im Sinne der DSGVO.
- Die HealthKit-Nutzung ist freiwillig.
- Wenn du HealthKit nicht aktivierst, wird diese Integration nicht genutzt.
- Daten, die in Apple Health geschrieben wurden, koennen zusaetzlich innerhalb des Apple-Systems gespeichert bleiben. Soweit solche Daten bereits in Apple Health gespeichert wurden, kann eine vollstaendige Entfernung gegebenenfalls ueber Apple Health bzw. Apple-Einstellungen erforderlich sein.

## 12. Lokale Benachrichtigungen

Die App kann lokale Benachrichtigungen auf deinem Geraet verwenden, insbesondere fuer:

- Rest-Timer waehrend des Trainings,
- Erinnerungen zum Eintragen des Koerpergewichts.

Dabei handelt es sich nach aktuellem Stand um lokale iOS-Benachrichtigungen, nicht um serverseitige Push-Nachrichten eines eigenen Backends des Anbieters.

Hierfuer werden auf dem Geraet insbesondere folgende Informationen verarbeitet:

- Benachrichtigungsfreigabe,
- Timer- und Erinnerungsstatus,
- Titel oder Bezug zur aktuellen Uebung,
- Zeitpunkte geplanter lokaler Benachrichtigungen.

## 13. Keine Werbung, kein App-Tracking, keine Drittanbieter-Analytics

Nach aktuellem Stand des Projekts verwendet `SimplyTrain`:

- keine Werbe-SDKs,
- kein app-uebergreifendes Tracking,
- keine IDFA-basierte Werbeverfolgung,
- keine Drittanbieter-Analytics- oder Marketing-SDKs.

Die App ist nach aktuellem Stand nicht darauf ausgelegt, Nutzer ueber Apps oder Websites Dritter hinweg zu tracken.

## 14. Empfaenger und Kategorien von Empfaengern

Personenbezogene Daten koennen, soweit technisch erforderlich und von dir genutzt, an folgende Kategorien von Empfaengern uebermittelt oder durch diese verarbeitet werden:

- Apple:
  - `Sign in with Apple`
  - App Store / StoreKit
  - iCloud / CloudKit
  - Apple Health / HealthKit
  - iOS-Systemdienste fuer Benachrichtigungen
- Sonstige Empfaenger nur, wenn:
  - du uns hierzu gesondert kontaktierst,
  - wir gesetzlich dazu verpflichtet sind,
  - dies zur Rechtsverfolgung oder Rechtsverteidigung erforderlich ist

Nach aktuellem Stand betreibt der Anbieter kein eigenes externes Tracking-, Werbe- oder Analytics-Backend fuer die App.

## 15. Uebermittlungen in Drittlaender

Soweit Apple oder andere eingebundene Dienste personenbezogene Daten in Staaten ausserhalb der EU bzw. des EWR verarbeiten, kann eine solche Uebermittlung auf Grundlage der von Apple eingesetzten Datenschutzmechanismen erfolgen. Die konkrete internationale Datenverarbeitung innerhalb der Apple-Infrastruktur richtet sich nach den Datenschutzinformationen von Apple.

## 16. Speicherdauer

Wir speichern personenbezogene Daten nur so lange, wie dies fuer die jeweiligen Zwecke erforderlich ist oder bis du sie loeschst bzw. die jeweilige Funktion deaktivierst, soweit keine gesetzlichen Aufbewahrungspflichten entgegenstehen.

Typischerweise bedeutet das:

- lokale App-Daten:
  - bis zur Loeschung durch dich,
  - bis zur Konto-/Datenloeschung in der App,
  - oder bis zur Deinstallation der App, soweit Daten nicht zusaetzlich in iCloud oder HealthKit liegen
- Keychain- bzw. Sessiondaten:
  - bis zur aktiven Konto-/Datenloeschung oder Entfernung der Session
- CloudKit-Backups und iCloud-Fotos:
  - bis zur Loeschung durch dich, Deaktivierung mit Loeschung oder Nutzung der In-App-Konto-Loeschfunktion, soweit technisch vorgesehen
- HealthKit-Daten:
  - soweit bereits an Apple Health uebermittelt, nach den Loesch- und Speicherregeln des Apple-Health-Systems

## 17. Deine Rechte

Soweit die DSGVO anwendbar ist, hast du nach Massgabe der gesetzlichen Voraussetzungen insbesondere folgende Rechte:

- Recht auf Auskunft, Art. 15 DSGVO
- Recht auf Berichtigung, Art. 16 DSGVO
- Recht auf Loeschung, Art. 17 DSGVO
- Recht auf Einschraenkung der Verarbeitung, Art. 18 DSGVO
- Recht auf Datenuebertragbarkeit, Art. 20 DSGVO
- Recht auf Widerspruch, Art. 21 DSGVO
- Recht, eine erteilte Einwilligung jederzeit mit Wirkung fuer die Zukunft zu widerrufen
- Recht auf Beschwerde bei einer Datenschutzaufsichtsbehoerde

Du kannst viele Daten bereits direkt in der App aendern oder entfernen. Fuer Anfragen zu datenschutzrechtlichen Rechten kontaktiere uns bitte unter `[KONTAKT-E-MAIL]`.

## 18. Abmelden, Konto- und Datenloeschung in der App

`SimplyTrain` stellt zwei unterschiedliche Aktionen zur Beendigung oder Unterbrechung der Nutzung bereit:

### 18.1 Abmelden ("Sign out")

Bei Verwendung der Funktion "Abmelden" im Profil-/Einstellungsbereich:

- werden lokale Apple-Sessiondaten aus dem iOS-Keychain entfernt,
- bleiben lokal gespeicherte Trainings-, Profil- und Foto-Daten erhalten,
- bleiben iCloud-/CloudKit-Backup und Trial-Statusdatensatz erhalten,
- stehen nach erneuter Anmeldung mit derselben Apple-ID alle Daten wieder zur Verfuegung.

### 18.2 Account und lokale Daten loeschen

Bei Verwendung der Funktion "Account loeschen" im Profil-/Einstellungsbereich werden insbesondere geloescht:

- lokal gespeicherte appbezogene Nutzerdaten und Datenbanken,
- lokal gespeicherte Fortschrittsfotos und deren Vorschauen,
- der appbezogene CloudKit-Backup-Datensatz (Datenbank-Backup),
- private iCloud-Fotodatensaetze der App, soweit von der App verwaltet,
- lokal gespeicherte Apple-Sessiondaten der App.

### 18.3 Wichtige Einschraenkungen

- Der Datensatz zum Beginn der Testphase (`firstSignedInAt`, siehe § 9.1) bleibt aus systembedingten Gruenden in deiner privaten iCloud-Datenbank erhalten und wird durch die In-App-Konto-Loeschung **nicht** entfernt. Hintergrund ist die Verhinderung eines wiederholten Trial-Beginns mit derselben Apple-ID. Eine vollstaendige Loeschung dieses Datensatzes kann ueber `Einstellungen` → Apple-ID → `iCloud` → `Apps mit iCloud` → `SimplyTrain` Apple-seitig erfolgen.
- Ein ueber Apple erworbenes In-App-Subscription-Abo oder `Lifetime`-Entitlement verbleibt bei Apple und wird durch die In-App-Konto-Loeschung nicht aufgehoben. Die Kuendigung eines Abonnements erfolgt ueber die Apple-ID-Einstellungen.
- Bereits in Apple Health geschriebene Daten werden nicht automatisch durch die App aus Apple Health entfernt. Eine Loeschung kann ueber die Apple-Health-App bzw. Apple-Einstellungen erfolgen.

## 19. Datensicherheit

Wir treffen angemessene technische und organisatorische Massnahmen, um personenbezogene Daten vor Verlust, Missbrauch, unbefugtem Zugriff oder unbefugter Veraenderung zu schuetzen. Nach aktuellem Stand zaehlen hierzu insbesondere:

- lokale Speicherung auf dem Geraet als Standardmodell,
- Nutzung von Apple-Systemmechanismen wie Keychain, HealthKit und privaten CloudKit-Datenbanken, soweit diese Funktionen verwendet werden,
- Beschraenkung optionaler Datenuebermittlungen auf aktivierte Apple-Dienste.

Eine vollstaendig risikofreie Datenverarbeitung kann jedoch bei digitalen Angeboten nicht garantiert werden.

## 20. Aenderungen dieser Datenschutzerklaerung

Wir koennen diese Datenschutzerklaerung anpassen, wenn dies aus rechtlichen, technischen oder produktbezogenen Gruenden erforderlich ist. Es gilt die jeweils aktuelle Fassung.

## 21. Kontakt

Bei Fragen zum Datenschutz kontaktiere uns bitte unter:

- E-Mail: `[KONTAKT-E-MAIL]`
- Support: `[SUPPORT-URL]`
