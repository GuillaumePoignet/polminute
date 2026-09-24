# Polminute — pages publiques

Les trois pages que TikTok exige de toute application utilisant la Content
Posting API : site, politique de confidentialité, conditions d'utilisation.
Elles doivent être servies depuis une adresse dont on prouve le contrôle,
d'où ce dépôt public.

Rien de sensible ici. Le moteur et la matière sont dans deux dépôts privés.

## Mise en ligne

**Settings → Pages →** Source `Deploy from a branch`, branche `main`,
dossier `/ (root)`.

Adresse obtenue : <https://guillaumepoignet.github.io/polminute/>

## Vérification TikTok

Le portail développeur fournit un fichier `tiktok<clé>.txt` à déposer à la
racine de ce dépôt. Une fois poussé, il est servi à la racine du site et le
bouton *Verify* passe au vert.

## Les trois adresses à déclarer

| Champ du portail | Adresse |
|---|---|
| Website URL | `https://guillaumepoignet.github.io/polminute/` |
| Privacy Policy URL | `https://guillaumepoignet.github.io/polminute/confidentialite.html` |
| Terms of Service URL | `https://guillaumepoignet.github.io/polminute/conditions.html` |
