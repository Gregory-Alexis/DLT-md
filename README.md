# DLT-md

```1
Pour gérer le cas ou le nombre de block est impair dans un merkle root,
il faut combiner la dernière empreinte avec elle même.  
Ex: Hopop = h(Hop + Hop)
Il ne restera donc qu'une seule empreinte qui sera appelé dans la racine de Merkle
```

```2
Il arrive à retrouver ses pair en se synchronisant avec les noeuds déjà existant,
 c'est à dire en échangeant des informations pour qu'ils puissent
fonctionner de manière coordonnée
```

```3
Nick Szabo est l'inventeur du smart contract.

Hall Finney a été l'un des premiers utilisateurs du bitcoin
et a reçu la première transaction de la part du créateur du bitcoin, Satoshi Nakamoto.
```

```4
Le type de donnée qui pourrait représenter une blockchain est le 'Linked List':

1) Les 2 ressemble à une list reliée par un lien

2) Dans la Linked list le pointeur(le lien représenté dans la link list) 
stocks l'adresse du noeud ou du block suivant.
il est utilisé pour passer au noeud suivant et le dernier noeud à un pointeur nul(sans valeur)

3)Dans Blockchain, le lien est appelé un pointeur de hachage. 
Le pointeur de hachage n'est pas seulement utilisé pour rechercher le bloc précédent de la transaction, 
mais aussi pour vérifier que les transactions stockées dans le bloc précédent ne sont pas altérées. 
Le pointeur de hachage est la valeur de hachage des données d'en-tête du bloc précédent. 
```

```6
Non, car il faudrait recalculer le bloc dans lequel se trouve tout les blocks dans lequel elle se trouve.
Ce qui voudrait dire que si toute le fois le bloc qui contient les informations de la transaction,
est le dernier, il faudrait un effort énorme pour y parvenir.
```

