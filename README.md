Commande help du ModoBot :

- modifier/modif nombres/num <nombre> => modifie le nombre de majuscules invalides à la suite (permission gestion des messages requis)
- modifier/modif longeur/long <nombre> => modifie la longeur des majuscules invalides (permission gestion des messages requis)
- mute <user> => mute/démute l'utilisateur spécifié (permission gestion des messages requis)
- filter enable/disable majuscules/maj => active/désactive le filtre à majuscule (permission gestion des messages requis)
- filter enable/disable blaklist => active/désactive le filtre par blacklist (permission gestion des messages requis)
- blacklist add <mot> => rajoute un mot dans la liste des mots interdits (permission gestion des messages requis)
- blacklist del/remove <mot> => supprime un mot dans la liste des mots interdits (permission gestion des messages requis)
- blacklist list => affiche tout les mots enregistrés dans la liste des mots interdits
- avertissement/avert add <user> <message> => (permission gestion des messages requis)
- avertissement/avert del/remove <ID avertissement> => (permission gestion des messages requis)
- avertissement/avert list => affiche une liste simple de tout les avertissements\n un utilisateur sans la permission 'gestion des messages' ne peut voir que sa liste
- avertissement/avert list <user> => affiche une liste détaillé de tout les avertissements d'un utilisateur\n Un utilisateur sans la permission 'gestion des messages' ne peut voir que sa liste```"

Infos supplémentaires :

- 3 méthodes pour se prendre un avertissement : avoir des messages majuscules invalides, utiliser un mot interdit, via la commande 'avertissement add'
- la commande 'set channel' active/désactive également les filtres dans le channel de la commande