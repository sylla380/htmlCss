# Html CSS

Un fichier CSS permet de changer radicalement l'affichage de plusieurs pages HTML.
La structure d'un fichier CSS est simple (plus que celle d'un fichier HTML).
Chaque règle CSS sert à appliquer des styles à une balise HTML, certaines balises, ou un groupe de balises ;
Chaque règle d'un fichier CSS débute par un sélecteur. Il s'agit de la ou les balises concernées par la règle. On y place le nom des balises ou une expression permettant de sélectionner les balises concernées ;
Ensuite, entre accolades (entre { et }), on définit une liste de déclarations (couples "propriété: valeur") afin d'appliquer certains effets graphiques aux balises sélectionnées. Ces déclarations sont séparés par des point-virgules (;).

## selecteur

Un sélecteur permet de définir à quelles balises un style donné doit être appliqué.
Concrètement, voici la liste des sélecteurs possibles accompagnés d'exemples.
Les sélecteurs peuvent être combinés pour effectuer un "filtrage" plus précis des balises auxquelles appliquer le style que vous souhaitez.

###selecteur de type Balise
Indiquer le nom d'une balise permet de restraindre la règle à un seul type de balise.
Ainsi, pour colorer tous les liens de la page (balises "a") en bleu, vous pouvez suivre cet exemple :

### selecteur attribut
Les sélecteurs d'attribut permettent de cibler un élément selon la présence d'un attribut ou selon la valeur donnée d'un attribut.

### selecteur d'ID
Un sélecteur d'identifiant (ID selector) permet, pour un document HTML, de cibler un élément grâce à la valeur de son attribut id.
Il faut que la valeur soit exactement la même que celle du sélecteur pour que l'élément soit effectivement ciblé.
### selecteur class
Les sélecteurs de classe CSS permettent de cibler des éléments d'un document en fonction du contenu de l'attribut class de chaque élément.
L'attribut class est une liste de termes séparés par des espaces,
il est nécessaire qu'un de ces termes corresponde exactement au nom utilisé dans le sélecteur pour que l'élément soit ciblé.
