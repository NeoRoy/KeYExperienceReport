Die Spezifikationen aus Bereinigt und Redux-Problematik sind identisch.
Da in JavaRedux die Klassen Collection, List und Iterator enthalten sind, wurden diese in Bereinigt umbenannt.
Dadurch k�nnen diese Spezifikationen auch in KeY ge�ffnet werden.

Hierf�r ist jedoch eine Anpassung an JavaRedux notwendig.
Der java.lang.Object-Klasse muss die Signatur der getClass-Methode hinzugef�gt werden:

	native Class getClass(); 