---
title: "Snippets für Email"
draft: true
image: "img/agenda.jpg"
showonlyimage: false
categories: ["Tech"]
tags: ["editoren", "emacs"]
topics: ["snippets"]
weight: 1
---

Outlook ist für mich ein mühsamer Weg um Emails zu schreiben. Leider kann ich im
Moment nicht Mu4e im Geschäft verwenden. Als Schmerzlinderung kommt Yasnippet ins Spiel.

<!--more-->

Ich arbeite in einer reinen Windows zentrierten Firma. Bin kein Programmierer,
liebe aber Modaleditoren. Besser gesagt Spacemacs im Evil Mode.

[Spacemacs](http://spacemacs.org/) ist eine Konfiguration von Emacs, mit Vim-Keybindings. Eine massive
Zahl von Befehlen ist über die Space Taste zu erreichen. Sie basieren auf
Mnemonics. Das heisst, zum Speichern eines Files, drücke ich `Space-f-s`, usw.
Im Netz finden sich unzählige Tutorials und Blogbeiträge über Emacs und
Spacemacs. 

Die meisten Nutzer sind natürlich Software-Entwickler. Trotzdem sind so viele
nützliche Tools für Emacs geschrieben worden, dass es fast schon ein eigenes
Betriebssystem ist.


\`\`\`
# -*- mode: snippet -*-
# name: mail
# key: mail
# --
Guten Tag liebe$1

$0

Mit freundlichen Grüssen
Hans Muster
Muster AG
Beispielhausen
\`\`\`

Inzwischen habe ich dieses Snippet noch ein wenig verfeinert und benutze noch
andere Bausteine nach _$0_ Sprungpunkt. 

Wenn die Mail dann fertig verfasst ist, Space-b-Y. Das kopiert den ganzen Buffer ind den Zwischenspeicher und kann ihn mit Crtl-v in Outlook einfügen.

Das Schreibgefühl in Spacemacs ist einfach besser. 
