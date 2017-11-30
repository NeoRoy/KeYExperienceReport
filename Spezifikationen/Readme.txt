Die Spezifikationen aus Bereinigt und Redux-Problematik sind identisch.
Da in JavaRedux die Klassen Collection, List und Iterator enthalten sind, wurden diese in Bereinigt umbenannt.
Dadurch können diese Spezifikationen auch in KeY geöffnet werden.

Hierfür ist jedoch eine Anpassung an JavaRedux notwendig.
Der java.lang.Object-Klasse muss die Signatur der getClass-Methode hinzugefügt werden:

	native Class getClass(); 