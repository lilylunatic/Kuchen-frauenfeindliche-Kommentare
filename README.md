# Kuchen-frauenfeindliche-Kommentare
Eine Analyse der Top tausend meistgeliketesten Kommentare unter KuchenTVs Video **Die 100% WAHRHEIT zur Gina Thematik. Habe ich sie geschlagen?** in dem er zugibt gegen seine Parterin Gewalt angewendet zu haben.
## 1. Methodik
Ich habe mir am 26.11.2021(10:43) und 27.11.2021 (10:50) alle Kommentare von KuchenTV Video "[Die 100% WAHRHEIT zur Gina Thematik. Habe ich sie geschlagen?](https://web.archive.org/web/20211126092349/https%3A%2F%2Fwww.youtube.com%2Fwatch%3Fv%3Dc186Z0zXo_E)" (web.archive.org snapshot vom 26.11.2021) gesichert, diese dann mit [Microsoft PowerBi](https://powerbi.microsoft.com/de-de/) (ein Datenanalysetool) in tabellarische Form gebracht, nach likes (absteigend) sortiert und anschließend die tausend Kommentare mit den meisten likes (absteigend nach likezahl sortiert) analysiert. Hierzu bekam jede zeile mit einem Frauenfeindlichen KOmmentar unter der Spalte "frauenfeindlich" eine 1 eingetragen, sodass die Spalteneinträge unter "frauenfeindlich" für die Summe an frauenfeindlichen Kommentaren einfach summiert werden kann ([Tabelle angehängt](https://github.com/Benji7103/Kuchen-frauenfeindliche-Kommentare/blob/main/Kuchen%20Kommentare.xlsx)).
### 1.1 Was ist frauenfeindlich?
KuchenTV ist in dieser Situation sehr eindeutig Täter, er hat Gewalt angewendet, das drei Jahre lang vertuscht, Feminist:innen für seine Falschaussage(n) verklagt und sogar Kopfgelder ausgesetzt.
Kommentare ,die mehr Solidarität mit ihm als mit den Opfern zeigen, die häusliche Gewalt relativieren, die sein Verhalten als *stark* darstellen, die ihm Mitleid für das *verlieren* im Beef ausprechen und jene die mit *aber wenn ne frau das machen würde* anfangen (weil gewalt gegen Frauen ein eindeutiges, **sexistisches** Problem ist).
### 1.2 Wie kam ich an die Kommentare?
Am 26.11. habe ich die mittels [youtuberandomcomment](https://youtuberandomcomment.com/) als JSON ausgeben lassen.

Am 27.11. gestaltete sich das schwieriger weil ich statt einer Datei nur dieses Pop-Up bekam [das pop up - Screenshot nachgestellt](https://github.com/Benji7103/Kuchen-frauenfeindliche-Kommentare/blob/main/Screenshots/Screenshot%20from%202021-11-28%2016-10-01.png)

Das sieht nicht nur wie ein Error aus, sonder ist auch einer wie ein Blick in die Browser Konsole verrät ![Der Error in der Konsole - Screenshot nachgestellt](https://github.com/Benji7103/Kuchen-frauenfeindliche-Kommentare/blob/main/Screenshots/Screenshot%20from%202021-11-28%2016-12-43.png)

Deswegen wurden die Kommentare am 27.11. mittels des cli tools [https://github.com/egbertbouman/youtube-comment-downloader](https://github.com/egbertbouman/youtube-comment-downloader) gesichert, weshalb die formate der Rohdaten leicht unterschiedlich sind. ![Ja das runterladen hat ne Weile gedauert - Originalscreenshot](https://github.com/Benji7103/Kuchen-frauenfeindliche-Kommentare/blob/main/Screenshots/Screenshot%20from%202021-11-27%2011-18-21.png)
## 2. Ergebnisse
### 2.1 vom 26.11. 
Im Schnitt sind 42,9% der top tausend am meisten geliketen Kommentare frauenfeindlich, das sind ca. 2 von 5 Kommentaren ![Das sieht dann so aus ach du schreck](https://github.com/Benji7103/Kuchen-frauenfeindliche-Kommentare/blob/main/Ergebnisse%20-%20Visualiert/26%2011%202021%20Grafik.png)
### 2.2 vom 27.11.
Im Schnitt sind 32,3% der top tausend am meisten geliketen Kommentare frauenfeindlich, das sind ca. 1 von 3 Kommentaren ![Das sieht dann so aus - besser aber immer noch nicht gut](https://github.com/Benji7103/Kuchen-frauenfeindliche-Kommentare/blob/main/Ergebnisse%20-%20Visualiert/27%2011%202021%20Grafik.png)
In anderen Worten: nach 24h sieht die Kommentarsektion zwar deutlich besser aus, _gut_ ist allerdings was anderes.
