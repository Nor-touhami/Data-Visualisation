

##### Voici un dashboard sous **R Shiny**, permettant d'analyser et de visualiser des données conçu pour explorer l'industrie mondiale du jeu vidéo à partir du dataset historique `vgsales.csv`. Il permet de transformer des milliers de lignes de données brutes en indicateurs visuels clairs, dynamiques et exploitables pour comprendre les grandes dynamiques du marché.

###### *Comme je n'ai pas réussi a publier le dashboard je vais vous le presenter avec des captures d'écran*


### Page d'Accueil
![[Pasted image 20261022180043.png]]### Les 5 Onglets Cles

1. **Vue Globale & Tendances**
    
    - **Role :** Offrir une vue macroeconomique (ventes globales cumulees, top editeur) et historique (pic de l'industrie en 2008, Top 10 mondial des jeux).
        
2. **Analyse par Plateforme**
    
    - **Role :** Comparer les performances des consoles (PlayStation, Xbox, Nintendo, PC) et leur repartition geographique (NA, EU, JP).
        
3. **Genres & Marchés**
    
    - **Role :** Identifier les genres les plus rentables (Action, Sports, etc.) et analyser les preferences culturelles selon les regions du monde.
        
4. **Fiche Jeu & Recherche**
    
    - **Role :** Permettre une interrogation ciblee via un moteur de recherche pour auditer un jeu specifique et ses ventes regionales.
        
5. **Tableau Brut**
    
    - **Role :** Explorer la base de donnees ligne par ligne grace a un tableau interactif filtrable, triable et exportable.

### Barre Latérale : Les Filtres Globaux

Situés sur la gauche de l'interface, ces filtres agissent simultanément sur l'ensemble des onglets et réactualisent tous les graphiques et messages en temps réel :

- **Filtre par Genre :** Permet de cibler un genre spécifique (Action, Sports, Role-Playing, etc.) ou de conserver une vue d'ensemble ("Tous").
    
- **Filtre par Plateforme :** Permet d'isoler une console particulière (PS3, X360, Wii, PC, etc.) ou d'analyser l'ensemble des supports ("Toutes").
    
- **Filtre par Période (Années) :** Un curseur temporel ajustable (de 1980 à 2020) pour restreindre l'analyse à une décennie ou une époque précise.

## Page 2: 

![[Pasted image 20261022180505.png]]L'onglet Analyse par Plateforme a pour objectif de comparer les performances commerciales des différentes consoles de jeux vidéo et d'analyser leur ancrage géographique. Il présente un bilan global identifiant la console leader du marché, un diagramme en barres classant les supports les plus vendus, ainsi qu'un graphique en barres empilées détaillant la répartition des ventes par région pour chaque plateforme.

## Page 3: 

![[Pasted image 20261022180718.png]]L'onglet Genres & Marchés a pour objectif d'analyser la rentabilité des différents genres de jeux vidéo et de comparer les préférences de consommation selon les régions du monde. Il présente un diagramme en barres classant les genres selon leur volume de ventes global, ainsi qu'un graphique croisé comparant en détail les performances régionales (Amérique du Nord, Europe, Japon et autres) pour chaque catégorie.

## Page 4: 
![[Pasted image 20261022180809.png]]L'onglet Genres & Marchés a pour objectif d'analyser la rentabilité des différents genres de jeux vidéo et de comparer les préférences de consommation selon les régions du monde. Il présente un diagramme en barres classant les genres selon leur volume de ventes global, ainsi qu'un graphique croisé comparant en détail les performances régionales (Amérique du Nord, Europe, Japon et autres) pour chaque catégorie.

## Page 5: 
![[Pasted image 20261022180905.png]]L'onglet **Tableau Brut** a pour objectif de permettre une exploration granulaire et complète de l'ensemble des données du projet. Il présente un tableau tabulaire interactif mis à jour en temps réel selon les filtres globaux, muni d'outils de recherche textuelle, de filtres par colonne, de options de tri et d'une pagination pour analyser l'intégralité du dataset ligne par ligne.