# ConTeXt Intro

ConTeXt ist eine leistungsfähige Alternative zu LaTeX.
Leider fehlt eine kompakte Einleitung, die beim Einstieg hilft.

Diese Dokument soll dies Lücke schließen.

Es ist bewußt kurz gehalten, daher werden viele Fähigkeiten nur angerissen. 
Weiter Informationen gibt es im 
[Contextgarden](https://wiki.contextgarden.net/Main_Page), allerdings nur in 
englisch.

Das PDF zeigt die Syntaxhervorhebung mit dem Modul vim.
Da nicht alle Nutzer einen Vim installiert haben,
ist der Abschnitt standardmäßig deaktiviert.
Um dem Abschnitt zu erzeugen, muss das `%` Zeichen in der Zeile entfernt 
werden.

~~~
% \enablemode[Vim]
~~~

Das PDF zeigt die Einbindung von externen Zeichensätzen.
Da nicht alle Nutzer diese Zeichensätze haben,
ist der Abschnitt standardmäßig deaktiviert.
Um dem Abschnitt zu erzeugen,
muss das `%` Zeichen in der Zeile entfernt werden 
und die entsprechenden Zeichensätze müssen installiert werden.

Es handelt sich um die Zeichensätze 
[Vollkorn](http://vollkorn-typeface.com) und 
[Mandala](http://www.softerviews.org/Fonts.html)

Außerdem wird der Zeichensatz Optima benutzt, der zum Lieferumfang von macOS 
gehört.

~~~
% \enablemode[Fonts]
~~~


# TODO

 *  Unterschiedliche environments (Design, Fonts)
 *  Define / Setup Beispiele und Erklärungen (JUH)
 *  Logo im Hintergrund

# DONE

 *  Fuß- und Endnoten
 *  Bibliography
 *  Klammern eckig / geschweift (JUH)
 *  Tabulate erklären (wg. Mathematik)
 *  Bilder drehen: Beispiele ergänzt
 *  PDF/A
