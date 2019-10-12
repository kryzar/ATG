# Changelog

## Transformation du code

### divers
- Prise en charge d'UTF-8 et supression des accents du type `\'e` (Antoine) ;
- remplacement des \newcommand par des \DeclareMathOperator et desdists opérateurs, p. ex. `\Frac`, `\pgcd`, `\ppcm`, `\spm` (Antoine) ;
- suppression de quelques `\hspace{-0.cm}` qui ne font rien au fichier .pdf (Naomi) ;
- table des matières avec liens cliquables (Quentin) ;
- passage de la classe `amsart` à la classe `book` pour plus de lisibilité (Antoine, Quentin) ;
- en-têtes et pieds de page plus lisibles (Quentin) ;
- augmentation de l'interlignage (Antoine) ;
- légere modification des marges (Antoine) ;
- ajouts d'accents aux majuscules, p. ex. Étant au lieu de Etant (Antoine, Quentin) ;
- ajouts de titres de sections et sous-sections (Antoine) ;
- index répertorié dans la table des matières (Quentin) ;
- agrandissement des diagrammes (Antoine) ;
- remplacement des `\emptyset` par des `\varnothing` car ils sont plus jolis.

### utilisation d'environnements
Les passages comme `\textbf{Lemme}\textit{Soit $A$ un anneau…}` ont été remplacés par des environnements dédiés :
	```\begin{lemme}Soit $A$ un anneau…\end{lemme}```
cela permet une numérotation automatique sans avoir besoin de mettre une `\subsection` vide avant l'énoncé du lemme. Les parties concernées sont :
- I.1.1 ;
- I.1.2 ;
- I.5.4 ;
- I.6.

Ces transformations se font progressivement.

## Ajouts mathématiques
- Diagrammes commutatifs (Antoine).

## Corrections mathématiques
- Corrections de diverses coquilles (Antoine, Naomi, Quentin).
