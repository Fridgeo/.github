# 🧊 Fridgéo : L'Alimentation Intelligente & Responsable

> **"De la terre au frigo, sans rien gâcher."**

**Fridgéo** est une solution mobile complète qui fusionne la gestion anti-gaspillage et le soutien aux circuits courts. L'application permet de suivre la péremption de ses produits via un scan intelligent et de localiser les producteurs locaux grâce à une cartographie interactive communautaire.

---

## 🚀 Vision du Projet

Le projet repose sur deux piliers majeurs pour transformer notre façon de consommer :

1. **Scan & Save :** Réduire le gaspillage domestique en numérisant son inventaire alimentaire. L'utilisateur reçoit des notifications avant que ses produits ne périment et se voit proposer des solutions pour les consommer.
2. **Local Maps :** Reconnecter les citoyens aux producteurs. Une carte interactive recense fermes, AMAP et distributeurs automatiques de produits frais, en utilisant des données Open Source.

---

## 🛠️ Stack Technique

Pour garantir performance, scalabilité et gratuité des données, nous avons choisi les meilleures technologies actuelles :

* **Frontend Mobile :** [Flutter] – Pour une expérience fluide sur iOS et Android.
* **Base de Données :** **PostgreSQL** avec l'extension **PostGIS** pour la gestion de la géolocalisation.
* **Données Externes :**
  - **Open Food Facts API :** Pour la récupération instantanée des fiches produits.
  - **OpenStreetMap (OSM) :** Pour l'affichage des cartes et le référencement des producteurs.


* **Infrastructure :** Serveur dédié avec **Docker** pour le déploiement des services.

---

## 📋 Fonctionnalités Clés

### 🛒 Gestion du Frigo (Scan & Save)

* **Scanner intelligent :** Reconnaissance des produits via code-barres (EAN).
* **Suivi de péremption :** Alertes automatiques via notifications avant expiration.
* **Recettes suggérées :** Suggestions basées sur les ingrédients bientôt périmés.

### 📍 Circuit Court (Local Maps)

* **Carte interactive :** Visualisation des points de vente directe autour de soi.
* **Recherche spatiale :** Filtres par type de produit ou distance.
* **Crowdsourcing :** Possibilité pour les utilisateurs d'ajouter et de vérifier de nouveaux points de vente.

## 👥 L'Équipe

Le développement est assuré par un binôme complémentaire :
- [SmashBalloon](https://www.github.com/SmasBalloon)
- [Yazouv](https://www..github.com/Yazouv)
