## Guide pour programmer le mur :

Commencez par t�l�charger et extraire le dossier sur votre bureau.
1. Ajoutez Nightbot � votre cha�ne si vous ne l'avez pas d�j� fait: 
https://beta.nightbot.tv/

2. Installez le syst�me API dans NightBot en suivant ces instructions
https://community.nightdev.com/t/customapi-quote-system/7871

3. Une fois que vous avez fait cela, vous devez acc�der aux commandes personnalis�es.
https://beta.nightbot.tv/commands/custom
- Copiez l'ID se trouvant dans "!addquote". Vous en aurez besoin dans la prochaine commande.

4. Cr�ez une nouvelle commande appel�e !wall (ou !set) et modifier pour que tous le monde puisse utiliser la commande.

5. Puis changez la commande en ceci - assurez-vous de remplacer [VOTRE ID ICI] par votre id, supprimez les crochets [] ---

$https://twitch.center/customapi/addquote?token=[VOTRE ID ICI]&data=$(userid))

6. Vous devez remplacer [VOTRE ID ICI] par l'id que vous avez copi�e � l'�tape 3 (notez que vous devez �galement supprimer les crochets []).

7. La derni�re chose dont vous avez besoin est une cl� Google API, suivez ces instructions:
  - https://www.slickremix.com/docs/get-api-key-for-youtube/
  - https://developers.google.com/youtube/v3/getting-started
  - Assurez-vous d'activer "Youtube Data API v3"

8. Ins�rez l'id de NightBot (ce n'est pas celle de l'�tape 3 mais celle que vous trouvez dans !quote) et la cl� API de Google dans le fichier config.js et vous �tes pr�t.

9. Vous devez ouvrir le fichier html dans le bloc-notes pour pouvoir le faire.

10. Ex�cutez votre commande en visitant ce lien avec votre id ins�r� pour v�rifier que le mur fonctionne.( vous devez suprimer les crochets ) https://twitch.center/customapi/addquote?token=[VOTRE ID ICI]&data=UC0aQ9apFPUadKr7ZSlVn5mA
