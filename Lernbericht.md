# Lern-Bericht
Delia Reho

## Einleitung

In diesem Projekt ging es darum, mittels Escaping Cross-Site-Scripting zu vermeiden.

## Was habe ich gelernt?

Ich habe gelernt, wie man Sonderzeichen ins HTML einfügen kann, sodass sie nicht als HTML-Text selbst aufgenommen werden.

## Beschreibung

Manchmal wenn man Tabs, Grösser- und Kleinerzeichen in einer HTML-Datei verwendet, wird es als HTML-Code aufgenommen, obwohl man es eigentlich auf der Webseite darstellen möchte. 
Um dies zu umgehen, benutzt man "Escaping". Dieses Escaping ist eine gegebene Zeichenstellung, die diese Sonderzeichen ersetzt, sodass sie als Webseiten-Inhalt erkannt werden. Zum Beispiel ist "<" auch "&amp;lt;" und ">" ist "&amp;gt;". (Hier musste ich auch Escaping benutzen um die &-Zeichen darzustellen, sonst werden sie direkt als < oder > angezeigt)
Diese Ersätze kann man auch überall im Internet nachschauen, wenn man diese nicht im Kopf behalten kann.

    <h1>So habe ich ein Video in HTML eingefügt:</h1>
    &lt;video autoplay loop id="bgvideo"&gt;
    <p>&lt;source src="bgvideo.mp4" type="video/mp4"&gt;
    <p>&lt;source src="bgvideo.ogg" type="video/ogg"&gt;
      
* Link zu einem selbstaufgenommenen YouTube Video: https://youtu.be/BtGljhiTfm8

## Verifikation

In meinem Textbeschrieb, sieht man, dass ich weiss, was Escaping ist und wieso man es verwendet. Ich habe auch eine Lösung vorgeschlagen, wie einfach es ist, die Escaping-Charaktere zu finden.
Im Code Ausschnitt und im Video sieht man, wie ich Escaping anwende und ein gutes Beispiel für wann es benutzt werden könnte. Dieses Beispiel habe ich mir selbst ausgedacht.

# Reflektion zum Arbeitsprozess

An diesem Auftrag lieft meist alles gut, da ich es sehr gut verstanden habe und es ein einfacher Auftrag war.
Jedoch was nicht so gut lief, war, dass ich sehr viel Zeit damit verbracht habe, die Lösung zu finden. Beim ersten Erledigen eines Escaping-Auftrags war ich unsicher, nach was ich suchen muss und was die richtige Lösung ist.

**VBV**: Ich werde meine Mitschüler und Lehrpersonen nach Hilfe fragen, sodass ich nicht hilflos nach einer Lösung suche, bei der ich nicht weiss was die Lösung alles beinhaltet.
