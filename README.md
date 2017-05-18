# Recette pour faire du git
Ceci est un dépôt de démonstration pour apprendre à utiliser git en collaborant sur une recette de crêpes
Merci à [gasp pour l'inspiration](https://github.com/gasp/crepes)

## 1 Setup Git
[Voir ce billet](http://build.prestashop.com/howtos/misc/set-up-your-git-for-contributing/)
A minima il faut configurer name et email

## 2 Add/Commit/Push/Pull sur la même branche du même dépôt sans conflit
```
git clone https://github.com/toutantic/recetteCrepes.git
cd recetteCrepes
git checkout develop
cp recettedescrepes.md recettedescrepes$USER.md
# Améliorer la recette
git status
git add .
git status
git commit -m "Un message explicite qui décrit la modification"
git status
git push
git pull
```

## 3 Avec des conflits

## 4 Travailler avec des branches

## 5 Travailler avec un fork de dépôt

## 6 Rebase
