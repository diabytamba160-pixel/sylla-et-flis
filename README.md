# Boutique Sylla & Fils

## Modifier les produits depuis un téléphone ou un ordinateur

1. Ouvrir l'adresse du site suivie de `/admin/`, puis toucher **Ouvrir l'administration**. On peut aussi ouvrir directement [Pages CMS](https://app.pagescms.org/).
2. Se connecter avec un compte GitHub et sélectionner le dépôt `diabytamba160-pixel/Sylla-et-flis`.
3. Ouvrir **Catalogue des produits** pour modifier un produit ou en ajouter un. Les champs permettent de changer son nom, son prix en FCFA, sa photo, sa description, sa catégorie et le numéro WhatsApp associé. Pour corriger une photo d'article, ouvrir la fiche concernée et remplacer le champ **Photo du produit** par une image existante ou une photo téléversée depuis l'appareil.
4. Ouvrir **Image de la page d'accueil** pour remplacer la grande photo de la bannière en haut de la page.
5. Enregistrer les changements dans Pages CMS. Ils sont publiés avec le prochain déploiement du site.

### Autoriser les membres de la boutique

Le propriétaire du dépôt doit ajouter chaque administrateur comme collaborateur GitHub et lui accorder le rôle **Write** (accès en écriture). Chaque membre se connecte ensuite à Pages CMS avec son propre compte GitHub. Ne partagez pas le mot de passe d'un compte personnel.

Pages CMS utilise le fichier `.pages.yml`, les données du catalogue dans `produits.json` et la photo de la bannière dans `site.json`. Les photos téléversées sont enregistrées dans `images/`.
