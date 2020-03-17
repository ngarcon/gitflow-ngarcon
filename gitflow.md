# Construire son gitflow

## Premières étapes

### Initialiser le projet

Au lancement d'un nouveau projet il faut initier son _versionnage_ 

```sh
git init
```

Ceci crée **en local** une première version du projet. Il faut ensuite établir un premier lien avec Github, pour les échanges futurs entre le **git local** et le **git remote** (ou **distant**).

```sh
git remote add origin ssh@ecetera/ecetera.git
```

Vient le tour du premier commit ( et LE SEUL dans un gitflow classique) : c'est le fameux `Init` ou `Initial commit`


```sh
git add .
git commit -m "Initial commit"
git push origin master
```


## Sources 

https://www.atlassian.com/git/tutorials/comparing-workflows/gitflow-workflow