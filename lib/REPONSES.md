

1.Un StatelessWidget affiche toujours la même chose, il ne change pas.
Un StatefulWidget peut changer pendant que l'app tourne, par exemple quand on appuie sur un bouton.
Exemple dans mon projet :
- StatelessWidget : LoginPage, HomePage, MyDrawer.
- StatefulWidget : AnimePage, parce que le compteur change.

2.Le nombre augmente en arrière-plan, mais l'écran ne change pas.
Sans setState, Flutter ne sait pas qu'il doit redessiner la page.

3.
Commit : je sauvegarde mon travail sur mon PC, avec un message.
Sync Changes : j'envoie cette sauvegarde sur GitHub.
Sans Sync, GitHub ne voit rien.