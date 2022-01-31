# Auto_Backup
Backup

Cheikh  Ahmed T Diop
Optesis-CTD



- Assurez-vous que l'utilisateur odoo a l'autorisation d'écriture sur le Backup Directory
- Ce module utilise 'cURL' pour sauvegarder la base de données, alors assurez-vous que le 'cURL' est installé.
 La procédure pour installer cURL sur Ubuntu est la suivante :
   1- Mettez à jour votre Ubuntu, lancez : sudo apt update && sudo apt upgrade.
   2- Ensuite, installez cURL, exécutez : sudo apt install curl.
   3- Vérifiez l'installation de cURL sur Ubuntu en exécutant : curl --version.
Configuration simplifiée

- Cliquez sur le menu 'Database Auto Backup'
- Ouvrez les paramètres 'Database Auto Backup'
- Activez la sauvegarde automatique et remplissez le formulaire de paramètres
- Si votre site est sécurisé SSL, assurez -vous que la SSL Enabled?bascule est active (Merci tout particulièrement à Ricky pour sa note !)