# Changelog

## Transformation du code
- prise en charge d'UTF-8 et supression des accents du type `\'e` (Antoine)
- remplacement des \newcommand par des \DeclareMathOperator et desdists opérateurs, e.g. `\Frac`, `\pgcd`, `\ppcm`, `\spm` (Antoine)
- suppression de quelques `\hspace{-0.cm}` qui ne font rien au fichier .pdf (Naomi)
- table des matières avec liens cliquables (Quentin)
- passage de la classe `amsart` à la classe `book` pour plus de lisibilité (Antoine, Quentin)
- remplacement progressif des `\textbf{Lemme}` au profit d'environnements dédiés (Antoine, Quentin), ce qui permet de supprimer les `\subsubsection` vides
- en-têtes et pieds de page plus lisibles (Quentin)
- augmentation de l'interlignage (Antoine)
- légere modification des marges (Antoine)

## Ajouts mathématiques
- diagrammes commutatifs (Antoine)

## Corrections mathématiques
- corrections de diverses coquilles (Antoine, Naomi, Quentin)

## Divers
- ajout d'un fichier .gitignore permettant de ne pas inclure les fichiers inutiles (issus de la compilation ou du système d'exploitation, comme les .aux et .log) dans le dépôt (Naomi)
