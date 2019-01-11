# Projet R 

*Auteurs : Thomas FONTAINE, Dan GOLDMAN, Juliette LEMAINS et Nicolas ROBIN*

Vous trouverez dans ce répertoire plusieurs fichiers permettant de répondre à l'énoncé donné en cours d'Outils et Méthodologie.
Voici la liste des fichiers :

- Un fichier Rproj a lancer pour se trouver dans le bon répertoire.
- Un fichier parametres.R : ce fichier répertorie les différentes variables d'environnement, il inclut les base de données de travail et également les variables nécessaires aux réponses des différentes questions.
- Un fichier projet.R : ce fichier répertorie l'ensemble des fonctions réponses à chaque questions. Nous avons choisis de créer une fonction par question pour rendre le code plus structuré.
- Un fichier projet.Rmd : ce fichier construit le rapport final grace à la librairie RMarkdown. Il génère un fichier .html .
- Une image structure.png : cette image est appelée dans le RMarkdown afin d'illustrer la structure de nos bases de données.
- Un fichier chemin_a_renseigner.txt : Ou votre chemin de données est à completer (un exemple y est déjà)
- Un fichier projet.html : ce fichier est la sortie du RMarkdown. Ce fichier est considéré comme le **rapport final** de notre projet.

*Comment executer notre code ?*
Pour executer notre code, vous pouvez procéder de deux manières: 
- via projet.Rmd : Vous n'avez qu'à ouvrir le paramètre.R et remplacer la variable execution_avec_RMarkdown par **TRUE** (l.19). Après ça vous pourrez cliquer sur knit dans le markdown et le markdown sera généré automatiquement en html. Pour cette partie n'oubliez pas de préciser votre répertoire de données dans chemin_a_renseigner.txt .
- via projet.R : Si vous souhaitez regarder plus en détail notre code et les différentes executions vous pouvez vous placer dans le code projet.R . Il vous suffira d'executer la totalité du code et de vous rendre en bas du code. Vous trouverez dans la partie "EXECUTION DU CODE" (l. 644) l'appel des fonctions commenté. Vous pourrez ainsi décommenter chaque appel de fonctions pour regarder les visualisations en détails via RStudio.
