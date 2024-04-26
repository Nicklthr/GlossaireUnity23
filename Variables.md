## Variables


boolean : Une variable de type booléen qui ne peut prendre que deux valeurs : True (vrai) ou False (faux). Utilisée pour les conditions ou les boucles qui nécessitent une vérification de vérité.


integer : Une variable de type entier qui contient des nombres sans partie décimale. Utilisée dans les calculs, les boucles etc.


float : Une variable de type flottante qui contient des nombres avec une partie décimale. 


double : Similaire au float mais avec une plus grande précision.


string : Une variable de type chaîne de caractères utilisée pour stocker du texte (peut contenir des mots, des phrases, suites de caractères).


char : Une variable qui stocke uniquement un caractère.


struct : Une variable permet de regrouper plusieur variables sous un même nom, pouvant contenir des types différents.


```c#
struct Coordonnees
{
public int x;
public int y;
}
```


enum : La variable enum (énumération) est utilisé pour définir un ensemble de constantes nommées.


```c#
enum Couleur
{
Rouge,
Vert,
Bleu
}
Couleur maCouleur = Couleur.Rouge;
```