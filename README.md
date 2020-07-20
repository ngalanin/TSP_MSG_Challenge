# TSP_MSG_Challenge
Die Lösung der MSG Challenge

## Requierements

Zum ausführen des Codes ist Jupyter Notebook benötigt und Python 3.7.4.
Dazu müssen folgende Python Module Installiert werden:plotly,numpy,folium,shapely,json,openrouteservice,pandas,ortools.
Die API-key für operrouteservice könnte gebraucht werden, aber wenn die Daten von Github Repo vorhanden sind, wird API-key nicht gebraucht.

## Die Lösung:


Ich habe die operroutservice API für die Distanz- und Dauermatrix benutzt. Die API habe ich auch für die Routeerstellung benutzt.
Die Zahlen aufgerundet damit es keine Nachkommastellen gibt.

Länge der Strecke: 3185 Km

Zeit für die Reise: 32 Stunden und 41 Minuten

Solution.csv beinhaltet die Rheinfolge der MSG Stellen.

0 -> 11 -> 15 -> 18 -> 19 -> 3 -> 20 -> 7 -> 12 -> 5 -> 6 -> 14 -> 13 -> 17 -> 9 -> 10 -> 2 -> 1 -> 8 -> 4 -> 16 -> 0

Ismaning/München (Hauptsitz)->Ingolstadt->Nürnberg->St. Georgen->Stuttgart->Bretten->Walldorf->Frankfurt->Köln/Hürth->Düsseldorf->Essen->Münster->Lingen (Ems)->	Schortens/Wilhelmshaven->Hamburg->Hannover->Braunschweig->Berlin->Görlitz->Chemnitz->Passau->Ismaning/München (Hauptsitz)

Die interaktive Code könnte unter dem Link eingesehen werden:
[Code](https://nbviewer.jupyter.org/github/ngalanin/TSP_MSG_Challenge/blob/master/MSG%20Tour.ipynb)

![image of the route](https://github.com/ngalanin/TSP_MSG_Challenge/blob/master/Route.png?raw=true)

