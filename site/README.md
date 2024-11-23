
# Guide d'installation pour le site

Le site fourni est installable sur votre WordPress.  
Nous proposons deux méthodes d'importation différentes.

## Acceder à la version déployée du site:
Une version du site a été déployée sur [InfinityFree](https://www.infinityfree.com/)
Vous pouvez cliquer ici pour acceder au site déployé: [Notre site de ecommerce](https://bacho-design.42web.io/wordpress/)

## Credentials pour le compte administrateur du site :
- **Utilisateur** : `thierry`  
- **Mot de passe** : `password`  

---

## Méthode 1 : Importation avec LocalWP (recommandée)

### Prérequis :
1. Avoir LocalWP installé :  
   - Rendez-vous sur le site [LocalWP](https://localwp.com/).  
   - Téléchargez la version correspondant à votre système d'exploitation.  
   - Installez LocalWP sur votre machine.

### Étapes pour importer et tester le site :
1. Ouvrez **Local** (LocalWP).  
2. Cliquez sur le bouton **+** en bas à gauche.  
3. Sélectionnez l'option **Select an Existing Zip**.  
4. Choisissez le fichier `quiferou-localwp.zip`.  
5. Donnez un nom au site local, par exemple `quiferou`, et laissez les configurations par défaut.  
6. LocalWP importera et configurera automatiquement le site.  

### Accès au site :
- Une fois l'importation terminée :  
  - Cliquez sur **Open Site** pour visualiser le site.  
  - Cliquez sur **WP Admin** pour accéder à l'administration.  

### Avantages :
- Le site est fourni tel quel.  
- Les versions de PHP, MySQL, et autres éléments sont automatiquement conformes si vous utilisez la dernière version de LocalWP.  
- Pas besoin de compétences avancées en WordPress.  

### Inconvénients :
- Nécessite d'installer LocalWP sur votre machine.  

---

## Méthode 2 : Importation avec WPVivid

### Prérequis :
1. Avoir un site WordPress opérationnel sur un serveur ou un environnement local.  
2. Installer le plugin **WPVivid Backup Plugin** :
   - Connectez-vous à l'administration WordPress.  
   - Allez dans **Extensions > Ajouter**.  
   - Recherchez **WPVivid Backup Plugin**.  
   - Installez et activez le plugin.

### Étapes pour importer et restaurer le site :
1. Téléchargez le fichier de sauvegarde fourni : `quiferou-wpvivid.zip`.  
2. Dans WordPress, allez dans **WPVivid Backup > Sauvegarder & Restaurer**.  
3. Descendez, dans les onglets en bas, et ouvre l'onglet **Televerser**
4. Cliquez sur **Téléverser un fichier de sauvegarde**.  
5. Sélectionnez le fichier `quiferou-vivid.zip` depuis votre ordinateur.  Puis cliquez sur **Upload** juste en bas
6. Une fois le fichier importé, accédez à l'onglet **Restaurer** dans WPVivid.  
7. Cliquez sur **Restaurer** pour finaliser l'importation.
**Note:** Vous devrez cliquer sur ***Restaurer* 2 fois**, puis, une validation vous sera demandée, et pour cela vous cliquerez sur **_OK_ par 3 fois**  


### Avantages :
- Plus rapide si un environnement WordPress est déjà en place.  
- Fonctionne directement sur un serveur ou en local sans dépendance à LocalWP.  

### Inconvénients :
- Nécessite un site WordPress opérationnel.  
- Dépendance au plugin WPVivid.  

---

## Comparatif des deux méthodes :

| **Critères**               | **LocalWP**                       | **WPVivid**                        |
|----------------------------|-----------------------------------|------------------------------------|
| **Facilité de mise en place** | Simple avec LocalWP, mais nécessite une installation. | Requiert un site WordPress actif.  |
| **Compatibilité**           | Assure des versions compatibles de PHP/MySQL. | Utilise la configuration existante. |
| **Souplesse**               | Pas besoin de plugins supplémentaires. | Compatible avec les serveurs en ligne. |
| **Complexité technique**    | Adapté aux débutants.            | Requiert quelques manipulations. |

 
