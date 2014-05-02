**Name**
Objekt in Datei

**Description**
Ein Objekt aus dem Workspace als Tabelle in eine Datei schreiben

**Usage**
Objektnamen und Dateinamen anpassen und dann die eine Zeile ausführen

**Input**
ein Objekt im Workspace von R

**Output**
eine Datei im aktuellen Arbeitsverzeichnis

**Author**
Ju

**TO DO**
Die Titelzeile muss noch so verruscht werden, dass die Titel über den Spalten stehen.
Die Zahlen müssen alle mit Nachkommastellen dargestellt werden, also evt, mit Nullen.

```{r}
write.table(wetter,file="wetterdaten_neu.txt", sep="\t")
```

