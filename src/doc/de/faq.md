# Häufig gestellte Fragen

## Allgemein

??? question "Welche allgemeinen Vor- und Nachteile bietet OSH?"

    === "Allgemein"
    
        **Vorteile**

        - Organisationsübergreifende Zusammenarbeit an den selben Quellen
        - „Forking“ erlaubt Übernahme der Quellen und unabhängige Weiterentwicklung

        **Nachteile**

        - Verwaltung der Quellen meist abhängig von initialen Entwickelnden


    === "Unternehmen"

        **Vorteile**
        
        - Schnellere Innovation durch Wiederverwendung bestehender Designs
        - Verteilung und Reduzierung des Entwicklungsaufwands durch Modularisierung auf viele Akteure
        - effizientere Kollaboration mit anderen Unternehmen
        - starke Reduzierung von Bürokratie
        - Reduzierung des Dokumentationsaufwandes (Modularisierung)
        
        **Nachteile**

        - Hoheit über die Entwicklung wird an Gemeinschaft abgegeben
        - Hoher initialer Entwicklungsaufwand kann nur wenig auf Produktpreis umgelegt werden (Gefahr der Nachahmung)
        - Geschäftsmodelle sind nicht mehr linear sondern vernetzt
        - zusätzlicher Dokumentationsaufwand in Kombination mit proprietären Komponenten und Datenformaten


    === "Bildung/Lehre (Schulen, Hochschulen)"

        **Vorteile**

        - starke Interdisziplinarität
        - problemorientiertes Lernen

        **Nachteile**

        - erfordert hohe Selbstständigkeit und Kommunikationsfähigkeit


    === "Wissenschaft"

        **Vorteile**

        - Weiterentwicklung von Artefakten über Projektfinanzierung hinaus
        - Integration in die Lehre

        **Nachteile**

        - Verwertungsabsichten der Institution stehen OS evtl. entgegen


    === "Community (Maker, Privatpersonen, …)"

        **Vorteile**

        - konstengünstige Verfügbarkeit von Technologien


        **Nachteile**

        - teilweise hohes Grundlagenwissen notwendig
        - u.U. hohe Investitionen für Werkzeuge/Werkstätten notwendig zur Fertigung von OSH


    === "Öffentliche Einrichtungen"

        **Vorteile**

        - Unabhängigkeit vom Markt
        - Wissensaustausch und Problemlösungsentwicklung mit anderen Einrichtungen (überregional)
        - Hoheit über Daten

        **Nachteile**

        - erfordert Betrieb und Wartung eigener Infrastruktur


??? question "Wann ist Open Source Hardware besonders sinnvoll?"

    OSH ist besonders sinnvoll wenn

    - dezentrale Netzwerk- und Plattformeffekte wichtig sind
    - Lernen und Verstehen im Vordergrund stehen
    - Reproduzierbarkeit gefordert ist
    - Wissensaustausch und Selbstbestimmung (intrinsische Motivation) wichtig sind
    - Herstellerunabhängigkeit gewünscht ist
    - Transparenz und langfristige Verfügbarkeit wichtig sind
    - Lokale Fertigung und Anpassung erforderlich sind
    - Langfristige Wartbarkeit benötigt wird"


## Lizenzierung

??? question "Können OSH Komponenten uneingeschränkt genutzt werden?"

    Vermutlich ja. 

    Es ist allerdings genau zu untersuchen was der konkrete Lizenzgegenstand ist. OSH kann viele Arten von Dingen umfassen, welche rechtlich unterschiedlich gehandhabt werden. Nicht alle Dateien eines OSH-Repositorys sind urheberrechtlich geschützt (oder durch ein anderes Schutzrecht), wie bspw. die Stückliste eines Geräts. Diese Dateien gelten als gemeinfrei. Was also nicht Gegenstand der Lizenz ist, kann nicht durch die Lizenz geregelt werden.

    Siehe ausführliche Erklärung zur Lizenzierung von OSH.


??? question "Welche Rolle spielt eine Open Source Lizenz?"

    Eine Open Source Lizenz definiert unter welchen Bedingungen die bereitgestellten Ressourcen genutzt werden dürfen. 

    Grundlegend meint dies die Freiheiten das Werk beliebig zu nutzen, zu studieren, zu verändern und weiterzuverbreiten insb. in veränderter Form oder zu kommerziellen Zwecken gemäß den Definitionen für Open Source der Open Source Initiative (OSI) oder der Free Software Foundation (FSF).

    Diese Organisationen prüfen Lizenzen auf deren Konformität mit hinsichtlich ihrer Open Source Definitionen.

    Eine Lizenz ist rechtlich von einer Nutzungsvereinbahrung zu unterscheiden. Eine Nutzungsvereinbahrung muss aktiv akzeptiert werden. Eine Lizenz, welche auf einem Schutzrecht begründet ist, wirkt auch ohne Zustimmung.


??? question "Welche Lizenzen sind für OSH geeignet?"

    Für Open Source Hardware existieren nur wenige Lizenzen. Seit 2020 existiert mit der CERN Open Hardware License Version 2 (CERN-OHL-2) die aktuell fortschrittlichste Open Source Hardware Lizenz. Sie stellt eine grundlegende Überarbeitung ihrer Vorgängerversion dar und löst diese vollständig ab. Die CERN-OHL-2 steht in 3 Varianten zur Verfügung:

    - freizügig (permissive): CERN-OHL-P-2.0
    - schwach reziprok: CERN-OHL-W-2.0
    - stark reziprok: CERN-OHL-S-2.0

    Die CERN-OHL-2 wurde von der OSI als freie Lizenz (als aktuell einzige Open Source Hardware Lizenz) anerkannt.

    Es existieren weiterhin ältere Lizenzen, wie die TAPR Open Hardware License oder die Solderpad Hardware License. Diese Lizenzen sind aktuell nicht mehr als freie Lizenzen von OSI oder FSF anerkannt. Siehe SPDX-Standard Lizenzliste.

    Welche Lizenz konkret für die eigene Entwicklung gewählt werden sollte hängt davon ab ob fremde Ressourcen genutzt werden und was deren Lizenzen erlauben (siehe Lizenzkompatibilität). Die Wahl der Lizenz (Variante) wirkt sich allerdings auf die strategische Ausrichtung des Projekts aus.

    Siehe hierzu Lizenzwahl-Baum.


??? question "Was bedeutet Copyleft insb. für OSH?"

    Das Copyleft ist ein Mechanismus, welcher den Lizenznehmenden vorschreibt bei Integration oder Veränderung des lizenzierten Materials, dieses unter Verwendung derselben oder einer kompatiblen Lizenz wieder zu veröffentlichen. Ein schwaches Copyleft beschränkt sich hierbei auf Veränderungen am lizenzierten Material. Im Falle eines starken Copylefts wirkt sich dieses auch auf das Gesamtwerk aus (reziproke Wirkung), sodass dieses ebenfalls unter diese Lizenz (inkl. der Quellen) veröffentlicht werden muss.


??? question "Was bedeutet Lizenzkompatibilität?"

    Werden fremde Komponenten im eigenen Projekt verwendet kann es somit zu Kollisionen der Lizenzbedingungen kommen. Es ist daher auf die Kompatibilität der Lizenzen zueinander zu achten.

    Eine solche Kollision entsteht bspw. wenn eine Komponente in eine Baugruppe integriert wird. Je nach Copyleft stärke bedingt dieser Vorgang die Lizenz für die resultierende Datei der Baugruppe. Ein schwaches Copyleft beschränkt sich auf Veränderungen an der Datei bzw. Komponente. Ein Starkes Copyleft wirkt sich auf die Baugruppe aus.

    Weiterhin ist die Kompatibilität auf ihre jeweilige Domäne (Software, Hardware, kreative Werke) sowie die jeweilige Lizenzfamilie begrenzt.

    Für eine detailliertere Einordnung siehe OSH Lizenzierung.


## Haftung

??? question "Wer haftet für Schäden durch Open Source Hardware?"

    Ein genereller Haftungsausschluss ist im deutschen/europäischen Rechtsraum nicht möglich. Etwaige Regelungen einer Lizenz sind daher nur begrenzt wirksam.
    „Open Source"" findet aktuell Einzug in die Gesetzgebung.
    Zuletzt wurde mit der Novelle der Produkthaftungsrichtlinie 2024 die verschuldensunabhängige Haftung für Software allgemein als Produkt näher definiert. Im gleichen Zuge ging auch Open Source Software und damit Open Source als Begriff in die neue Richtlinie mit ein. Open Source Hardware wird aktuell noch nicht explizit erwähnt nur digitale Fertigungsunterlagen und Fertigungsprogramme werden beschrieben. Wesentliches Kriterium bildet die kommerzielle Absicht. Es sollte somit mindestens zwischen kommerziellen Produktbeschreibungen und Open Source Entwicklungsrepositorys unterschieden  und letztere als solche unbedingt gekennzeichnet werden. Weiterhin sollte zum frühest möglichen Zeitpunkt auf bekannte Gefahren oder Fehler hinsichtlich des Entwicklungsstandes transparent hingewiesen werden. Die Haftung richtig sich nach dem Leistungsversprechen und Eindruck den die Projektbeschreibung erzeugt.

    Weitere Informationen sind in der Aufzeichnung zum Webinar zur OSH Produkthaftung sowie in der dazugehörigen Präsentation zu finden.


## Dokumentation

??? question "Welche Bedeutung hat die Dokumentation bei OSH?"

    Die Dokumentation eines OSH-Projekts umfasst alle bereitgestellten Daten, die für den Nachbau und die Nutzung erforderlich sind. Eine Dokumentation kann in verschiedenen Formen erfolgen.
    
    Eine gute Dokumentation fördert vor allem:
    
    - **Nachbaubarkeit**: Ohne vollständige Dokumentation können andere das Projekt nicht nachbauen oder weiterentwickeln. Die Dokumentation ist somit das Herzstück jedes OSH-Projekts.
    - **Wissensweitergabe**: Sie ermöglicht die transparente Kommunikation von Konstruktionsdetails, Materialien, Fertigungsschritten und Designentscheidungen.
    - **Kollaboration**: Eine gute Dokumentation fördert die Zusammenarbeit innerhalb der Community und ermöglicht es anderen, Verbesserungen und Anpassungen vorzunehmen.
    - **Langfristige Verfügbarkeit**: Die Dokumentation stellt sicher, dass das Wissen auch in Zukunft zugänglich bleibt, selbst wenn die ursprünglichen Entwickler nicht mehr verfügbar sind oder Komponenten auf dem Markt nicht verfügbar sind.
    - **Qualitätssicherung**: Klare Anleitungen reduzieren Fehler beim Nachbau und erhöhen die Zuverlässigkeit des Endprodukts.
    
    Beispiele:
    
    - Minimale Dokumentation (Readme) um mit den Quelldateien arbeiten zu können
    - umfangreiche Beschreibung mit Bildern und Videos
    - Separate Dokumentationsseite (z.B. Wiki) mit detaillierten Hintergrundinformationen
    - Tutorials 
    
    Fazit: Je besser die Dokumentation, desto höher der Nutzen und die Nachhaltigkeit des OSH-Projekts für die gesamte Community.

    Für weitere detaillierte Informationen schau in unseren OSH-Guide.

<!--
## Offene Infrastruktur

??? question "Welche Rolle spielen offene Dateiformate und Software für OSH?"
-->


## Kollaboration

??? question "Wie funktioniert Kollaboration durch Open Source Projekte?"

    Durch den freien Zugang zu den Quelldateien stehen allen Akteuren zu jedem Zeitpunkt die gleichen Informationen zur Verfügung. Es kann somit sehr präzise miteinander über Funktionen und Eigenschaften kommuniziert werden. Wird ein OSH-Projekt als Repository über kollaborative Entwicklungsplattformen wie GitHub oder GitLab bereitgestellt so gibt es dort sehr niedrigschwellig die Möglichkeit per Tickets Kontakt zu den Entwickelnden aufzunehmen und in Austausch zu treten.
    Häufig ist eine E-Mail-Adresse der Beitragenden im Repository hinterlegt.

    Insb. bei OSH wird die direkte Kollaboration durch geschlossene proprietäre Dateiformate und Systeme erschwert. Es muss dann mit zusätzlichem Aufwand dokumentiert werden wie Komponenten funktionieren oder welche sonstigen proprietären Komponenten verwendet werden, welche nicht als digitales Modell im Repository frei zur Verfügung gestellt werden dürfen.

    Eine weitere Form der Zusammenarbeit entsteht durch eine intensive Nutzung bereits vorhandener OSH-Designs. Auch eine Norm-/Standardkomponente kann als OSH-Design vorliegen. Werden im Zuge der Entwicklung einzelne Komponenten verbessert oder durch zusätzliche Informationen ergänzt (z.B. Bezugsquellen, detailliertere Modelle, Materialinformationen, etc.) so stehen diese Informationen automatisch allen anderen Projekten zur Verfügung, die diese Komponenten nutzen.


## Schutzrechte

??? question "Welche Rolle spielen Schutzrechte in Open Source Projekten?"

    === "Schutzrechte"
        
        Schutzrechte spielen auch bei Open Source Projekten eine zentrale Rolle. Allerdings ist die Logik wie diese zur Anwendung kommen einen gänzlich andere als in der herkömmlichen proprietären Produktentwicklung.

        Relevante Schutzrechte:

        - Urheberrecht
        - Markenrecht
        - Designrecht
        - Patentrecht (indirekt)


    === "Urheberrecht"

        Das Urheberrecht bildet die Grundlage für die Lizenzierung der Quelldateien (parametrische CAD-Modelle, Dokumentation, Grafiken, ...) und ist in seiner Schutzdauer auf die 


    === "Design- & Patentrecht"

        Das Patentrecht schützt funktionale technische Dinge (Erfindungen), wie Funktionsprinzipien, Mechanismen, Verfahren, etc.
        Die Gestalt eines technischen Objekts, wie das Aussehen (Form, Farbe, Gestalt), Benutzeroberflächen, etc. wird durch das Designrecht geschützt. OSH-Designs können Design- oder Patentrechtlich geschützt werden wenn die grundlegenden Anforderungen zur Schutzfähigkeit erfüllt sind. Das bedeutet vor allem, dass eine Veröffentlichung erst nach Erteilung eines Schutzrechts erfolgen kann.

        Allerdings bietet der freie Austausch in OS-Projekten mit der Community gerade in der Anfangsphase großes Potential um Fehlplanungen und Investitionen zu minimieren.


    === "Markenrecht"

        Eine Marke ist wahrscheinlich das wichtigste Mittel um die Projektbezeichnung unter der sich eine Community formiert vor Nachahmung zu schützen.

        Siehe ausführliche Erklärung zur Lizenzierung von OSH.


## Kombinierbarkeit
  
??? question "Können offene und proprietäre Komponenten kombiniert werden?"

    Ja, teilweise. Es muss unterschieden werden was worin integriert wird. Weiterhin muss zwischen der digitalen und der physischen Nutzung der Komponente unterschieden werden.

    ***Werden OSH-Designs in einem proprietären Produkt verwendet?***

    OSH-Designs lassen sich vermutlich uneingeschränkt in einem proprietären Produkt nutzen. Ein proprietäres Produkt wird nur in seiner physischen Form verbreitet. Ein Copyleft beschränkt sich zunächst nur auf urheberrechtlich geschützte Quelldateien. Eine Verpflichtung zur Offenlegung der Quellen durch ein Copyleft eines physischen technischen Objekts erfordert allerdings ein zugrundeliegendes Schutzrecht. Dies ist erst durch ein Patent oder hinsichtlich des Aussehens durch ein Design gegeben. Es ist daher eine bisher nicht eindeutig geklärte Frage ob ein Copyleft im Hardware-Bereich eine Wirkung hat. Es ist alternativ auch möglich OSH-Designs per Reverse Engineering in ein anderes CAD-Format zu überführen. Es ist somit nur schwer nachweisbar auf welche Art OSH-Designs genutzt werden.

    ***Werden proprietäre Komponenten in einem OSH-Design verwendet?***

    Digitale Modelle proprietärer Komponenten werden meist nur unter der Bedingung bereitgestellt, diese nicht weiter verbreiten zu dürfen. Bei der Veröffentlichung eines OSH-Designs müssen diese proprietären Modelle also wieder entfernt werden womit das Design ein unvollständiges Fragment ist. Eine Referenzierung des Komponenten kann somit nur über die Stückliste oder eine zusätzliche Dokumentation (Bauanleitung, etc.) erfolgen. Dadurch entsteht zusätzlicher Aufwand.

    Der physischen Nutzung proprietärer Komponenten durch Zukauf steht allerdings nichts im Wege und entspricht der herkömmlichen Nutzung.


<!-- ## Wissensaufbau

??? question "Welche Auswirkungen hat Open Source Hardware auf die Aneignung und Weiterentwicklung von Wissen?" 

-->


## Finanzierung

??? question "Wie lässt sich Open Source Hardware finanzieren?"

    === "Allgemein"

        Die Kosten für eine OSH-Entwicklung lassen sich nicht direkt wie in der herkömmlichen proprietären Produktentwicklung auf die Produktion und damit auf den Stückpreis eines Produkts umlegen. Aber auch in der proprietären Entwicklung ist eine Querfinanzierung über den Absatz mit dem Risiko verbunden eine falsche Menge zu produzieren. Wird zu wenig produziert fällt der Stückpreis zu hoch aus und die abgesetzte Menge reicht nicht zur Refinanzierung. Wird zu viel produziert gelangt man zu einem niedrigen Stückpreis bleibt aber u.U. auf einer zu großen Menge sitzen, da der Markt gesättigt ist oder der Bedarf generell niedriger ist als prognostiziert. 

        Daher stellt sich die Frage wie die Produktentwicklung von der Produktion entkoppelt werden kann. Durch den generellen freien öffentlichen Zugang zu den OSH-Dokumentationen entspricht OSH einer kollaborativen digitalen gemeinfreien Wissensinfrastruktur.

        Neben einer direkten Finanzierung kommen auch Kostensenkungen und damit frei werdende Kapazitäten zur Finanzierung von OSH-Entwicklungen in Frage. 

        Für die Finanzierung von OSH-Designs ergeben sich folgende Möglichkeiten: 

        - Forschungsförderung
        - Stiftungsgelder
        - Crowdfounding & Spenden
        - Auftragsentwicklung
        - Zertifizierung von OSH-Produkten
        - Service & Support
        - Branchenverband (vgl. Open Logistics Foundation)


    === "Wissenschaft"

        Eine umfassende Förderung speziell für OSH gibt es bisher nicht.

        Der [Prototype Fund Hardware](https://prototypefund.de/) der Open Knowledge Foundation startete 2021 und 
        fördert OSH-Projekte mit bis zu 10.000 €. 

        Verglichen mit Projektvolumina in Wissenschaft & Forschung ist dieses Budget für komplexe Vorhaben oder eine konstante Beschäftigung über mehrjährige Entwicklungsphasen jedoch sehr begrenzt. 

        Eine Alternative stellt die Einreichung regulärer Förderanträge dar, bei der die Entwicklung von Open Source als integraler Bestandteil des Projekts definiert wird. Dies gelingt, indem die Veröffentlichung der Projektergebnisse explizit unter einer freien Lizenz (siehe Lizenzierung) erfolgt und die verwendeten sowie resultierenden Daten auf einer geeigneten Plattform frei zugänglich gemacht werden. Zu solchen Plattformen zählen beispielsweise Git-basierte Entwicklungsplattformen, wie [GitHub](https://github.com/), [GitLab](https://gitlab.com/) oder Instanzen nicht-kommerzieller Anbieter, wie [Codeberg](https://codeberg.org/) oder der Hochschulen sowie die [Open Source Hardware Association](https://www.oshwa.org/) oder fachspezifische Journale. 

        Auf diese Weise lassen sich verschiedene Förderprogramme für OSH nutzbar machen, darunter EU-Programme wie bspw. [Horizon Europe](https://research-and-innovation.ec.europa.eu/funding/funding-opportunities/funding-programmes-and-open-calls/horizon-europe_en), nationale Forschungsförderorganisationen oder auch Stiftungen mit Open-Source-Schwerpunkt.

<!-- 
    === "Unternehmen"

        Für Unternehmen gestaltet sich die Finanzierung für OSH schwieriger. 

-->