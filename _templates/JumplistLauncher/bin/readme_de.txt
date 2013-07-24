Jumplist-Launcher v7 (C) 2009 von Hedgehog
==========================================

Die komplett �berarbeitete Taskbar von Windows 7 bietet einige 
Features die den Workflow unter Windows erheblich
verbessern. Unter Ihnen ist die so genannte JumpList, die erscheint 
wenn auf ein Icon in der Superbar rechts klickt.
Wenn man allerdings mehrere Programme unter einem Icon zusammenfassen 
will geht man leer aus.
Mit dem 'Jumplist-Launcher' kann man eigene Jumplisten erzeugen, die 
aus bis zu 60 Programmen, Dateien und Ordner bestehen
und in selbst definierte Gruppen angeordnet sind.


1. Versionshistorie
-------------------
Version 7:
- Es kann nun ein Standard-Eintrag ausgew�hlt werden, der bei einem Linksklick auf das Superbar-Icon
  ge�ffnet wird. In dem Fall wird der Jumplist ein Eintrag hinzugef�gt um das Konfigurationsfenster
  des Jumplist-Launchers �ffnen zu k�nnen
- Die Oberfl�che wurde erneut �berarbeitet (vielen Dank an Heiko Eckendorf f�r das Konzept)
- Der Fehler, dass einige Leute keine Jumplist (oder Tasklist) erstellen k�nnen ist nun endlich behoben

Version 6:
- Jedem Element k�nnen jetzt Parameter hinzugef�gt werden (macht nat�rlich nur bei ausf�hrbaren Dateien Sinn)
- per Drag'n'Drop eingef�gte Verkn�pfungen werden nun aufgel�st. Das schlie�t ihre Parameter mit ein.
- Wenn ein Icon nicht mehr vorhanden ist wird es gegen ein Standard-Icon ersetzt
- Die Oberfl�che und der Workflow beim Einf�gen von Dateien wurden �berarbeitet
- Leute die nicht die Max. Anzahl der Jumplist-Items anpassen konnte, sollten dies nun tun k�nnen

Version 5:
- Die Gruppen und Eintr�ge k�nnen nun per Drag'n'Drop verschoben werden
- Beim L�schen in der Liste geraten die Icons nicht mehr durcheinander
- Beim hinzuf�gen von Dateien �ber den Dateibrowser wird nun das korrekte Icon �bernommen

Version 4:
- Man kann nun optional statt der normalen Jumpliste eine Aufgabenliste erzeugen. Diese hat den Vorteil, dass
  die maximale Anzahl ihrer Eintr�ge nicht an der, der zuletzt verwendeten Dateien gebunden ist. Leider scheint
  es aber keine Einstellung zu geben bei der man festlegt wie viele Tasklisten-Eintr�ge es maximal geben soll
- das teilweise seltsame Verhalten wenn man Eintr�ge im Treeview hoch und runter bewegt (z.B. Dateien werden zu Gruppen)
  wurde behoben
- man kann nun mehrere Eintr�ge gleichzeitig nach oben und unten bewegen
- Wenn der icons-Ordner nicht existiert wird er erschaffen (das behebt den "Datei �...\iconInfo.dat� kann nicht 
  erstellt werden." Fehler)

Version 3:
- Ab sofort kann man eine Datei (leider keine Ordner) auch ohne direktes Starten
  des Jumplist-Launchers in die Liste aufnehmen. Dazu zieht man die Datei einfach
  auf das Symbol in der Taskleiste und h�lt beim loslassen die Shift-Taste gedr�ckt
- die Icons von Ordnern k�nnen ver�ndert werden
- ein Fehler wurde behoben durch den die Icons durcheinander geraten sind wenn man
  einen Ordner gel�scht hat 
- Der �Fehler beim Holen der Daten�� wird nicht mehr auftreten, stattdessen wird das
  Setzen der Anzahl der maximalen Jumplist-Eintr�ge einfach deaktiviert 

Version 2:
- bis zu 60 (bisher 10) m�gliche Jumplist-Eintr�ge, die maximale Anzahl 
  an Eintr�gen in der Jumpliste l�sst sich im Programm selbst �ndern
- Eintr�ge die hinzugef�gt werden, erscheinen nun in der richtigen Gruppe
- Ordner k�nnen auch der Liste hinzugef�gt werden

Version 1:
- Erstver�ffentlichung


2. Features
-----------
- keine Installation, kein M�ll in der Registry
- Jumplisten mit bis zu 60 Programmen oder Dateien erzeugen, die direkt ge�ffnet 
  werden k�nnen
  (Hinweis: die Einstellung  der maximalen Anzahl der Jumplist-Eintr�ge kann nur
  global f�r das gesamte Windows ge�ndert werden)
- Jeder Datei k�nnen Startparameter �bergeben werden 
- Eintr�ge in der Jumplist k�nnen gruppiert werden
- Ein Eintrag kann festgelegt werden, der beim Anklicken des Superbar-Icons des
  Jumplist-Launchers ge�ffnet wird
- Wenn die Jumpliste angelegt wurde, muss der 'Jumplist-Launcher' nicht im 
  Hintergrund weiterlaufen
- Durch Kopieren des Jumplist-Launcher Ordners kann man mehrere Icons auf der 
  Superbar haben mit verschiedenen Eintr�gen
- Dateien k�nnen direkt aus dem Windows-Explorer in das Programm gezogen werden 
  um sie zur Liste hinzuzuf�gen
- Die Icons und Namen der Eintr�ge k�nnen frei gew�hlt werden
- Auf 'Create Jumplist' klicken um die Jumplist zu erzeugen und alles zu speichern
- Eintr�ge k�nnen  hinzugef�gt werden indem man einzelne Dateien auf das Taskbar-Symbol 
  des Jumplist-Launchers zieht und beim loslassen die Shift-Taste dr�ckt.

3. Vorraussetzungen
-------------------
- Microsoft Windows 7 RC (build 7100 oder h�her)


4. Benutzung
------------
- Jumplist-Launcher.exe starten
- Gruppen hinzuf�gen mit 'Add Group', Die Gruppen k�nnen direkt durch klicken 
  auf den Namen im Treeview ver�ndert werden
- Dateien, Ordner oder Programme hinzuf�gen durch klicken auf '...' oder sie einfach 
  vom Windows-Explorer ins Programm ziehen
- Gruppen und Eintr�ge k�nnen neu organisiert werden indem man sie selektiert 
  und dann den hoch oder runter-Button anklickt
- Wenn n�tig die Anzahl der maximalen Jump-List-items �ndern
- Auf 'Create Jumplist' klicken um die Jumplist zu erzeugen und alles zu speichern
- Das Programm an die Superbar anheften
- Programm schlie�en


5. bekannte Fehler
------------------
- Wenn man die Anzahl der maximalen Jumplist-Eintr�ge ver�ndert, dann �ndert sich zugleich die Anzahl
  der zuletzt benutzten Datei
  Dieser Fehler kann im Moment nicht behoben werden, da beide Werte durch nur einen Wert in der Registry
  repr�sentiert werden


6. To-Do
--------
- mehrere Eintr�ge in der Superbar die unterschiedlichen Dateien/Ordnern
  enthalten mit nur einer Instanz des Jumplist-Launchers
- Einstellungen speichern als XML-Datei
- irgendwelche Ideen?


7. FAQ
------
Q: Im Programm treten seltsame Fehler auf
A: Die Daten enthalten wahrscheinlich Fehler. L�schen Sie den ganzen Inhalt des Icon-Ordner, aber nicht
   den Ordner selbst und die Datei 'settings.dat' aus dem Jumplist-Launcher-Ordner

Q: Wie kann ich dem Eintrag des Jumplist-Launchers der an die Superbar gepinnt ist ein eigenes Icon zuweisen?
A: Erstellen Sie eine Verk�pfung der Exe-Datei und ziehen Sie diese auf die Superbar. In den Eigenschaften
   der Verkn�pfung k�nnen Sie manuell ein Icon zuweisen

Q: 60 Dateien/Programme nur? ...Ich will mehr!
A: Kopieren Sie den gesamten Jumplist-Launcher-Ordner irgendwo anders hin.
   Beide Jumplist-Launcher.exe benutzen unterschiedliche Daten. Deshalb k�nnen Sie ihnen unterschiedliche
   Dateien/Programme zuweisen.

8. Kontakt
----------
Vorschl�ge, Kritik oder Problemberichte gehen in meinen Blog unter www.ali.dj/jumplist-launcher :)