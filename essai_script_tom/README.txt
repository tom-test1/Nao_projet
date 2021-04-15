Pour run le code, il faut:
copier le dossier dans le nao (/home/nao/.local/share/PackageManager/apps/)
puis dans un terminal :
ssh nao@"adresseIPduPepper" 
puis
cd /home/nao/.local/share/PackageManager/apps/essai_script_tom
puis 
/.local/share/PackageManager/apps/essai_script_tom $ python app.py


et le programme devrait fonctionner.
De meme pour l'autre programme, il faut juste changer essai_scrip_tom par essai_scrip_tom_non_ethique




Le code quand a lui est assez explicite, le fichier .top correspond aux input/output vocaux (echanges avec l'utilisateur) et le fait de 
passer une variable à 1 fait rentrer le programme dans la fonction en question. (ex : $test=1 var exécuter la fonction on_event_test)


