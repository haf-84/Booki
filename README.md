
Projet 2 Booki Décembre 2022 - Openclassrooms. 

Voici l’ensemble des points fonctionnels et techniques à prendre en compte pour le développement du nouveau site Booki. L’ensemble de ces éléments a été validé par l’équipe Produit, il est donc important de les respecter.

1. Spéciﬁcations fonctionnelles et contraintes techniques: <br>

1.1 Fonction recherche: <br>
●	Les usagers pourront rechercher des hébergements dans la ville de leur choix. <br>
●	Le champ de recherche est un champ de saisie, le texte doit donc pouvoir être édité par l’utilisateur. <br>
●	Il faut englober ce champ dans un formulaire. La partie Recherche ne doit pas être fonctionnelle - il s’agit d’une première version pour valider l’interface.<br>
<br>
1.2 Cartes hébergements et activités:<br>
●	Chaque carte d’hébergement ou d’activité devra être cliquable dans son intégralité (pas uniquement le titre).<br>
●	Pour l’instant, les liens sont vides. On peut utiliser un attribut `href=”#”` pour simuler la présence d’un lien. <br>
<br>
1.3 Filtres de recherche:<br>
●	Les hébergements peuvent être ﬁltrés par thématique, comme le budget ou l’ambiance.<br>
●	Les ﬁltres doivent changer d’apparence au survol. Par contre, ils ne doivent pas être fonctionnels - il s’agit d’une première version pour valider l’interface. <br>

1.4 Liens “Hébergements” et “Activités”:<br>
● Les textes “Hébergements” et “Activités”, situés dans l’en-tête, sont des liens. Ils doivent mener respectivement vers la section “Hébergements à Marseille” et “Activités à Marseille”.<br>

2. Spéciﬁcations techniques:<br>

2.1 Maquettes:<br>
●	Trois maquettes ont été réalisées : desktop, tablette et mobile.<br>

2.2 Breakpoints:<br>
Nous avons convenu avec le designer UI d’utiliser 992 px et 768 px :<br>
●	>=992 px pour les écrans d’ordinateurs ;<br>
●	>=768 px pour les tablettes ; <br>
● et tout ce qui est en dessous de 768 pour les téléphones portables.<br>

2.3 Largeur max: <br>
Pour éviter d’étirer la page web sur la largeur de façon excessive, il va falloir déterminer une largeur maximum de 1 400 px.<br>

2.4 Desktop first: <br>
Il faut d’abord réaliser l’intégration pour les ordinateurs (autrement dit, en desktop ﬁrst), puis les tablettes et enﬁn les téléphones. L’utilisation des Media Queries nous permettra de réaliser l’intégration pour les différents supports.<br>

2.5 Bibliothèque d'icônes: <br>
Les icônes proviennent de la bibliothèque Font Awesome.<br>

2.6 Couleurs:<br>
Les couleurs de la charte sont le bleu (#0065FC), une version plus claire de ce bleu (#DEEBFF) et le gris pour le fond (#F2F2F2).<br>

2.7 Police:<br>
La police du site est Raleway. Nous pouvons passer par Google Fonts pour importer facilement cette police dans le code : https://fonts.google.com/specimen/Raleway.<br>

2.8 Mise en page:<br>
Il est recommandé d'utiliser Flexbox.<br>

2.9 Balises sémantiques<br>
Il est important d’utiliser des balises sémantiques, au minimum “header”, “nav”, “h1-h2-h3”, “main”, “section”, “article” et “footer”.<br>

2.10 Validité du code: <br>
●	Aﬁn d’harmoniser les outils avec toute l’équipe, il faudra utiliser l’IDE Visual Studio Code pour le développement du site.<br>
●	Le code doit être valide aux validateurs W3C HTML et CSS.<br>
●	Le code HTML ne doit pas contenir de propriété CSS.<br>
●	Lors du passage du desktop au mobile et à la tablette, ne pas dupliquer le code HTML (exception faite dans le formulaire avec le mot “Rechercher” et l’icône de la loupe).<br>
●	Privilégier l’utilisation des classes CSS pour cibler un élément, plutôt que d’utiliser le nom de l’élément lui-même.<br>
●	Ne pas dupliquer des classes CSS inutilement. Exemple : si 4 éléments sont identiques du point de vue de la mise en forme, alors utiliser une seule et même classe CSS, et non pas 4.<br>

2.11 Compatibilité navigateurs<br>
La maquette doit être compatible avec les dernières versions de Google Chrome et de Mozilla Firefox. Il faudra tester la page web sur ces deux navigateurs.<br>

2.12 Restrictions: <br>
●	Aucun framework CSS (type BootStrap ou Tailwind CSS) ou préprocesseur CSS (type Sass ou Less) ne doit être utilisé.<br>
●	Aucun autre langage ne doit être utilisé (comme JavaScript, par exemple).<br>












# Formation2-_P2_Booki
