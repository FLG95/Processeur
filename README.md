Fichier principale : CyProcessingUnit.circ

&#x09;Circuit main : combinaison du bloc ALU, Du banc de registre, des différentes RAM et du décodeur





Fichier ALU : ALU.circ

&#x09;L'ALU et ses différents module



Fichier registre : RegisterLib.circ





Sélecteur sur 5 bits :

2 premier bits de poids fort = sélection du module
3 premier bits de poids faible = sélection de l'opération dans le module



En cas de problème de library manquante à l'ouverture du fichier principale il faut juste sélectionner le fichier comprenant le module manquant (ex : il manque OpératorLib, il faut cliquer sur ComparatorAndOperatorLib).



voir le fichier binding.txt pour les input output du décodeur.

