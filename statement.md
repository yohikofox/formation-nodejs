# Créez un script Node.js qui utilise un stream de lecture pour lire un fichier texte volumineux et affichez son contenu sur la console.

Objectif : Écrire un script Node.js qui utilise un stream de lecture pour lire un fichier texte volumineux et afficher son contenu sur la console.

Instructions :

1. Créez un fichier texte volumineux avec un contenu aléatoire ou utilisez un fichier existant. Par exemple, vous pouvez créer un fichier texte de 10 Mo en utilisant la commande suivante :    
```bash
dd if=/dev/urandom of=output.txt bs=1M count=10    
```
2. Créez un script Node.js qui utilise un stream de lecture pour lire le contenu du fichier texte volumineux et afficher son contenu sur la console.
    
3. Utilisez le module `fs` de Node.js pour créer un stream de lecture pour le fichier texte volumineux.
    
4. Attachez un gestionnaire d'événements `data` pour le stream de lecture qui s'exécute à chaque fois qu'un morceau de données est disponible à partir du flux.
    
5. Utilisez la méthode `console.log()` pour afficher le contenu du fichier sur la console.
    
6. Testez votre script en exécutant la commande `node script.js` dans un terminal.
    

Contraintes :

- Vous ne pouvez pas utiliser de modules externes autres que `fs`.
- Vous devez utiliser un stream de lecture pour lire le fichier texte volumineux.

Bonus :

- Ajoutez un gestionnaire d'événements pour l'événement `end` du stream de lecture pour afficher un message indiquant que la lecture est terminée.
- Ajoutez un gestionnaire d'erreur pour le stream de lecture pour afficher une erreur en cas de problème de lecture du fichier.
- Utilisez des options de flux pour améliorer les performances du script, telles que l'utilisation d'un buffer de lecture plus grand.

Bon courage !