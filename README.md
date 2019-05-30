# AtlantaBot

Atlanta est un bot Discord open source très complet développé par Androz!

## Fonctionnalités

Atlanta est un bot Discord open source développé par Androz2091. Si vous souhaitez réutiliser du code venant de ce bot, veuillez mettre une **star** au git.

Atlanta propose :

- plus de 70 commandes faites en class (musique, économie, administration, modération, et +)
- la traduction en anglais 🇬🇧
- la gestion des rewards via les votes sur DBL grâce à un serveur express
- les commandes en messages privés
- un superbe dashboard web très complet !
- et bien plus !

Fonctionnalités à venir :

- Ajout des shards
- Ajout des menus de rôles
- Ajout des sauvegardes de serveurs

## Installation

Il est possible de lancer Atlanta depuis votre propre serveur. Pour qu'Atlanta fonctionne correctement, veillez à obtenir les bonnes clefs d'API, à installer les node modules, et à modifier le fichier de configuration.

> Si vous ne comptez pas modifier le bot, une version en ligne en permanence est disponible : [Atlanta sur Discordbots.org](https://discordbots.org/bot/557445719892688897), que vous pouvez inviter sur votre propre Discord.

### Node modules

Pour installer les node modules, tapez `npm install`. Une fois cela fait, si vous n'avez pas d'erreur, félicitations, vous avez correctement installé les node modules !

### Fichier de configuration

Vous devez renommer le fichier `config.js.example` en `config.js` et le compléter avec vos informations :

> - `token` : le token de votre bot Discord
> - **Support**
>   - `id` : l'identifiant du serveur support de votre bot
>   - `logs` : l'identifiant du salon des logs (lorsqu'un serveur est rejoint)
>   - **Roles**
>       - `donator` : le rôle donateurs du serveur support
>       - `staff` : le rôle staff du serveur support
>       - `moderator` : le rôle donateurs du serveur support
>       - `contributors` : le rôle contributeurs du serveur support
>       - `friends` : le rôle amis du serveur support
> - `Préfixe` : le préfixe du bot
> - **Embed**
>   - `color` : la couleur du liserai des embeds (doit être hexadécimale)
>   - `footer` : le texte qui s'affiche en bas des embeds
> - `default_language` : le language par défaut des nouveaux Discord (`en` ou `fr`)
> - `owner` : l'identifiant Discord du propriétaire du bot
> - **Server**
>   - `port` : le port du serveur express
>   - `sessionPassword` : le mot de passe utilisé pour les sessions express
>   - **Votes**
>       - `auth` : le mot de passe du webhook (qui doit être configuré dans les paramètres sur discordbots.org)
>       - `channel` : le salon dans lequel seront envoyés les messages de votes
>   - **oAuth2**
>       - `secret` : le "client secret" qui se trouve dans la page de gestion de votre bot, general informations
>       - `websiteURL` : la page d'accueil du site (par exemple : `http://localhost:30000`)
> - **apiKeys**
>   - `fortnite` : votre clé d'api [Fortnite Tracker](https://fortnitetracker.com/site-api)
>   - `dbl` : votre clé d'api [DiscordBots](https://discordbots.org/api/docs#mybots)
>   - `simple_youtube_api` : votre clé d'api [YouTube v3](https://console.developers.google.com)
>   - `yandex` : votre clé d'api [yandex](https://passport.yandex.com/auth?retpath=https://tech.yandex.com/translate/) (utilisée pour la commande de traduction)
>   - `anidiots` : votre clé d'api dev.anidiots.guide (utilisée pour les messages de bienvenue & messages d'au revoir)

### Lancer le bot

Pour démarrer le bot, tapez simplement `node atlanta.js` !

### Inviter le bot

Pour inviter le bot, vous devez générer une URL oauth que vous trouverez sur discordapp.com dans la page de gestion de votre bot (oauth2) !
Ou utiliser [un site de calculateur de permissions Discord](https://finitereality.github.io/permissions-calculator/?v=0)

## Support

Si vous avez besoin d'aide, nous sommes disponible pour vous répondre !

[Discord](https://discordapp.com/invite/Ntv5bJR)  
[Twitter](https://twitter.com/AtlantaBot)