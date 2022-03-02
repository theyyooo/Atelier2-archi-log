# Atelier2-archi-log

## Qu’est ce que des Services Web Full Rest ? 

## Quelles sont les contraintes imposées par ce type de service ?

## Qu’est ce qu’un gestionnaire de dépendance ? 

## Maven est-il le seul ? 

## Quel est l’avantage d’utiliser un gestionnaire de dépendances ? 

## Quelles sont les grandes étapes de fonctionnement de Maven ?

## Qu’est ce qu’une application classique Entreprise Java Application ? 

## Donner un exemple d’usage avec web service, JSP, JavaBean, EJB et JMS.

## Qu’est ce que Spring ? qu’apporte Spring boot vis-à-vis de Spring ?

## Qu’est ce que Spring Boot ? 

## Quels sont les points communs/différences entre JEE et Spring Boot ?

## Qu’est ce qu’une annotation ? 

## Quels apports présentent les Annotations ?

## Comment fait-on pour créer un Web Service Rest avec Spring Boot ?

## Qu’est ce qu’un container de Servlet ? 
Un container de Servlet est un logiciel qui exécute des Servlet (Tomcat est le plus populaire).

## Comment fonctionne un containeur de Servlet ?
Un container de Servlet 

## Expliquer la philosophie « Convention over Configuration » de Spring boot ?
Il s'agit d'une philosiphie qui tend à faire diminuer le nombre de décisions qu'un développeur doit prendre : il doit se concentrer sur les aspects non conventionnels de l'application. Cela permet de réduire le nombre de fichiers de configuration et de configurer par défaut les applications en se basant sur les standards du milieu.

## Expliquer ce qu’il se passe lors de l’exécution «SpringApplication .run(App.class,args) »
L'exécution «SpringApplication.run(App.class,args)» permet de créer le contexte de l’application, instancier les beans enregistrés et effectuer le
packaging demandé.

## Qu’est ce qu’un DAO ? 
Un DAO (Data Access Object, ou Objet d'Accès aux Données) est un patron de conception (c'est-à-dire un modèle pour concevoir une solution) utilisé dans les architectures logicielles objet.

## En quoi est-ce intéressant d’utiliser ce pattern ? 
Utiliser ce pattern, tout d'abord, est reconnu comme bonne pratique en réponse à un problème de conception d'un logiciel : le pattern décrit les grandes lignes d'une solution, qui peuvent ensuite être modifiées et adaptées en fonction des besoins.

## Qu’est ce qu’un Singleton ?
Un singleton est un patron de conception (design pattern) dont l'objectif est de restreindre l'instanciation d'une classe à un seul objet (ou bien à quelques objets seulement). Il est utilisé lorsqu'on a besoin exactement d'un objet pour coordonner des opérations dans un système. 

## Que permet de réaliser les Entity dans SpringBoot ? 
Les Entity dans SpringBoot agisse pour une connexion à la base de données en indiquant, via l'annotation @Entity, une classe persistante. Le service JPA va ainsi créer une table correspondante à cette classe

## Est-ce spécifique à SpringBoot ?
Non, nous pouvons en trouver également avec Symfony par exemple.

## Combien d’instances avez-vous crées lors de l’usage de «Service» en Spring boot? Pourquoi ?
Nous avons créé une seule instance lors de l'usage de "Service" en Springboot, il s'agit de l'instance Singleton.

## Que fournit le CRUD Repository de Spring boot ?
Le CRUD Repository de Springboot contenant des méthodes permettant de réaliser les différentes opérations CRUD.

## Que sont les CRUD ?
Les CRUD (create - read - update - delete) représentent les quatre fonctions de base du stockage persistant. CRUD fait généralement référence aux opérations effectuées dans une base de données ou un magasin de données, mais peut également s'appliquer aux fonctions de niveau supérieur d'une application.

## Qui réalise l’implémentation de la méthode findBy Property lors de la création d’un repository en Spring Boot ?
C'est le service qui réalise l'implémentation de la méthode findBy Property lors de la création d'un repository en Springboot

## Comment gère-t-on les relations One To One, One to Many et Many to Many avec JPA ?
 - One-To-One : sans table d'association (il nous faut utiliser le couple d'annotation JPA @OneToOne et @JoinColumn), avec attribut inverse ou avec table d'association (il faut encore utiliser l'annotation @OneToOne mais il va falloir la coupler à une annotation @JoinTable afin d'y spécifier les informations utiles à la jointure).
 - One-To-Many : sans table d'association (la clé de jointure, permettant la mise en relation, sera portée par la table associée à la classe) ou avec table d'association (une 3e table servira à stocker les paires de clés de mise en relations).
 - Many-To-Many : avec table d'association (il faut utiliser l'annotation @ManyToMany qu'il va falloir coupler à une annotation @JoinTable afin d'y spécifier les informations utiles à la table de jointure).

## Qu’est ce qu’une Architecture SOA ? Qu’est ce qu’une architecture Micro Service ?
- L'architecture orientée services (ou SOA, Service-Oriented Architecture) est un modèle de conception qui rend des composants logiciels réutilisables, grâce à des interfaces de services qui utilisent un langage commun pour communiquer via un réseau.
- Une architecture de microservices se différencie d'une approche monolithique classique par le fait qu'elle décompose une application pour en isoler les fonctions clés. Chacune de ces fonctions est appelée « service » et ces services peuvent être développés et déployés indépendamment les uns des autres (faible couplage).

## Il y a-t-il d’autres architectures existantes ? 
D'autres architectures existent :
- Les architectures en appel et retour
- Les architectures en couche
- Les architectures centrées sur les données
- Les architectures en flots de données (architecture SOA & microservices)
- Les architectures orientées objets
- Les architectures orientées agents

## Quels sont leurs avantages/inconvénients ?
| Tableau comparatif    |          Avantages          |         Inconvénients         |
| :---------- | :--------------------------: | :----------------------: |
| architectures en appel et retour |  |   |
| architectures en couche     |                |           |
| architectures centrées sur les données      |                |         |
| architectures en flots de données    |               |          |
| architectures orientées objets     |                |           |
| architectures orientées agents      |               |           |
