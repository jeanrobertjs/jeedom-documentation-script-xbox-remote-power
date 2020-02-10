# Xbox Remote Power

Il s’agit d’un petit script qui peut allumer votre Xbox One à distance.

## Prérequis

Vous aurez besoin de trois choses pour que cela fonctionne:

- de Python 2 ou 3 installé
- de l'adresse IP de votre Xbox One
- du Live device ID de votre Xbox One

Pour trouver l’adresse IP de votre Xbox, rendez-vous sur Paramètres > Réseau > Paramètres avancés.

Pour trouver le Live device ID de votre Xbox One, rendez-vous sur Paramètres > Système > Informations sur la console.

## Utilisation

Exécutez le script comme suit, en remplaçant [ip address] par l’adresse IP de votre Xbox One et [live device id] par votre Live device ID de votre Xbox One.

```bash
python xbox-remote-power.py -a [ip address] -i [live device id]
```

Depuis l'interfaçe du plugin Script de jeedom cela peut donner quelque chose comme ceci en créant une commande "Xbox On" :
![Xbox On command in Jeedom](../images/XboxOnCmd.png)

et en utilisant des variables :
![Xbox On command with variables in Jeedom](../images/XboxOnCmd_with_variables.png)
