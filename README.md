## Guide pour programmer le mur :

Commencez par télécharger et extraire le dossier sur votre bureau.
1. Ajoutez Nightbot à votre chaîne si vous ne l'avez pas déjà fait: 
https://beta.nightbot.tv/

2. Installez le système API dans NightBot en suivant ces instructions
https://community.nightdev.com/t/customapi-quote-system/7871

3. Une fois que vous avez fait cela, vous devez accéder aux commandes personnalisées.
https://beta.nightbot.tv/commands/custom
- Copiez l'ID se trouvant dans "!addquote". Vous en aurez besoin dans la prochaine commande.

4. Créez une nouvelle commande appelée !wall (ou !set) et modifier pour que tous le monde puisse utiliser la commande.

5. Puis changez la commande en ceci - assurez-vous de remplacer [VOTRE ID ICI] par votre id, supprimez les crochets [] ---

$https://twitch.center/customapi/addquote?token=[VOTRE ID ICI]&data=$(userid))

6. Vous devez remplacer [VOTRE ID ICI] par l'id que vous avez copiée à l'étape 3 (notez que vous devez également supprimer les crochets []).

7. La dernière chose dont vous avez besoin est une clé Google API, suivez ces instructions:
  - https://www.slickremix.com/docs/get-api-key-for-youtube/
  - https://developers.google.com/youtube/v3/getting-started
  - Assurez-vous d'activer "Youtube Data API v3"

8. Insérez l'id de NightBot (ce n'est pas celle de l'étape 3 mais celle que vous trouvez dans !quote) et la clé API de Google dans le fichier config.js et vous êtes prêt.

9. Vous devez ouvrir le fichier html dans le bloc-notes pour pouvoir le faire.

10. Exécutez votre commande en visitant ce lien avec votre id inséré pour vérifier que le mur fonctionne.( vous devez suprimer les crochets ) https://twitch.center/customapi/addquote?token=[VOTRE ID ICI]&data=UC0aQ9apFPUadKr7ZSlVn5mA
