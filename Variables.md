## Variables


boolean : Une variable de type bool�en qui ne peut prendre que deux valeurs : True (vrai) ou False (faux). Utilis�e pour les conditions ou les boucles qui n�cessitent une v�rification de v�rit�.


integer : Une variable de type entier qui contient des nombres sans partie d�cimale. Utilis�e dans les calculs, les boucles etc.


float : Une variable de type flottante qui contient des nombres avec une partie d�cimale. 


double : Similaire au float mais avec une plus grande pr�cision.


string : Une variable de type cha�ne de caract�res utilis�e pour stocker du texte (peut contenir des mots, des phrases, suites de caract�res).


char : Une variable qui stocke uniquement un caract�re.


struct : Une variable permet de regrouper plusieur variables sous un m�me nom, pouvant contenir des types diff�rents.


```c#
struct Coordonnees
{
public int x;
public int y;
}
```


enum : La variable enum (�num�ration) est utilis� pour d�finir un ensemble de constantes nomm�es.


```c#
enum Couleur
{
Rouge,
Vert,
Bleu
}
Couleur maCouleur = Couleur.Rouge;
```