---
title: Comment gérer votre module en 1 clic ?
excerpt: Découvrez comment gérer votre module en 1 clic depuis votre espace client OVHcloud
slug: 1-click-module-management
section: CMS
order: 2
---

**Dernière mise à jour le 21/12/2021**

## Objectif

Les modules en 1 clic permettent l’installation facile et rapide d’un logiciel en ligne d'assistance à la création de site Internet (communément appelé « CMS »). OVHcloud vous propose les plus connus d'entre eux : WordPress, PrestaShop, Drupal et Joomla.

**Découvrez comment gérer votre module en 1 clic depuis votre espace client OVHcloud.**

> [!warning]
>
> OVHcloud met à votre disposition des services dont la configuration, la gestion et la responsabilité vous incombent. Il vous revient de ce fait d'en assurer le bon fonctionnement.
>
> Nous mettons à votre disposition ce guide afin de vous accompagner au mieux sur des tâches courantes. Néanmoins, nous vous recommandons de faire appel à un prestataire spécialisé et/ou de contacter l'éditeur du service si vous éprouvez des difficultés. En effet, nous ne serons pas en mesure de vous fournir une assistance. Plus d'informations dans la section [Aller plus loin](#aller-plus-loin) de ce guide.
>

## Prérequis

- Disposer d'une [offre d'hébergement Web Cloud](https://www.ovh.com/fr/hebergement-web/) permettant l'installation d'un module en 1 clic (seule l'offre gratuite [Start10M](https://docs.ovh.com/fr/hosting/activer-start10m/) n'est pas concernée).
- Avoir créé un module en 1 clic sur votre hébergement (Si vous n'avez pas encore effectué cette installation, suivez les instructions de ce [guide](https://docs.ovh.com/fr/hosting/modules-en-1-clic/)).
- Être connecté à votre [espace client OVHcloud](https://www.ovh.com/auth/?action=gotomanager&from=https://www.ovh.com/fr/&ovhSubsidiary=fr).

## En pratique

### Accéder à votre site

Pour accéder à la partie publique de votre site suite à l'installation d'un module en 1 clic, rendez-vous dans votre [espace client OVHcloud](https://www.ovh.com/auth/?action=gotomanager&from=https://www.ovh.com/fr/&ovhSubsidiary=fr), cliquez sur `Web Cloud`{.action}, `Hébergements`{.action}, sur l'hébergement concerné puis sur l'onglet `Modules en 1 clic`{.action}.

Cliquez ensuite sur le bouton `...`{.action} à droite de la ligne concernant votre module puis sur `Accéder au module`{.action}.

> [!primary]
>
> Si votre site ne s'affiche pas correctement suite à cette manipulation, consultez les guides OVHCLOUD liés aux hébergements mutualisés dans la section [Diagnostic](https://docs.ovh.com/fr/hosting/).
>

### Accéder à l'interface administrateur

Pour accéder à la partie de votre site réservée aux administrateurs, rendez-vous dans votre [espace client OVHcloud](https://www.ovh.com/auth/?action=gotomanager&from=https://www.ovh.com/fr/&ovhSubsidiary=fr), cliquez sur `Web Cloud`{.action}, `Hébergements`{.action}, sur l'hébergement concerné puis sur l'onglet `Modules en 1 clic`{.action}.

Cliquez ensuite sur le bouton `...`{.action} à droite de la ligne concernant votre module puis sur `Accéder à l'interface d'administration du module`{.action}.

### Retrouver l'identifiant administrateur

Cliquez sur l'onglet `Modules en 1 clic`{.action} depuis la partie `Hébergements`{.action} de votre espace client. L'identifiant administrateur de votre module apparaît dans la colonne `Login`.

Vous pouvez également rechercher l'e-mail reçu lors de la création de votre module depuis votre [espace client OVHcloud](https://www.ovh.com/auth/?action=gotomanager&from=https://www.ovh.com/fr/&ovhSubsidiary=fr) : cliquez sur votre nom en haut à droite de l'écran puis, dans le menu qui apparaît, cliquez sur `Emails de service`{.action}.

### Modifier le mot de passe de votre module

Vous pouvez modifier le mot de passe de votre module depuis votre espace client OVHcloud ou en vous rendant directement sur la page de connexion à l'espace administrateur de votre site Web.
Dans les deux cas, un e-mail de réinitialisation de mot de passe vous sera envoyé.

> [!primary]
>
> **Que faire si vous n'avez pas reçu l'e-mail de réinitialisation du mot de passe administrateur de votre site ?**
>
> Sur la boîte e-mail concernée, vérifiez les dossiers `Spams`{.action} et `Corbeille`{.action}.
>
> Vous pouvez également retrouver l'ensemble des e-mails envoyés par nos services depuis votre [espace client](https://www.ovh.com/auth/?action=gotomanager&from=https://www.ovh.com/fr/&ovhSubsidiary=fr) : cliquez sur votre nom en haut à droite de votre écran puis, dans le menu contextuel à droite de l'écran, cliquez sur `Emails de service`{.action}.
>
> **Durée de validité des liens :**
>
> - Après avoir reçu l'e-mail de changement de mot de passe, le lien de réinitialisation restera valide pendant 48 heures. 
> - Après avoir cliqué sur le lien, celui-ci n'est valide que pendant 30 minutes.
>

Pour modifier le mot de passe d'accès à l'interface d'administration de votre site **via l'espace client OVHcloud**, cliquez sur `Web Cloud`{.action}, `Hébergements`{.action}, sur l'hébergement concerné puis sur l'onglet `Modules en 1 clic`{.action}.

Cliquez ensuite sur le bouton `...`{.action} à droite de la ligne concernant votre module puis sur `Modifier le mot de passe`{.action}. Cliquez sur `Valider`{.action}. Vous recevrez sous quelques minutes par e-mail un lien de réinitialisation de votre mot de passe.

### Supprimer votre module

> [!warning]
>
> La sauvegarde de vos données fait partie des opérations essentielles à la [sécurisation de vos sites](https://docs.ovh.com/fr/hosting/secure-website/). Nous vous conseillons d'importer régulièrement et **avant toute suppression** la sauvegarde de vos données sur un support local, tel qu'une clé USB ou un disque dur externe, en suivant les instructions de ce [guide](https://docs.ovh.com/fr/hosting/exporter-son-site-web/).
>

#### Étape 1 : identifier la base de données lié à votre module <a name="step1"></a>

Pour supprimer votre module en 1 clic, vous devez commencer par identifier sa base de données de façon **certaine**. Rendez-vous pour cela dans votre [espace client OVHcloud](https://www.ovh.com/auth/?action=gotomanager&from=https://www.ovh.com/fr/&ovhSubsidiary=fr). Cliquez sur `Web Cloud`{.action}, `Hébergements`{.action}, sur l'hébergement concerné puis sur l'onglet `Bases de données`{.action}.

Si vous disposez d'une seule base de données dans cette partie de votre espace client et que vous ne possédez pas de solutions [Cloud Database](https://www.ovh.com/fr/cloud-databases/), vous pouvez considérer qu'il s'agit de celle de votre site.

Dans le cas contraire, rendez-vous dans l'onglet `Multisite`{.action}. Notez le nom du `Dossier racine` : il s'agit du répertoire dans lequel se trouvent les fichiers qui constituent votre module en 1 clic sur le serveur FTP.

Connectez-vous ensuite à [l'espace FTP de votre hébergement](https://docs.ovh.com/fr/hosting/connexion-espace-stockage-ftp-hebergement-web/). Ouvrez le `Dossier racine` trouvé précédemment dans l'onglet `Multisite`{.action} et recherchez le fichier de configuration de votre module :

- Pour WORDPRESS : **« wp-config.php »** (le nom de la base de données apparaît sous la mention **« DB_NAME »**).
- Pour JOOMLA : **« configuration.php »** (le nom de la base de données apparaît sous la mention **« public $db »**).
- Pour DRUPAL : **« settings.php »** (Pour le retrouver, rendez-vous dans le dossier **« sites »** puis **« default »**. Le nom de la base de données apparaît sous la mention **« database »**).
- Pour PRESTASHOP : **« parameters.php »** (Pour le retrouver, rendez-vous dans le dossier **« app »** puis **« config »**. Le nom de la base de votre module apparaît sous la mention **« database_name »**).

#### Étape 2 : sauvegarder votre module

Pour sauvegarder votre site, suivez les instructions de ce [guide](https://docs.ovh.com/fr/hosting/exporter-son-site-web/), afin de récupérer à la fois ses fichiers sur l'espace FTP de votre hébergement et sa base de données.

#### Étape 3 : supprimer votre module

> [!alert]
>
> La suppression de votre module en 1 clic et de sa base de données entraîneront également celle de **l'ensemble de leurs sauvegardes**. Les données supprimées ne pourront pas être récupérées par la suite.
>

Pour supprimer votre module en 1 clic, rendez-vous dans votre [espace client OVHcloud](https://www.ovh.com/auth/?action=gotomanager&from=https://www.ovh.com/fr/&ovhSubsidiary=fr), cliquez sur `Web Cloud`{.action}, `Hébergements`{.action}, sur l'hébergement concerné puis sur `Modules en 1 clic`{.action}.

Cliquez ensuite sur le bouton `...`{.action} à droite de la ligne désignant votre module puis sur la commande `Supprimer le module`{.action}.

> [!warning]
>
> La suppression de votre module 1 clic **n'entraînera pas automatiquement celle de sa base de données**. Si vous lancez l'installation d'un nouveau CMS sans avoir supprimé préalablement la base de données du précédent (et que votre hébergement ne permet pas la création automatique d'une nouvelle base), le message « [Une erreur s’est produite lors du chargement des informations (You need at least one free database)](https://docs.ovh.com/fr/hosting/erreurs-frequentes-modules-en-1-clic/#une-erreur-sest-produite-lors-du-chargement-des-informations-you-need-at-least-one-free-database) » s'affichera sur votre espace client.
>
> Si vous disposez d'un abonnement [Kimsufi](https://www.kimsufi.com/fr/hosting.xml) ou [Perso](https://www.ovhcloud.com/fr/web-hosting/personal-offer/) ou si vous avez déjà créé quatre bases de données sur votre hébergement [Pro](https://www.ovhcloud.com/fr/web-hosting/professional-offer/) ou [Performance](https://www.ovhcloud.com/fr/web-hosting/performance-offer/), vous devrez donc supprimer la base de données identifiée à [l'étape 1](#step1) **AVANT** de pouvoir créer un nouveau module en 1 clic.
>

Pour finaliser la suppression de votre module, rendez-vous donc dans l'onglet `Bases de données`{.action}, toujours dans la partie `Web cloud`{.action}, `Hébergements`{.action} et dans l'hébergement concerné sur votre [espace client OVHcloud](https://www.ovh.com/auth/?action=gotomanager&from=https://www.ovh.com/fr/&ovhSubsidiary=fr) puis cliquer sur `...`{.action} à droite de la ligne désignant la base et sur le bouton `Supprimer la base de données`{.action}.

Avant de relancer l'installation d'un nouveau module, vérifiez que les tâches de suppression demandées précédemment ont bien été finalisées via l'onglet `Tâches en cours`{.action}.

### Bonnes pratiques

Sécurisez votre site en suivant les instructions de ce [guide](https://docs.ovh.com/fr/hosting/secure-website/).

Ajoutez des outils de test de type CAPTCHA sur les formulaires de votre site.

N'installez pas sur votre site de plugins ou de templates qui n'ont pas été recommandés par les communautés officielles de votre CMS : 

- [Wordpress](https://wpfr.net/){.external}
- [Joomla!](https://forum.joomla.fr/){.external}
- [Drupal](https://www.drupal.fr/forum){.external}
- [Prestashop](https://www.prestashop.com/forums/){.external}

## Aller plus loin <a name="aller-plus-loin"></a>

[Résoudre les erreurs les plus fréquentes liées aux modules en 1 clic](https://docs.ovh.com/fr/hosting/erreurs-frequentes-modules-en-1-clic/).

Pour des prestations spécialisées (référencement, développement, etc), contactez les [partenaires OVHcloud](https://partner.ovhcloud.com/fr/).

Échangez avec notre communauté d'utilisateurs sur <https://community.ovh.com/>.