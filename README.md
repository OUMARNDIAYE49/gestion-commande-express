## Gestion des Commandes

Ce projet implémente un composant métier en JavaScript pour la gestion des commandes. Le composant permet de gérer les opérations CRUD (Créer, Lire, Mettre à jour, Supprimer) sur les commandes. Les principales entités modélisées sont les commandes, les clients et les articles commandés.


1. Classe Customer

Attributes:
- name (string): Name of the client.
- email (string): Email of the client.
    
Methods:
- createCustomer(): Creates a new client with the provided data.
- getCustomer(): Returns the client's information.
- editCustomer(): Updates the client's information with the provided data.
- deleteCustomer(): Deletes the client.

2. Classe product
Attributes:
- name (string): Name of the article.
- quantity (string): Description of the article.
- price (number): Price of the article.

Methods:
- createProduct(): Creates a new article with the provided data.
- getProduct(): Returns the article's information.
- editProduct(): Updates the article's information with the provided data.
- deleteProduct(): Deletes the article.

3. Order Class

Attributes:
- customer (Client): Instance of the Client class representing the client who placed the order.
- amount (Array<Article>): List of Article instances that are part of the order.
- orderDate (Date): Date when the order was placed.
- status (string): Status of the order (e.g., 'Pending', 'Shipped', 'Delivered').

Methods:
- createOrder(orderData): Creates a new order with the provided data.
- getOrder(): Returns the order's information.
- editOrder(newOrderData): Updates the order's information with the provided data.
- deleteOrder(): Deletes the order.
- addItem(article): Adds an article to the order.
    
### Prérequis
Avant de commencer, assurez-vous d'avoir les éléments suivants installés sur votre machine :

- Node.js (version 14 ou supérieure) : Utilisé pour exécuter le projet JavaScript. Télécharger Node.js
- npm (Gestionnaire de paquets de Node.js) : Généralement inclus avec Node.js, utilisé pour installer les dépendances.
- Git : Utilisé pour cloner le dépôt et gérer le contrôle de version. Télécharger Git

### Optionnel :
- Postman (ou tout autre outil de requête API) : Pour tester les API si nécessaire. Télécharger Postman

### Installation
Pour installer et exécuter le projet, suivez ces étapes :

### Clonez le dépôt
git clone ````https://github.com/OUMARNDIAYE49/gestion-commande-express.git````

### Naviguez dans le répertoire du projet
cd ```gestion-commande-express```

### Installez les dépendances (si nécessaire)
- initialisé ```git init```
- Express ```npm install express```
- body-parser ```npm install body-parser```
- nodemon ```npm install nodemon```

### UTilisation
Pour démarrer l'application, exécutez la commande suivante 
 ```npm start ```

### Diagramme de  Classe

![Image diagramme de classe](./assets/image-diagramme-class.jpeg)


### Authors
[Oumar Djiby Ndiaye ](https://github.com/OUMARNDIAYE49/gestion-commande-express.gitt)