# SWR-lab1-STP
> 1. Pourquoi l’utilisation de STP est-elle nécessaire avec une telle topologie réseau ?

Car une boucle existe entre les switchs.
> 2. Est-ce que les switches utilisés dans cette simulation ont STP activé par défaut ? Justifiez votre réponse avec une capture WireShark du trafic entre les switches.

> 3. Quelle est la di érence entre la topologie initiale et celle ci-dessous ?

> 4. Comment est élu le root bridge dans notre cas, étant donné qu’aucune priorité n’est configurée ? 

> 5. Trouvez l’adresse MAC de chacun des switches dans le réseau que vous avez simulé. Aidez-vous de la commande show interfaces.

> 6. Pourquoi y’a-t-il plusieurs adresses MAC sur un switch ?

> 7. En vous basant sur votre réponse, qui devra être le switch élu dans votre réseau?

> 8. Vérifiez votre réponse à l’aide des paquets STP échangés et joignez une capture d’écran.

> 9. Créez un schéma du réseau et représentez le switch racine ainsi que les ports racines, désignés et bloqués en utilisant les connaissances acquises en cours. Indiquez également le chemin que devrait emprunter un ping entre PC1 et PC2. Prouvez-le en e ectuant le ping et en joignant une capture d’écran (en capturant entre S1 et S4 ou S1 et S3 par exemple).

> 10. En milieu de boucle (entre deux autres switches), Repérez le switch par lequel le ping passait entre PC1 et PC2. Choisissez une des deux interfaces connectées. Après quelques secondes, une trame STP un peu spéciale devrait apparaître sur la capture, de quoi s’agit-il ?

> 11. Attendez un instant et refaites un ping. Joignez une capture d’écran prouvant que le ping emprunte un chemin di érent cette fois-ci.

> 12.  Pourquoi faut-il attendre quelques secondes avant de pouvoir communiquer après avoir eu un changement de topologie ?

> 13.  Est-ce qu’un nouveau root bridge a été élu ? Justifiez votre réponse.

> 14.  Nous allons maintenant forcer l’élection d’un autre switch en tant que racine. Quel est le paramètre à modifier pour ce faire ?

> 15.  Modifiez ce paramètre et indiquez également la commande utilisée pour le changer. Vérifiez qu’un nouveau switch a été élu root.

> 16.  Modifiez la topologie existante de sorte à obtenir le réseau suivant :
> a. Quel switch sera élu comme racine avec ce nouveau réseau ?
> b. Quels sont les ports racine, désignés et bloqués ?
> c. Quel serait le chemin emprunté par un ping entre PC1 et PC2 ? Justifiez votre réponse avec une capture Wireshark.

> 17. Lancez une capture Wireshark entre deux switches. Montrez l’évolution du contenu des trames STP durant le processus d’élection du root. Vous pouvez redémarrer les switches afin de réinitialiser les configurations précédentes. 
