ECS avec Fargate : Fargate permet d'exécuter les conteneurs Docker sans se préoccuper des serveurs sous-jacents. Cela réduit la complexité opérationnelle et permet de se concentrer sur le développement et l’amélioration de l’application.

Elastic Load Balancer : Garantit que le trafic soit distribué de manière équilibrée entre les instances du backend, ce qui assure la résilience et l’évolutivité de l'application.

Amazon RDS : Pour une base de données fiable et gérée. RDS simplifie les sauvegardes et la gestion des mises à jour, tout en étant sécurisé et compatible avec plusieurs types de bases de données.

Amazon VPC : Pour isoler les ressources et protéger le backend et la base de données contre les accès non autorisés. Cela permet un contrôle fin des flux réseau, augmentant ainsi la sécurité de l'application.

Amazon S3 : Permet le stockage des fichiers statiques avec un accès rapide et peu coûteux.

Route 53 et CloudWatch : Route 53 assure la gestion des noms de domaine et un routage de haute disponibilité. CloudWatch offre une visibilité sur les performances de l’application et permet de réagir rapidement aux anomalies.